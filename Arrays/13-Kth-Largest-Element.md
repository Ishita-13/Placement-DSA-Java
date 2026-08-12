# Kth Largest Element in an Array

## Difficulty
Medium

## Pattern
Sorting / Heap / Quickselect

## Key Idea
The Kth largest element is found from the end after sorting.

## Approach
1. Sort the array.
2. Find index: `n - k`.
3. Return `nums[n - k]`.

## Time Complexity
O(n log n)

## Space Complexity
O(1)

## Key Trick
Kth Largest → `n - k`

## Companies
Amazon, Microsoft, Google, Meta, Apple
