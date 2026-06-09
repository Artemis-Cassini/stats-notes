**Detecting If Two Items Are Equal Using An If Statement**
- A program commonly needs to determine if two items are equal. Ex: If a hotel gives a discount for guests on their 50th wedding anniversary, a program to calculate the discount can check if a variable num_years is equal to the value 50. A programmer can use an if statement to check if two values are equal.

- An if statement executes a group of statements if an expression is true. The statements in a branch must be indented, typically four spaces.

**Equality and Inequality Operators**
- Whereas the equality operator checks whether two values are equal, the inequality operator (!=) evaluates to True if the left and right sides are not equal, or different.

- An expression involving an equality or inequality operator evaluates to a Boolean value. A Boolean is a type that has just two values: True or False.

| Equality Operators | Description                      | Example (assuming x is 3)         |
| ------------------ | -------------------------------- | --------------------------------- |
| ==                 | a == b means a is equal to b     | x == 3 is True<br>x == 4 is False |
| !=                 | a != b means a is not equal to b | x != 3 is False<br>x != 4 is True |

**If-Else Statements**
- An if-else statement executes one group of statements when an expression is true, and another group of statements when the expression is false. In the example below, the if-else statement outputs if a number entered by the user is even or odd. The if statement executes if divRemainder is equal to 0, and the else statement executes if divRemainder is not equal to 0.

**Multi-Branch If-Else Statements**
- Commonly, a program may need to detect several specific values of a variable. An if-else statement can be extended to have three (or more) branches. Additional branches use the elif keyword, which means "else if". Each branch's expression is checked in sequence. As soon as one branch's expression is found to be True, that branch's statement executes (and no subsequent branch is considered). If no expression is True, the else branch executes.