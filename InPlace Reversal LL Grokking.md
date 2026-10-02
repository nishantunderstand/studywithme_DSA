[[Fast And Slow Pointer Grokking]]

- [x] [Reverse a LinkedList](https://leetcode.com/problems/reverse-linked-list/) (206) | Why curr!=null isused 
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

