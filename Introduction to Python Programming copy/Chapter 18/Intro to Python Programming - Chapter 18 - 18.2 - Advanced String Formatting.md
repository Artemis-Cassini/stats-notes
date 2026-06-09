**Field Width**
- A format specification may include a **field width**, that defines the minimum number of characters that must be inserted into the string. If the replacement value is smaller in size than the given field width, then the string is padded with space characters 

**Aligning Text**
- A format specification can include an **alignment character** that determines how a value should be aligned within the width of the field

**Fill**
- The **fill character** is used to pad a replacement field when the inserted string is smaller than the field width

| Format Specification | Value of Score |
| -------------------- | -------------- |
| {score:}             | 9              |
| {score:4}            | 9              |
| {score:0>4}          | 9              |
| {score:0>4}          | 18             |
| {score:0^4}          | 18             |

**Floating-Point Precision**
- The optical **precision** component of a format specification indicates how many digits should be included in the output of floating types