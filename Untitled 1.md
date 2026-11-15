

```

class Solution {

    public int minTime(Node root, int target) {

        // K : Node || V : ParentNode
        Map<Node, Node> map = new HashMap<>();

        // 1. Build Parent Map
        Node targetNode = inOrder(root, map, target);

        // 2. BFS FROM TARGET
        Queue<Node> que = new LinkedList<>();
        Set<Node> visited = new HashSet<>();

        que.offer(targetNode);
        visited.add(targetNode);

        int time = 0;

        while (!que.isEmpty()) {

            int n = que.size();
            boolean burned = false;

            while (n-- > 0) {

                Node curr = que.poll();

                // LEFT
                if (curr.left != null && !visited.contains(curr.left)) {
                    que.offer(curr.left);
                    visited.add(curr.left);
                    burned = true;
                }

                // RIGHT
                if (curr.right != null && !visited.contains(curr.right)) {
                    que.offer(curr.right);
                    visited.add(curr.right);
                    burned = true;
                }

                // PARENT
                if (map.containsKey(curr) && !visited.contains(map.get(curr))) {
                    que.offer(map.get(curr));
                    visited.add(map.get(curr));
                    burned = true;
                }
            }

            if (burned) {
                time++;
            }
        }

        return time;
    }

    // Build Parent Map + Find Target Node
    private Node inOrder(Node root, Map<Node, Node> map, int target) {

        if (root == null) return null;

        Node targetNode = null;

        if (root.data == target) {
            targetNode = root;
        }

        if (root.left != null) {
            map.put(root.left, root);
        }

        Node left = inOrder(root.left, map, target);

        if (root.right != null) {
            map.put(root.right, root);
        }

        Node right = inOrder(root.right, map, target);

        if (targetNode != null) return targetNode;
        if (left != null) return left;

        return right;
    }
}

```