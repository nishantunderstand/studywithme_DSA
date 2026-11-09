
https://takeuforward.org/blogs/data-structure-and-algorithm/template-mental-model

|Problem Requirement|Maintained State|
|---|---|
|Sum of the current window|Running sum|
|Number of zeros|Zero count|
|Number of distinct values|Frequency map and distinct count|
|Repeated characters|Character frequencies|
|Required character matches|Frequency map and matched count|
|Maximum or minimum element|Monotonic deque|
|Number of odd elements|Odd-element count|
|Product of elements|Running product|




## The Window Invariant

A **window invariant** is a condition that remains true whenever the window is used to update the answer.

Examples include:

- The window contains at most `K` distinct values.
- The window contains no repeated characters.
- The window sum is smaller than or equal to a limit.
- The window contains all required characters.
- The window size is exactly `K`.

Before writing the solution, clearly define:

- What makes the window valid?
- What information is required to check validity?
- Which element enters when `right` moves?
- Which element leaves when `left` moves?
- When should the answer be updated?

Most sliding-window errors occur when the maintained state and the actual window no longer match.

### The Window Invariant

A window invariant is a condition that remains true whenever the window is used to update the answer.

Examples include:

- The window contains at most K distinct values.
- The window contains no repeated characters.
- The window sum is smaller than or equal to a limit.
- The window contains all required characters.
- The window size is exactly K.

Before writing the solution, clearly define:

- What makes the window valid?
- What information is required to check validity?
- Which element enters when right moves?
- Which element leaves when left moves?
- When should the answer be updated?

Most sliding-window errors occur when the maintained state and the actual window no longer match.



[[SlidingWindow Grokking]]
