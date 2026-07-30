# Maximum and Minimum Element in an Array

## Difficulty

Easy

---

## Pattern

Linear Traversal

---

## Pattern Recognition

If the question asks:

- Maximum
- Minimum
- Largest
- Smallest

Think **Linear Traversal**.

---

## Brute Force

Sort the array.

Time Complexity: O(n log n)

---

## Optimal Approach

Traverse the array once.

Maintain:

- max
- min

Update them while traversing.

---

## Time Complexity

O(n)

---

## Space Complexity

O(1)

---

## Interview Tips

- Don't sort the array.
- Initialize max and min with the first element.
- Handle empty array if required.

---

## Common Mistakes

❌ max = 0

Always use:

```java
max = arr[0];
```

---

## Similar Questions

- Second Largest Element
- Largest Three Elements
- Stock Buy Sell
- Maximum Difference
