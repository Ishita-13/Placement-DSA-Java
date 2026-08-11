# Next Permutation

## Pattern
Greedy + Array Traversal + Two Pointers

## Recognition
If the question asks for the next greater permutation of an array:

Think:
Right → Left → Pivot → Swap → Reverse

## Optimal Approach
1. Traverse from right to left.
2. Find the first index `i` where:
   `arr[i] < arr[i + 1]`
3. This `i` is called the pivot.
4. Find the smallest element greater than `arr[i]` from the right side.
5. Swap the pivot with that element.
6. Reverse the part after the pivot.
7. If no pivot exists, reverse the complete array.

## Why Reverse?
After finding the pivot from right to left, the part after the pivot is in descending order.

After swapping, we need the smallest possible arrangement after the pivot.

Descending → Reverse → Ascending

## Time Complexity
O(n)

## Space Complexity
O(1)

## Interview Tips
- Always start from the right.
- Pivot condition:
  `arr[i] < arr[i + 1]`
- Find the element greater than the pivot from the right.
- Don't stop after swapping.
- Reverse the suffix to get the smallest possible arrangement.
- If no pivot exists, the array is already the largest permutation.

## Common Mistakes
- Starting from left to right.
- Finding the wrong pivot.
- Stopping after the swap.
- Sorting instead of reversing.
- Forgetting the decreasing-array case.

## Similar Questions
- Previous Permutation
- Permutations
- Permutations II
- Next Greater Element

## Revision Trick
Pivot → Swap → Reverse

## Example
Input:
`[1,2,3,6,5,4]`

Pivot:
`3`

Swap with:
`4`

After swap:
`[1,2,4,6,5,3]`

Reverse suffix:
`[1,2,4,3,5,6]`

Answer:
`[1,2,4,3,5,6]`
