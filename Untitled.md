

```
import java.util.*;

class Solution {
    public List<Integer> distanceK(TreeNode root, TreeNode target, int k) {
        List<Integer> answer = new ArrayList<>();
        if (root == null || target == null || k < 0) {
            return answer;
        }

        List<TreeNode> path = new ArrayList<>();
        if (!findPath(root, target, path)) {
            return answer;
        }

        collectDown(target, k, null, answer);

        for (int i = path.size() - 2; i >= 0; --i) {
            int distanceUp = path.size() - 1 - i;

            if (distanceUp == k) {
                answer.add(path.get(i).data);
            }

            int remaining = k - distanceUp - 1;
            if (remaining >= 0) {
                TreeNode ancestor = path.get(i);
                TreeNode childOnTargetPath = path.get(i + 1);
                TreeNode otherSubtree;

                if (ancestor.left == childOnTargetPath) {
                    otherSubtree = ancestor.right;
                } else {
                    otherSubtree = ancestor.left;
                }

                collectDown(otherSubtree, remaining, null, answer);
            }
        }

        return answer;
    }

    private boolean findPath(TreeNode node, TreeNode target, List<TreeNode> path) {
        if (node == null) {
            return false;
        }

        path.add(node);
        if (node == target) {
            return true;
        }

        if (findPath(node.left, target, path) || findPath(node.right, target, path)) {
            return true;
        }

        path.remove(path.size() - 1);
        return false;
    }

    private void collectDown(TreeNode node, int distance, TreeNode blocked,
                             List<Integer> answer) {
        if (node == null || node == blocked || distance < 0) {
            return;
        }

        if (distance == 0) {
            answer.add(node.data);
            return;
        }

        collectDown(node.left, distance - 1, blocked, answer);
        collectDown(node.right, distance - 1, blocked, answer);
    }
}
```