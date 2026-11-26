### **Level Order Traversal – Summary**

[[Generic Tree Pepcoding CrafterHack]]


Both approaches use **BFS (Queue)**.

|Without `queSize`|With `queSize`|
|---|---|
|Normal BFS traversal|Level-wise BFS traversal|
|Processes one node at a time|Processes one complete level at a time|
|Cannot identify level boundaries directly|Identifies level boundaries|
|Simple traversal|Level separation, averages, zigzag, etc.|

**Key Concept:**

- `que.poll()` → Remove current node.
- `que.offer()` → Add children to the queue.
- `que.size()` → Capture the number of nodes at the current level.

**Interview Tip:**
Use `queSize` whenever the problem requires processing or calculating something separately for each level.
**Both are BFS.** `queSize` **is optional, depending on the problem requirement.**