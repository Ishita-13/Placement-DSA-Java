# Search in Rotated Sorted Array

## Difficulty
Medium

## Pattern
Modified Binary Search

## Key Idea
In a rotated sorted array, at least one half is always sorted.

## Approach
1. Find `mid`.
2. Check which half is sorted.
3. Check if the target lies in that sorted half.
4. Search that half, otherwise search the other half.
5. Repeat until target is found.

## Time Complexity
O(log n)

## Space Complexity
O(1)

## Key Trick
Sorted Half → Check Target Range → Eliminate Other Half

## Companies
Amazon, Microsoft, Google, Facebook, Adobe
