### Logical AND, OR, and NOT (General)
- A **logical operator** treats operands as being true or false, and evaluates to true or false

| Logical Operator | Description                                                         |
| ---------------- | ------------------------------------------------------------------- |
| a AND b          | **Logical AND**: true when both of its operands are true            |
| a OR b           | **Logical OR**: true when at least one of its two operands are true |
| NOT a            | **Logical NOT**: true when its one operand is false, and vice-versa |

---
### Logical Operators

| Logical Operator | Description                                                                |
| ---------------- | -------------------------------------------------------------------------- |
| a && b           | **Logical AND** (&&): true when both of its operants are true              |
| a \|\| b         | **Logical OR** (\|\|): true when at least one of its two operands are true |
| !a               | **Logical NOT** (!): true when its one operand is false, and vice-versa    |


if ((inputYear >= 1930) && (inputYear <= 1939)) {
   cout << "The 30s" << endl;
}
else if ((inputYear >= 1940) && (inputYear <= 1949)) {
   cout << "The 40s" << endl;
}
else if ((inputYear >= 1950) && (inputYear <= 1959)) {
   cout << "The 50s" << endl;
}
else {
   cout << "Outside the range of study" << endl;
}