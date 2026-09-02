Valid Anagram
Difficulty

Easy

Pattern

HashMap / Frequency Counting

Key Idea

Two strings are anagrams if they contain the same characters with the same frequencies.

Approach
If lengths are different → return false.
Store frequency of each character from the first string.
Traverse the second string and decrease the frequency.
If a character is not present → return false.
If all frequencies become zero → strings are anagrams.
Time

O(n)

Space

O(n)

Key Trick

First string → increase frequency
Second string → decrease frequency

Companies

Nagarro, Media.net, Directi, Google, Adobe, Flipkart
