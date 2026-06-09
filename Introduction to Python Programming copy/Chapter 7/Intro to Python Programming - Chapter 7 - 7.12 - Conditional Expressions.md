**Conditional Expressions**
- A conditional expression has the following form
	- expr_when_true if condition else expr_when_false
- All three operands are expressions. The condition in the middle is evaluated first. If the condition evaluates to True, then expr_when_true is evaluated. If the condition evaluates to False, then expr_when_false is evaluated. For example, if x is 2, then the conditional expression `5 if x==2 else 9*x` evaluates to 5.

- A conditional expression has three operands and thus is sometimes referred to as a ternary operation.

- Good practice is to restrict usage of conditional expressions to an assignment statement, as in: y = 5 if (x == 2) else 9*x. Some Python programmers denounce conditional expressions as difficult to read and comprehend, since the middle operand is actually the first evaluated, and left-to-right syntax is preferred. However, simple assignments such as the statement above are acceptable.