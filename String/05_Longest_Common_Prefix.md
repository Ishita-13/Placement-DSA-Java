Longest Common Prefix
Difficulty

Easy

Pattern

String Traversal

Key Idea

Compare characters at the same index across all strings.

Approach
Take the first string as the reference.
Traverse each character position.
Compare that character with the same position in every string.
If a mismatch occurs or a string ends → return the prefix before that position.
If no mismatch occurs → return the first string.
Time

O(n × m)

Space

O(1)

Key Trick

Outer loop → character position
Inner loop → check all strings

Example

["flower", "flow", "flight"] → "fl"

Companies

Amazon, Microsoft, Google, Meta, Adobe
