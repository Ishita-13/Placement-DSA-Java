Valid Parentheses
Difficulty

Easy

Pattern

Stack

Key Idea

Use a Stack to match every closing bracket with its corresponding opening bracket.

Approach
Opening bracket → push() into stack.
Closing bracket → check the top of stack.
If brackets match → pop().
If they don't match or stack is empty → return false.
At the end, stack must be empty.
Time

O(n)

Space

O(n)

Key Trick

Opening → PUSH
Closing → Match TOP → POP

Companies

Amazon, Microsoft, Google, Meta, Bloomberg, Adobe
