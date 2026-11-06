LC : 35,744,34

- [ ] [Rotation Count](https://www.geeksforgeeks.org/problems/rotation4723/1) (GFG)
- [ ] [Search Bitonic Array](https://www.interviewbit.com/problems/search-in-bitonic-array/) (Interviewbit)
- [ ] [Search in a Sorted Array of Unknown Size](https://www.naukri.com/code360/problems/search-in-infinite-sorted-0-1-array_696193) (702) (Naukri-360)  
- [ ] [Search in Rotated Array](https://leetcode.com/problems/search-in-rotated-sorted-array/) (33)
- [x] [Bitonic Array Maximum](https://www.geeksforgeeks.org/problems/maximum-value-in-a-bitonic-array3001/1) (GFG)
- [x] [Ceiling of a Number](https://leetcode.com/problems/search-insert-position/) (35)  
- [x] [Find First and Last Position of Element in Sorted Array](https://leetcode.com/problems/find-first-and-last-position-of-element-in-sorted-array/) (34)  
- [x] [Find Smallest Letter Greater Than Target](https://leetcode.com/problems/find-smallest-letter-greater-than-target/) (744) 
- [x] [Minimum Absolute Difference](https://leetcode.com/problems/minimum-absolute-difference/) (1200)
- [x] [Order-agnostic Binary Search](https://www.geeksforgeeks.org/order-agnostic-binary-search/) (GFG)
- [x] [Search in a Sorted Array of Unknown Size](https://leetcode.com/problems/search-in-a-sorted-array-of-unknown-size/) (702) 

---
Intution :
- LowerBound  : First Index where  `arr[i]>=x`
- UpperBound  : First Index where  `arr[i]>x`

Standard Variable name 
low high ans mid start end beg end , L, R mid

---
Upper and Lower Bound 
https://www.youtube.com/watch?v=6zhGS79oQ4k

How to know ??
- Open Interval
- Closed Interval 

while(low<high) 
while(low<=high) 


---
[[Array]]

---
- How to know array is ascending or descending ?   
- `boolean isAsc = arr[start] < arr[end];`

---
Either Whole Array Sorted Ascending or Descending => Then Binary Search
Same Array containt both => Then you need to know left sorted and right Sorted => Got it 
- How to know left Sorted  : nums[L] <= nums[M]
- or right Sorted ? : nums[L] > nums[M]
- Rotated Array

- How to find Rotation count ?