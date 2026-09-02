Remove Consecutive Characters
Difficulty

Easy

Pattern

String Traversal

Key Idea

Remove only consecutive duplicate characters, keeping one occurrence.

Approach
Add the first character to the answer.
Traverse from index 1.
Compare the current character with the previous character.
If different → add it.
If same → skip it.
Time

O(n)

Space

O(n)

Key Trick

Current ≠ Previous → Add
Current = Previous → Skip

Example

"aabbcc" → "abc"
"abbaca" → "abaca"

Companies

Amazon, Microsoft, Google, Adobe, Accenture, TCS
