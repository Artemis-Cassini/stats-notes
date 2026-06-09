**Formatted String Literals (F-Strings)
- A formatted string literal, or f-string, allows a programmer to create a string with placeholder expressions that are evaluated as the program executes
- An f-string states with an *f* character and uses curly braces {} to denote the placeholder expressions
- A replacement field, as its value replaces the expression in the final output 

**Additional F-String Features**
- An - sign is provided after the expression in a replacement field to print both the expression and its result

**Format Specifications** 
- A format specification inside a replacement field allows a value's formatting in the string to be customized
- This is introduced with a colon in the replacement field, it separates the 'what' on the left from the 'how' on the right
- This allows the left side to be evaluated, and the right side is the format specification that determines how to show that value using special characters 
- A presentation type is part of a format specification that determines how to represent a value in text form, such as an integer, a floating point, a fixed precision decimal, a percentage, a binary, etc.