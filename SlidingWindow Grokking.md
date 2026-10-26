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