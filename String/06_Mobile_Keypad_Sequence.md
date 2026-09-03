Convert Sentence into Mobile Numeric Keypad Sequence
Difficulty

Easy

Pattern

Character Mapping / Lookup Table

Key Idea

Map each alphabet character to its corresponding mobile keypad sequence.

Approach
Create a keypad mapping for A-Z.
Convert each character to uppercase.
Find its index using ch - 'A'.
Get the corresponding keypad sequence.
Append it to the answer.
Example

"HELLO" → "4433555555666"

H → 44
E → 33
L → 555
L → 555
O → 666
Time

O(n)

Space

O(n)

Key Trick

Character → Index → Lookup → Append

Companies

Amazon, Microsoft, Google, Infosys, TCS, Accenture
