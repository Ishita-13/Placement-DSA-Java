# Repeat and Missing Number Array

## Pattern
Hashing (Frequency Array)

## Recognition
If the question says:
- One Missing Number
- One Repeating Number
- Numbers from 1 to N

Think Frequency Array or Hashing.

## Optimal Approach
1. Create a frequency array.
2. Count frequency of each number.
3. Frequency = 2 → Repeating.
4. Frequency = 0 → Missing.

## Time Complexity
O(n)

## Space Complexity
O(n)

## Interview Tips
- Numbers are from 1 to N.
- Create frequency array of size n+1.
- Learn O(1) approaches (Math, XOR, Cyclic Sort) for product-based interviews.

## Similar Questions
- Missing Number
- Find Duplicate Number
- Set Mismatch (LeetCode 645)

## Revision Trick
1 to N + One Missing + One Duplicate → Hashing
