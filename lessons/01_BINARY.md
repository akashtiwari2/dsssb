# Lesson 01: Binary foundations — 30 October
Status: introductory application 3/3 correct; delayed recall pending. Planned 30 Oct CS block.
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
N01=13 with weights, N02=32 patterns/max31, N03=1010; all correct on 30 Oct. Recall due 31 Oct.


## Binary addition and unsigned overflow
0+0=0; 0+1=1; 1+0=1; 1+1=10 (write 0 and carry 1).
With incoming carry: 1+1+1=11 (write 1 and carry 1).
Work from right to left, just as decimal addition.
Example: 0101+0011=1000. Columns right-to-left: 1+1=10; 0+1+carry1=10; 1+0+carry1=10; 0+0+carry1=1. Decimal check 5+3=8.
Fixed 4-bit unsigned storage: 1111+0001 gives mathematical 10000; retaining only 4 low bits stores 0000 and carry-out is 1 (unsigned overflow). Signed overflow has different rules.
Pending assistant-generated questions:
N04: 0110+0011, show result and decimal check.
N05: 1011+0110, show full sum; if only 4 bits retained give stored bits and unsigned overflow status.
After response: brief Boolean gates lesson and connect to inspected digital-logic PYQ; maintain planned general-section rotation.
