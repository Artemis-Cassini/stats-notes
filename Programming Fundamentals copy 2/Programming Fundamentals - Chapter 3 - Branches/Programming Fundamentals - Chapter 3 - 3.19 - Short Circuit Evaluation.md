- **Short circuit evaluation** skips evaluating later operands if the result of the logical operator can already be determined

| Operator               | Example             | Short circuit evaluation                                                                                                |
| ---------------------- | ------------------- | ----------------------------------------------------------------------------------------------------------------------- |
| operand1 && operand2   | true && operand2    | If the first operand evaluates to true, operand2 is evaluated.                                                          |
| operand1 && operand2   | false && operand2   | If the first operand evaluates to false, the result of the AND operation is always false, so operand2 is not evaluated. |
| operand1 \|\| operand2 | true \|\| operand2  | If the first operand evaluates to true, the result of the OR operation is always true, so operand2 is not evaluated.    |
| operand1 \|\| operand2 | false \|\| operand2 | If the first operand evaluates to false, operand2 is evaluated.                                                         |
