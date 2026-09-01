# Find Minimum in Rotated Sorted Array

## Difficulty
Medium

## Pattern
Modified Binary Search

## Key Idea
The minimum is at the rotation point.

## Approach
Compare `nums[mid]` with `nums[right]`:
- `nums[mid] > nums[right]` → minimum is on the right.
- Otherwise → minimum is on the left, including `mid`.

## Time Complexity
O(log n)

## Space Complexity
O(1)

## Key Trick
`mid > right` → go right  
Otherwise → go left

## Companies
Amazon, Microsoft, Google, Meta
