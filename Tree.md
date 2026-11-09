https://takeuforward.org/blogs/data-structure-and-algorithm/binary-tree-data-structure

Binary Tree
Binary Search Tree
General Tree


LCA
Diameter 
BFS
DFS

Diameter 
1. By Node
2. By Edge





| Term                 | Meaning                                                    |
| -------------------- | ---------------------------------------------------------- |
| **Node**             | An individual element containing data and child references |
| **Root**             | The topmost node from which the tree begins                |
| **Edge**             | A connection between a parent and child                    |
| **Parent**           | A node directly connected above another node               |
| **Child**            | A node directly connected below another node               |
| **Left Child**       | The child connected through the left reference             |
| **Right Child**      | The child connected through the right reference            |
| **Siblings**         | Nodes that share the same parent                           |
| **Leaf Node**        | A node with no children                                    |
| **Internal Node**    | A node with at least one child                             |
| **Ancestor**         | Any node appearing on the path from the root to a node     |
| **Descendant**       | Any node present below another node                        |
| **Subtree**          | A node together with all of its descendants                |
| **Path**             | A sequence of connected nodes                              |
| **Depth**            | Number of edges from the root to a node                    |
| **Height of a Node** | Number of edges on its longest downward path to a leaf     |
| **Height of a Tree** | Height of its root                                         |
| **Degree of a Node** | Number of children of the node                             |


Time Complexity 
- Skew Tree
- Balanced Tree


---
Tree Order 
1. Pre-Order
2. In-Order
3. Post-Order
---
1. Recursion Approach 
2. Stack Approach
You need to know both.  🤔🤔🤔 


---
Euler Diagram


---


https://leetcode.com/problems/binary-tree-inorder-traversal/description/


https://www.geeksforgeeks.org/dsa/inorder-tree-traversal-without-recursion/


Moris Order 


---
Height Of A Tree  🤔🤔🤔 
1. By Node
2. By Edge


- [ ] [[DFS Tree Depth First Search Grokking]]
- [ ] [[BFS Tree Breadth First Search Grokking]]



---
Diameter 
1. Is it passing through root or not ?
``
```
[ Diameter = leftHeight + rightHeight ]
```

https://leetcode.com/problems/diameter-of-binary-tree/description/

Coding Approach : 
- Approach 1: Using class-level variable (simplest)
- Approach 2: Using an array (no class-level variable)



```java
// Leetcode : 543
class Solution {
    int maxi=0;    
    public int diameterOfBinaryTree(TreeNode root) {
        //dfsHeightByNode(root);
        dfsHeightByEdge(root);
        return maxi;
    }

    // Monday, December 30, 2024 11:23:09 PM
    // Time Complexity:O(n) | Space Complexity:O(HeightOfTree)
    public int dfsHeightByEdge(TreeNode root) {
        if(root==null) return -1;
        int left = dfsHeightByEdge(root.left);
        int right = dfsHeightByEdge(root.right);
        maxi = Math.max(maxi,left+right+2);  //<--
        return 1 + Math.max(left,right);
    }

    // Monday, December 30, 2024 10:11:23 PM
    // Time Complexity:O(n) | Space Complexity:O(HeightOfTree)
    public int dfsHeightByNode(TreeNode root) {
        if(root==null) return 0;        
        int left = dfsHeightByNode(root.left);
        int right = dfsHeightByNode(root.right);
        maxi = Math.max(maxi,left+right);
        return 1+ Math.max(left,right);  //<--
    }
}
```
