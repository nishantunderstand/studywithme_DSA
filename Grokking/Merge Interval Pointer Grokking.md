- [x] [Merge Intervals](https://leetcode.com/problems/merge-intervals/) (56)  
- [x] [Insert Interval](https://leetcode.com/problems/insert-interval/) (57)
- [x] [Intervals Intersection](https://leetcode.com/problems/interval-list-intersections/) (986)
- [x] [Conflicting Appointments](https://leetcode.com/problems/meeting-rooms/) (252)
- [x] [Meeting Room](https://www.geeksforgeeks.org/problems/attend-all-meetings/1) (252) 
- [x] [Minimum Meeting Rooms](https://leetcode.com/problems/meeting-rooms-ii/) (253)
- [x] https://www.geeksforgeeks.org/problems/attend-all-meetings-ii/1#expected-approach-by-using-extra-space-on-time-and-on-space
- [x] [Maximum CPU Load](https://www.geeksforgeeks.org/maximum-cpu-load-from-the-given-list-of-jobs/) (GFG)
- [x] https://www.naukri.com/code360/problems/cpu-task-scheduler_2248081
- [ ] [Employee Free Time](https://leetcode.com/problems/employee-free-time/) (759)
- [ ] https://www.naukri.com/code360/problems/employee-free-time_1171181

---
https://www.youtube.com/watch?v=fmdNUOQnhrU
- Check Whether Intervals is sorted or not ?  🤔🤔🤔 
```java
Arrays.sort(intervals,new Comparator<int[]>(){
            @Override    
            public int compare(int[] a, int[] b){
                return Integer.compare(a[0],b[0]);
            }
        });
```


```java
	Arrays.sort(intervals,(a,b)-> Integer.compare(a[0],b[0]));
```


https://www.youtube.com/watch?v=BCZ_9clRkxo
- You need to pratice

https://www.geeksforgeeks.org/problems/attend-all-meetings/1


https://leetcode.com/problems/meeting-rooms-ii/description/


https://www.geeksforgeeks.org/problems/attend-all-meetings-ii/1


https://leetcode.com/discuss/post/2166045/line-sweep-algorithms-by-c0d3m-8ebq/


https://www.youtube.com/watch?v=zKSDKQ-ifmI


https://www.youtube.com/playlist?list=PLpIkg8OmuX-IOG_-Bv92l-EhuBQX28LOm

Delta : +1 / -1
When to use Horizontal / Vertical ?

![[Line-Sweep-2.png]]

![[Line-Sweep-1.png]]


https://www.youtube.com/watch?v=9X0-4zSfd80&list=PLpIkg8OmuX-IOG_-Bv92l-EhuBQX28LOm&index=2

[[Difference Array]]


![[Line-Sweep-3.png]]


![[Line-Sweep-4.png]]

![[Line-Sweep-5.png]]


---
[[Line Sweep Alogrithm]]


Interval Question
1. Sort by StartTime
2. Sort by EndTime 
How to Know ?

Line Sweep Algorithm 
1. Difference Array
2. TreeMap