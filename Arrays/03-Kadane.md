# Maximum Subarray Sum (Kadane's Algorithm)

## Pattern
Kadane's Algorithm

## Recognition
If the question asks for the maximum sum of a contiguous subarray, think Kadane's Algorithm.

## Optimal Approach
Maintain:
- currentSum
- maxSum

At each step:
- currentSum = max(current element, currentSum + current element)
- Update maxSum.

## Time Complexity
O(n)

## Space Complexity
O(1)

## Interview Tips
- Don't confuse subarray with subsequence.
- Use the Math.max() version to handle all-negative arrays.

## Similar Questions
- Maximum Product Subarray
- Circular Subarray Sum
- Stock Buy & Sell
