**Relational Operators**
- A relational operator checks how one operand’s value relates to another, such as being greater than
- Some operators, such as >=, involve two characters. A programmer cannot arbitrarily combine the >, =, and < symbols; only the two-character sequences shown represent value operators

| Relational Operators | Description                                  | Example (assume x is 3)                                 |
| -------------------- | -------------------------------------------- | ------------------------------------------------------- |
| <                    | a < b means a is less than b                 | x < 4 is True<br>x < 3 is False                         |
| >                    | a > b means a is greater than b              | x > 2 is True  <br>x > 3 is False                       |
| <=                   | a <= b means a is less than or equal to b    | x <= 4 is True  <br>x <= 3 is True  <br>x <= 2 is False |
| >=                   | a >= b means a is greater than or equal to b | x >= 2 is True  <br>x >= 3 is True  <br>x >= 4 is False |
**Detecting Ranges with If-Else Statements**
- Programmers commonly use the sequential nature of the multi-branch if-else arrangement to detect ranges of numbers

**Operator Chaining**
- Python supports operator chaining
- Chaining performs comparisons left to right, evaluating a < b first
- If the result is True, then b < c is evaluated next
- If the result of the first comparison a < b if False, then there is no need to continue evaluating the rest of the expression