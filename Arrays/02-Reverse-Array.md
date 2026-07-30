# Reverse Array

## Pattern
Two Pointers

## Recognition
If the question asks to reverse, swap from both ends, or compare first and last elements, think Two Pointers.

## Optimal Approach
Use two pointers:
- Left at index 0
- Right at last index
- Swap
- Move inward

## Time Complexity
O(n)

## Space Complexity
O(1)

## Interview Tips
- Prefer in-place reversal.
- Use `while(left < right)`.

## Common Mistakes
- Forgetting to move pointers.
- Not using a temporary variable.
- Using an extra array unnecessarily.

## Similar Questions
- Reverse String
- Valid Palindrome
- Move Zeroes
- Two Sum II
