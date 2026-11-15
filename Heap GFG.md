
# **Heap – Extract Max / Extract Min Practice Questions**

Since you've completed **Building Heap from Array (GFG)**, the next step is to practise heap insertion, deletion, extraction and priority queue operations.

Here are the direct practice links across GFG, LeetCode, Naukri Code360 and HackerRank.

## **1. GFG – Must Practise**

|Problem|Difficulty|Practice|
|---|---|---|
|Max Heap Implementation|Easy|[GFG](https://www.geeksforgeeks.org/problems/max-heap-implementation/1?utm_source=chatgpt.com)|
|Binary Heap Operations (Min Heap)|Medium|[GFG](https://www.geeksforgeeks.org/problems/operations-on-binary-min-heap/0?utm_source=chatgpt.com)|
|Building Heap from Array|—|[GFG related heap practice](https://www.geeksforgeeks.org/problems/convert-min-heap-to-max-heap-1666385109/1?utm_source=chatgpt.com)|
|Kth Largest Element|Medium|[GFG](https://www.geeksforgeeks.org/problems/kth-largest-element-in-a-stream-1587115620/1?utm_source=chatgpt.com)|
|Merge Two Binary Max Heaps|Medium|[GFG](https://www.geeksforgeeks.org/problems/merge-two-binary-max-heap0144/1?utm_source=chatgpt.com)|

**Important:** GFG's Binary Heap Operations problem explicitly covers `insertKey()`, `deleteKey()` and `extractMin()`.

GeeksforGeeks+1

## **2. Naukri Code360**

|Problem|What you learn|Practice|
|---|---|---|
|Min Heap|Insert + Extract Min|[Solve](https://www.naukri.com/code360/problems/min-heap_8230863?utm_source=chatgpt.com)|
|Min Heap Implementation|Extract + Delete + Insert|[Solve](https://www.naukri.com/code360/problems/min-heap-implementation_5480527?utm_source=chatgpt.com)|
|Min Heap (Alternative)|Query-based heap operations|[Solve](https://www.naukri.com/code360/problems/min-heap_4691801?utm_source=chatgpt.com)|

The first problem is particularly useful for implementing `extractMinElement()` yourself.

Naukri Code 360+1

## **3. LeetCode – Heap / Priority Queue**

LeetCode doesn't generally ask for a standalone `extractMax()` or `extractMin()` operation. Instead, practise these problems to understand the same operations.

|#|Problem|Difficulty|Link|
|---|---|---|---|
|1046|Last Stone Weight|Easy|[Solve](https://leetcode.com/problems/last-stone-weight/?utm_source=chatgpt.com)|
|703|Kth Largest Element in a Stream|Easy|[Solve](https://leetcode.com/problems/kth-largest-element-in-a-stream/?utm_source=chatgpt.com)|
|215|Kth Largest Element in an Array|Medium|[Solve](https://leetcode.com/problems/kth-largest-element-in-an-array/?utm_source=chatgpt.com)|
|347|Top K Frequent Elements|Medium|[Solve](https://leetcode.com/problems/top-k-frequent-elements/?utm_source=chatgpt.com)|
|692|Top K Frequent Words|Medium|[Solve](https://leetcode.com/problems/top-k-frequent-words/?utm_source=chatgpt.com)|
|973|K Closest Points to Origin|Medium|[Solve](https://leetcode.com/problems/k-closest-points-to-origin/?utm_source=chatgpt.com)|
|23|Merge K Sorted Lists|Hard|[Solve](https://leetcode.com/problems/merge-k-sorted-lists/?utm_source=chatgpt.com)|
|295|Find Median from Data Stream|Hard|[Solve](https://leetcode.com/problems/find-median-from-data-stream/?utm_source=chatgpt.com)|

GyanByte+1

## **4. HackerRank**

|Problem|Heap operation|Link|
|---|---|---|
|QHEAP1|Insert, Delete, Find Min|[Solve](https://www.hackerrank.com/challenges/qheap1/problem?utm_source=chatgpt.com)|
|Jesse and Cookies|Extract Min + Insert|[Solve](https://www.hackerrank.com/challenges/jesse-and-cookies/problem?utm_source=chatgpt.com)|

**QHEAP1 is especially important** because it tests the basic priority queue operations.

## **5. Recommended Practice Order**

Follow this sequence to build confidence:

1. **Heap Fundamentals**
    
    - Building Heap from Array
        
    - Heapify (Min Heap / Max Heap)
        
    
2. **Basic Operations**
    
    - Insert into Heap
        
    - Extract Max
        
    - Extract Min
        
    - Delete an element
        
    
3. **Intermediate**
    
    - Kth Largest
        
    - Kth Smallest
        
    - Last Stone Weight
        
    - Connect N Ropes with Minimum Cost
        
    
4. **Advanced**
    
    - Top K Frequent Elements
        
    - Merge K Sorted Lists
        
    - Find Median from Data Stream
        
    

## **6. Revision: Heap Operations Complexity**

|Operation|Time Complexity|
|---|---|
|Get Max / Min (Peek)|O(1)|
|Insert|O(log n)|
|Extract Max / Min|O(log n)|
|Delete arbitrary element|O(log n)*|
|Build Heap|O(n)|
|Heapify|O(log n)|

_Assuming the element's index is already known._

**My recommendation:** First implement `extractMax()` and `extractMin()` manually using Java arrays, without `PriorityQueue`. This will strengthen your understanding of heapify and index manipulation.

I can also prepare a Java heap practice tracker with solutions and dry runs for each problem.

🧩Daily Java heap practice questionTap to set up