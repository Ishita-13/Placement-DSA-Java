# Product of Array Except Self

## Difficulty
Medium

## Pattern
Prefix Product + Suffix Product

## Key Idea
For every index:
answer = product of left elements × product of right elements.

## Approach
1. Store left product in `answer`.
2. Traverse from right and multiply by right product.
3. No division required.

## Time Complexity
O(n)

## Space Complexity
O(1) extra space

## Key Trick
Left Product × Right Product

## Companies
Amazon, Microsoft, Google, Meta, Apple
