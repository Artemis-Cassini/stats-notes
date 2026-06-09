**Precedence Rules**
- The order in which operators are evaluated in an expression is known as precedence rules.
- Arithmetic, logical, and relational operators are evaluated in the order shown below

| Operator/Convention | Description                                                              | Explanation                                                                                                            |
| ------------------- | ------------------------------------------------------------------------ | ---------------------------------------------------------------------------------------------------------------------- |
| ()                  | Items within parentheses are evaluated first                             | in (a * (b+c)) - d, the + is evaluated first, then x, then -                                                           |
| * / % + -           | Arithmetic operators (using their precedence rules; see earlier section) | z - 45 * y < 53 evaluates x first, then -, then <                                                                      |
| < <= > >= == !=     | Relational. (in)equality, and membership operators                       | x < 2 or x >= 10 is evaluated as (x < 2) or (x >= 10) because < and >= have precedence over or                         |
| not                 | not (logical NOT)                                                        | not x or y is evaluated as (not x) or y                                                                                |
| and                 | Logical AND                                                              | x == 5 or y == 10 and z != 10 is evaluated as (x == 5) or ((y == 10) and (z != 10)) because and has precedence over or |
| or                  | Logical OR                                                               | x == 7 or x < 2 is evaluated as (x == 7) or (x < 2) because < and == have precedence over or                           |
**Common Error: Missing Parentheses**
- A common error is to write an expression that is evaluated in a different order than expected. Good practice is to use parentheses in expressions to make the intended order of evaluation explicit. For example, a programmer might write:

- `not a == b` intending to mean `(not a) ==  b`, but the interpreter computes `not (a == b)` because equality operators (== ) have precedence over logical operations (not).
- `w and x == y and z` intending `(w and x) == (y and z)`, but the interpreter computes `(w and (x == y)) and z` because == has precedence over and.
- `not x + y < 5` intending `(not x) + y < 5`, but the interpreter computes `not ((x + y) < 5)` because the addition operator + has the highest precedence and is computed first, followed by the relational operation <, and finally the logical not operation.