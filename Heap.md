[[Two Heaps Grokking]]
Complete Binary Tree

Operation

Heaify
1-Based Index
0-Based Index

Array Based Implementation
Floor  : Lower
Ceil : Upper 

[[Division]]


---
Heap 
CBT
0-Based Indexing 
Parent Node : ith Index
`LC :  2*i + 1`
`RC :  2*i + 2`

Child Node : ith Index , How to find Parent Node ?  
`Ceil Value [i/2] -1` 
Integer Division


Height of Tree h, Maximium No of Nodes in CBT will be : 
`2^h+1 -1` 
Always Start From 0

If there are N-Nodes, Then Find the height of CBT : 
Floor Value log n base 2

Range of Leave Nodes in CBT is
`[N/2] to N-1`
0-Based Indexing

| Concept     | Formula          |
| ----------- | ---------------- |
| Parent      | `(i - 1) / 2`    |
| Left Child  | `2*i + 1`        |
| Right Child | `2*i + 2`        |
| Max Nodes   | `2^(h+1) - 1`    |
| Height      | `floor(log2(N))` |
| First Leaf  | `N/2`            |
| Last Leaf   | `N-1`            |
| Leaf Count  | `ceil(N/2)`      |
