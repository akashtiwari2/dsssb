# Lesson 01: Binary foundations — 30 October
Status: introduced; learner application pending. Planned 30 Oct CS block.
Priority reason: prerequisite for digital logic, architecture and addressing. P24 Q13 (ID 630680598443, PDF p41) tests K-map minimisation; number representation and Boolean basics precede that skill. This is NOT a claim binary conversion was that PYQ or most frequent topic.
Source details: ../sources/PYQ_ANALYSIS.md.

Binary has digits 0 and 1. From rightmost position, weights are 2^0,2^1,2^2,... = 1,2,4,8,16,...
Decimal value = sum(bit at position i * 2^i), with i starting at 0 on the right.
Worked example: 1011 base 2 = 1*8 + 0*4 + 1*2 + 1*1 = 11.
Fixed n bits give 2^n different patterns. For unsigned integers, range is 0 through 2^n-1.
Example: 3 bits give 8 patterns and maximum unsigned value 7.
Do not confuse number of patterns with highest value. These range formulas are unsigned; signed representation needs separate rules.

Assistant-generated application:
N01: Convert 1101 base 2 to decimal; show weights.
N02: How many patterns can 5 bits form; largest unsigned value?
N03: Write decimal 10 in binary.
No answers yet. Next: grade then binary addition/Boolean gates. Recall due 31 Oct.
