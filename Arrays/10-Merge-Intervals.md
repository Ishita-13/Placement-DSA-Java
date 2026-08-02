# Merge Intervals

## Pattern
Sorting + Interval Merging

## Recognition
If the question asks:
- Merge intervals
- Overlapping intervals

Think Sorting first.

## Optimal Approach
1. Sort intervals by starting point.
2. Take the first interval as current.
3. If next interval overlaps, merge them.
4. Otherwise, store current interval and move ahead.
5. Add the last interval.

## Time Complexity
O(n log n)

## Space Complexity
O(n)

## Interview Tips
- Always sort intervals first.
- Overlap condition:
  next.start <= current.end

## Similar Questions
- Insert Interval
- Non-overlapping Intervals
- Meeting Rooms
- Meeting Rooms II

## Revision Trick
Intervals + Overlap → Sort → Merge
