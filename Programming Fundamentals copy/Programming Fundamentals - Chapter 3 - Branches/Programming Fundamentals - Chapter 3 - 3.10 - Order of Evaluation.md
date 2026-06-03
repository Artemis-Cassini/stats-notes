### Precedence Rules
- The order in which operators are evaluated in an expression are known as **precedence rules**

| Operator/Convention | Description                                  |
| ------------------- | -------------------------------------------- |
| ()                  | Items within parentheses are evaluated first |
| !                   | ! (logical NOT) is next                      |
| * / % + -           | Arithmetic operators                         |
| < <= > >=           | Relational operators                         |
| == !=               | Equality and inequality operators            |
| &&                  | Logical AND                                  |
| \|\|                | Logical OR                                   |

---
### Common Error: Bitwise rather than Logical Operators
- Logical AND is && and not just &, and logical OR is || and not just |. & and | represent **bitwise operators**, which perform AND or OR on corresponding individual bits of the operands.