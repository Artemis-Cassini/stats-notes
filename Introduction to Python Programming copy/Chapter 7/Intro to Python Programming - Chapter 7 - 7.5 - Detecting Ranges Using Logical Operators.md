**Logical AND, OR, and NOT (General)**
- A logical operator treats operands as being True or False, and evaluates to True or False. Logical operators include AND, OR, and NOT. Programming languages typically use various symbols for those operators, but below the words AND, OR, and NOT are used for introductory purposes 

| Logical Operator | Description                                                     |
| ---------------- | --------------------------------------------------------------- |
| a AND b          | Logical AND: True when both of its operands are True            |
| a OR b           | Logical OR: True when at least one of its two operands are True |
| NOT a            | Logical NOT: True when its one operand is False, and vice versa |
**Booleans and Logical Operators**
- A boolean refers to a value that is either True or False
- A programmer can assign a Boolean value by specifying True or False, or by evaluating an expression that yields a Boolean

*Given age = 19, days = 7, user_char = “q”*

| A                          | B                                                              |
| -------------------------- | -------------------------------------------------------------- |
| (age > 16) and (age < 25)  | True, because both operands are True                           |
| (age > 16) and (days > 10) | False, because both operands are not True (days > 10 is False) |
| (age > 16) or (days > 10)  | True, because at least one operand is True (age > 16 is True)  |
| not (days > 10)            | True, because operand is False                                 |
| not (age > 16)             | False, because operand is True                                 |
| not (user_char == “q”)     | False, because operand is True                                 |
**Detecting Ranges Implicitly vs. Explicitly**
- A programmer often uses logical operators to detect a range by explicitly specifying the high end and low end of the range. However, if a program should detect increasing ranges without gaps, a multi-branch if-else statement can be used without logical operators; the low end of the range is implicitly known upon reaching an expression. Likewise, a decreasing range without gaps has implicitly known high-ends.