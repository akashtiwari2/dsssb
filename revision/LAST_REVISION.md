# Last revision pack
Updated 30 October 2026. These are first-session corrections; no topic is certified retained.

## Percentage
Second change uses new base. +20%, -20% gives 100→120→96: 4% decrease.
Signed formula and conditions: [formula cards](FORMULAS.md).

## Direction
Cancel opposing components separately. N4 E3 S4 ends 3 km east. Walking distance =11 km; displacement magnitude=3 km.
Learner got direction correct and distance wrong; calculation cause unknown.

## Python
- ord('A') = 65: one character to its Unicode code point.
- chr(65) = 'A': valid code point integer to character.
- dict() constructs a dictionary (key-value mapping); dict() by itself gives {}.
Recall pair: ord → number; chr → character.
B03 selected dict(); R03 immediate chr/ord transfer correct; delayed recall pending.

## DBMS keys
Primary key uniquely identifies a row and cannot be NULL; it may consist of multiple columns.
Foreign key references a primary/unique key of a referenced table (possibly the same table); columns need not share a name.
Example: Department(dept_id PRIMARY KEY); Student(student_id PRIMARY KEY, department_code FOREIGN KEY references Department.dept_id).
Student rows can share a department_code. Valid referencing values must have matching referenced keys, with NULL handling governed by column/DBMS constraints.
Learner's general uniqueness/relationship explanation was correct; no example supplied. Do not infer FK naming misconception solely from ambiguous wording.

## Next recall
31 October: percentage transfer, direction components, ord/chr contrast, PK/FK example.
Then 2 November, 6 November, 13 November; adjust using actual answers.


## Binary
Right-to-left weights: 1,2,4,8,16...; only 1-bit weights contribute.
n bits: 2^n patterns, unsigned max 2^n-1. N01–N03 3/3 correct.
Addition: 1+1=10; 1+1+1=11. Include carry in each next column.
4-bit unsigned 1111+0001 -> full10000; stored0000 with carry-out1.
Next recall 31 Oct.
