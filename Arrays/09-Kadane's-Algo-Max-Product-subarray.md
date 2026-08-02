# Maximum Product Subarray

## Pattern
Maximum & Minimum Product Tracking

## Recognition
If the question asks for the maximum product of a contiguous subarray, remember that negative numbers can flip the sign.

## Optimal Approach
1. Maintain maximum and minimum product ending at current index.
2. If current number is negative, swap them.
3. Update both products.
4. Track the global maximum.

## Time Complexity
O(n)

## Space Complexity
O(1)

## Interview Tips
- Product problems are different from sum problems.
- Negative × Negative = Positive.
- Keep both maximum and minimum products.

## Similar Questions
- Maximum Subarray Sum
- Maximum Circular Subarray
- Product of Array Except Self

## Revision Trick
Product + Negative Numbers → Track Max & Min Product
