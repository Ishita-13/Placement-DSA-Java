# Contains Duplicate

## Pattern
HashSet

## Recognition
If the question asks whether an element repeats, think HashSet.

## Optimal Approach
Traverse the array once.
If the element already exists in HashSet, return true.
Otherwise, add it.

## Time Complexity
O(n)

## Space Complexity
O(n)

## Interview Tips
- Use HashSet for duplicate checking.
- Use HashMap when frequency is required.

## Similar Questions
- Find Duplicate Number
- Happy Number
- Longest Consecutive Sequence
