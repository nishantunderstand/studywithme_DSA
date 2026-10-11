LC : 1, 15, 16, 18, 26, 75, 713, 844, 977

- [ ] [Minimum Window Sort](https://leetcode.com/problems/shortest-unsorted-continuous-subarray/) (581)
- [ ] [Quadruple Sum to Target](https://leetcode.com/problems/4sum/) (18)
- [ ] [Subarrays with Product Less than a Target](https://leetcode.com/problems/subarray-product-less-than-k/) (713)
- [ ] [Triplets with Smaller Sum](https://www.geeksforgeeks.org/problems/count-triplets-with-sum-smaller-than-x5549/1 ) (259) (GFG)  
- [x] [Comparing Strings containing Backspaces](https://leetcode.com/problems/backspace-string-compare/) (844)
- [x] [Dutch National Flag Problem](https://leetcode.com/problems/sort-colors/) (75) 
- [x] [Pair with Target Sum](https://leetcode.com/problems/two-sum/) (1)  
- [x] [Remove Duplicates](https://leetcode.com/problems/remove-duplicates-from-sorted-array/) (26)
- [x] [Squaring a Sorted Array](https://leetcode.com/problems/squares-of-a-sorted-array/) (977)
- [x] [Triplet Sum Close to Target](https://leetcode.com/problems/3sum-closest/) (16)  
- [x] [Triplet Sum to Zero](https://leetcode.com/problems/3sum/) (15)  
- [x] [Triplets with Smaller Sum](https://leetcode.com/problems/3sum-smaller/) (259)



---
Intution
1. left<=right is needed or not
2. min = Integer.MAX_VALUE
3. max = Integer.MIN_VALUE 
4. Use a real value when you're comparing **distance/difference** (LC : 16)
5. `if(i>0 && nums[i]==nums[i-1]) continue;` Skip Duplicate Logic


Difference Kya hai ??
end-start+1
end-start