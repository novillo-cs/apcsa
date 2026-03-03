---
title: CW 44 - Partition Algorithm
due_date: 2026-03-02
---


## Partition Algorithm

You must implement the following method:

```
public static int partition( int [] data, int start, int end){
  // You must declare variables to track left and right indices
}
```

Call the method like this: `partition(yourArray, 0, yourArray.length - 1));`

**Note:** start and end define the boundaries of the array, but you need left and right as moving pointers that
walk toward each other during the partitioning process. start and end need to stay unchanged so you
know the original bounds, while left and right do the actual work of scanning and swapping elements
around the pivot.

Save here: `../APCSA/apcsa-assignments-spring-YourUsername/classwork/03_02_partition/Partition.java`
