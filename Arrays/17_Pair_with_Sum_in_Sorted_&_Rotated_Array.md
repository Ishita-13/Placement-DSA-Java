# Find Pair with Sum in Sorted & Rotated Array

## Difficulty
Medium

## Pattern
Two Pointers

## Key Idea
Find the rotation point, then use circular two pointers.

## Approach
1. Find the smallest element.
2. Set `left` at minimum and `right` at maximum.
3. Move pointers based on their sum.
4. Treat the array as circular.

## Time Complexity
O(n)

## Space Complexity
O(1)

## Key Trick
Sum < target → move left  
Sum > target → move right

## Companies
Amazon, Microsoft, Google
