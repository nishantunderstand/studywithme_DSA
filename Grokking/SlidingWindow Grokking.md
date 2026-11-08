LC : 3,209,340,424,643,904,1493

- [x] [Permutation in a String](https://leetcode.com/problems/permutation-in-string/) (567)
- [ ] [Smallest Window containing Substring](https://leetcode.com/problems/minimum-window-substring/) (76)
- [x] [String Anagrams](https://leetcode.com/problems/find-all-anagrams-in-a-string/) (438)
- [ ] [Words Concatenation](https://leetcode.com/problems/substring-with-concatenation-of-all-words/) (30)
- [x] [Fruit Into Baskets](https://leetcode.com/problems/fruit-into-baskets/) (904)
- [x] [Longest Repeating Character Replacement](https://leetcode.com/problems/longest-repeating-character-replacement/) (424)  
- [x] [Longest Subarray of 1's After Deleting One Element](https://leetcode.com/problems/longest-subarray-of-1s-after-deleting-one-element/) (1493)
- [x] [Longest Substring with At Most K Distinct Characters](https://leetcode.com/problems/longest-substring-with-at-most-k-distinct-characters/) (340)
- [x] [Longest Substring with At Most K Distinct Characters](https://www.geeksforgeeks.org/problems/longest-k-unique-characters-substring0853/1)  (GFG) 
- [x] [Longest Substring Without Repeating Characters](https://leetcode.com/problems/longest-substring-without-repeating-characters/) (3)
- [x] [Maximum Average Subarray I](https://leetcode.com/problems/maximum-average-subarray-i/) (643)
- [x] [Minimum Size Subarray Sum](https://leetcode.com/problems/minimum-size-subarray-sum/) (209)
---
Refrence Video Links 
- https://www.youtube.com/watch?v=dvXyTOYVxB8
- https://www.youtube.com/watch?v=U2ppEzBaMck
- https://www.youtube.com/watch?v=ExY8svHF_Eo
---
Intution 
1. Start From SlidingWindow 
2. HashSet or HashMap (Frequency or Position)
3. Never Jump to FreqArray or CharacterArray 

If something can be solved by HashMap, I think they can also be solved by FreqArr as well.

---

```java
int[] freq = new int[26];  // 26 Alphabet
int[] freq = new int[128]; // ASCII Character
int[] freq = new int[256]; //
// I need to understand the reason, When to use which version
```

```
length = end - start + 1
LeetCode 1493 = end - start
```


---
https://www.youtube.com/watch?v=3QbafTQaBQk

---
https://seanprashad.com/leetcode-patterns/?pattern=Sliding+Window

https://leetcode.com/discuss/post/5622545/sliding-window-technique-patterns-by-cx1-i8ab/

- [ ] [Sliding Window Pattern Question](https://app.notion.com/p/Sliding-Window-Pattern-Question-1931b0873dd5809bbb9ec4a07e6ebf17?pvs=21)
- [ ] [Sliding Window Pattern Synced](https://app.notion.com/p/Sliding-Window-Pattern-Synced-1b71b0873dd58152869ef3cec0955db1?pvs=21)
- [ ] [Sliding Window Pattern FixedSized](https://app.notion.com/p/Sliding-Window-Pattern-FixedSized-2d41b0873dd58005a005d9de1f85244a?pvs=21)
- [ ] [Sliding Window Pattern **Exact Subarray Count Pattern**](https://app.notion.com/p/Sliding-Window-Pattern-Exact-Subarray-Count-Pattern-37f1b0873dd5801884c4d703cec35ef3?pvs=21)


----

https://leetcode.com/discuss/post/3100856/fixed-size-sliding-window-important-ques-ktu4/

https://www.geeksforgeeks.org/problems/max-sum-subarray-of-size-k5313/1
https://www.geeksforgeeks.org/problems/first-negative-integer-in-every-window-of-size-k3345/1

https://www.geeksforgeeks.org/problems/maximum-of-all-subarrays-of-size-k3101/1



https://www.youtube.com/watch?v=29OnjVQ-fk4&t=240s


https://www.geeksforgeeks.org/problems/count-occurences-of-anagrams5839/1
- Check the variable name 


https://leetcode.com/problems/find-all-anagrams-in-a-string/description/


---

### **1. Fixed Sliding Window Problems**

- [x] [https://www.geeksforgeeks.org/problems/max-sum-subarray-of-size-k5313/1](https://www.geeksforgeeks.org/problems/max-sum-subarray-of-size-k5313/1)
- [x] [https://www.geeksforgeeks.org/problems/first-negative-integer-in-every-window-of-size-k3345/1](https://www.geeksforgeeks.org/problems/first-negative-integer-in-every-window-of-size-k3345/1)
- [x] [https://leetcode.com/problems/number-of-sub-arrays-of-size-k-and-average-greater-than-or-equal-to-threshold/?utm_source=chatgpt.com](https://leetcode.com/problems/number-of-sub-arrays-of-size-k-and-average-greater-than-or-equal-to-threshold/?utm_source=chatgpt.com)

### **2. Dynamic Sliding Window Problems**

- [x] [https://www.geeksforgeeks.org/problems/smallest-subarray-with-sum-greater-than-x5651/1](https://www.geeksforgeeks.org/problems/smallest-subarray-with-sum-greater-than-x5651/1)
- [x] [https://leetcode.com/problems/minimum-size-subarray-sum/description/](https://leetcode.com/problems/minimum-size-subarray-sum/description/)

### **3. Caterpillar Method Problems**

- [x] [LeetCode - 560. Subarray Sum Equals K](https://leetcode.com/problems/subarray-sum-equals-k/)
- [ ] [LeetCode - 1438. Longest Subarray with Sum Less Than or Equal to K](https://leetcode.com/problems/longest-subarray-with-sum-less-than-or-equal-to-k/)
- [ ] https://www.geeksforgeeks.org/problems/longest-sub-array-with-sum-k0809/1
- [ ] https://leetcode.com/problems/longest-continuous-subarray-with-absolute-diff-less-than-or-equal-to-limit/description/
- [ ] [LeetCode - 713. Subarray Product Less Than K](https://leetcode.com/problems/subarray-product-less-than-k/)

### **4. Expanding/Shrinking Sliding Window:**

- [x] [Longest Substring Without Repeating Characters](https://leetcode.com/problems/longest-substring-without-repeating-characters/)
- [x] [Longest Substring with At Most Two Distinct Characters](https://leetcode.com/problems/longest-substring-with-at-most-two-distinct-characters/)
- [x] https://www.naukri.com/code360/problems/longest-substring-with-at-most-two-distinct-characters_3125863
- [x] [Permutation in String](https://leetcode.com/problems/permutation-in-string/)
- [ ] [Minimum Window Substring](https://leetcode.com/problems/minimum-window-substring/)
- [ ] [Longest Repeating Character Replacement](https://leetcode.com/problems/longest-repeating-character-replacement/)
- [x] [Find All Anagrams in a String](https://leetcode.com/problems/find-all-anagrams-in-a-string/)

### **5.Exact Subarray Count Pattern**

- [ ] [**LeetCode 992: Subarrays with K Different Integers**](https://leetcode.com/problems/subarrays-with-k-different-integers/)
- [ ] [**LeetCode 560: Subarray Sum Equals K**](https://leetcode.com/problems/subarray-sum-equals-k/)
- [x] [**LeetCode 904: Fruit Into Baskets**](https://leetcode.com/problems/fruit-into-baskets/) 
- [ ] [**LeetCode 739: Daily Temperature**](https://leetcode.com/problems/daily-temperature/)
- [ ] https://leetcode.com/problems/daily-temperatures/description/
- [ ] [**LeetCode 713: Subarray Product Less Than K**](https://leetcode.com/problems/subarray-product-less-than-k/)


https://leetcode.com/problems/number-of-sub-arrays-of-size-k-and-average-greater-than-or-equal-to-threshold/submissions/2189411949/

---

- SlidingWindow Drawback - Fail for Negative value 
- 904 : Code Syntax is the Issue 