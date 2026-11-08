- [x] [Merge K Sorted Lists](https://leetcode.com/problems/merge-k-sorted-lists/) (23)
- [x] [Kth Smallest Number in M Sorted Lists](https://www.geeksforgeeks.org/problems/kth-smallest-element5635/1) (GFG)
- [x] [Kth Smallest Number in a Sorted Matrix](https://leetcode.com/problems/kth-smallest-element-in-a-sorted-matrix/) (378) 
- [ ] [Smallest Number Range](https://leetcode.com/problems/smallest-range-covering-elements-from-k-lists/) (632)
- [ ] [K Pairs with Largest Sums](https://leetcode.com/problems/find-k-pairs-with-smallest-sums/) (373)

---
Intution : 
1. Smallest -> maxHeap | You need to pass comparator ,Prefer Lambda One 
2. Largest -> minHeap

---
378 : PriortyQueue Approach 
Do i need to solve it by Other Approach.


https://leetcode.com/problems/merge-k-sorted-lists/description/


```java

```

```java
PriorityQueue<Integer> minPQ = new PriorityQueue<>();


PriorityQueue<Integer> maxHeap = new PriorityQueue<>((a,b)->Integer.compare(b,a));


PriorityQueue<ListNode> minPQ = new PriorityQueue<>(
            (a,b)->Integer.compare(a.val,b.val)
        );
                
PriorityQueue<Integer> minPQ = new PriorityQueue<>(
			(a,b)->Integer.compare(map.get(a),map.get(b))
  );        
```

- If you normal Datatype : You don't need to do anything.
- But if you pass custom, Then you need to pass comparator.