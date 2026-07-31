# Chocolate Distribution Problem

## Pattern
Sorting + Fixed Sliding Window

## Recognition
If the question asks to choose K elements with minimum difference, sort the array first.

## Optimal Approach
1. Sort the array.
2. Check every window of size M.
3. Compute:
   last element - first element
4. Keep the minimum difference.

## Time Complexity
O(n log n)

## Space Complexity
O(1)

## Interview Tips
- Always sort first.
- Think of a fixed-size sliding window after sorting.

## Similar Questions
- K Closest Elements
- Minimum Difference Pair
- Aggressive Cows
