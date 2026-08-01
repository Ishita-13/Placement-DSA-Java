# Merge Two Sorted Arrays Without Extra Space

## Pattern
Two Pointers + Gap Method

## Recognition
If the question asks:
- Merge two sorted arrays
- Without extra space

Think Gap Method.

## Optimal Approach
1. Treat both arrays as one virtual array.
2. Initialize gap = ceil((n+m)/2).
3. Compare elements gap distance apart.
4. Swap if needed.
5. Reduce the gap until it becomes 1.

## Time Complexity
O((n+m) log(n+m))

## Space Complexity
O(1)

## Interview Tips
- Don't use an extra array.
- Gap Method is based on Shell Sort.

## Similar Questions
- Merge Sorted Array
- Merge Intervals
- Sort Colors

## Revision Trick
Sorted Arrays + No Extra Space → Gap Method
