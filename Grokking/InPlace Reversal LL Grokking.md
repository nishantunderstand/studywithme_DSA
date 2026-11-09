LC : 206 

- [x] [Reverse a LinkedList](https://leetcode.com/problems/reverse-linked-list/) (206) 
- [ ] [Reverse a Sub-list](https://leetcode.com/problems/reverse-linked-list-ii/) (92)
- [ ] [Reverse every K-element Sub-list](https://leetcode.com/problems/reverse-nodes-in-k-group/) (25)
- [ ] [Reverse alternating K-element Sub-list](https://leetcode.com/problems/reverse-nodes-in-k-group/) (25)
- [ ] [Rotate a LinkedList](https://leetcode.com/problems/rotate-list/) (61)

---


```
// LeetCode : 206
class Solution {
    public ListNode reverseList(ListNode head) {
        ListNode prev = null;
        ListNode curr = head;
        while(curr!=null){ //<-- WHY ??
            ListNode nextNode = curr.next;
            curr.next = prev;
            prev = curr;
            curr = nextNode;
        }
        return prev;
    }
}
```




[[Fast And Slow Pointer Grokking]]


You need to understand Rerverse a LL With a Deep Understanding.

---
If there is change that head will get changed then use Dummy Node concept ?


https://leetcode.com/problems/reverse-linked-list-ii/description/

https://www.youtube.com/watch?v=bRZ_Fy4zRRY&t=85s
- DummyNode Concept
- When to use ?


https://www.youtube.com/watch?v=ykxvY2ZUfM4



https://redquark.org/leetcode/0025-reverse-nodes-in-k-group/


https://algo.monster/liteproblems/25


https://www.youtube.com/watch?v=vqaO4oIJqnI



