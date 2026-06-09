**Code Blocks**
- A code block is a series of statements grouped together. A code block in Python is defined by its indentation level. Ex: the number of blank columns from the left edge. The initial code block is not indented. A new code block can follow a statement that ends with a colon, such as an "if" or "else". In addition, a new code block must be more indented than the previous code block. The program below includes comments indicating where each new code block begins.

- The amount of indentation used to indicate a new code block can be arbitrary, as long as the programmer uses the same indentation consistently for each line in the block. Good practice is to use the standard recommended four columns per indentation level.

- A common error for new Python programmers is the mixing of tabs and spaces. Never mix tabs and spaces for indentation in the same program. Many editors consider a tab to be equivalent to either three or four spaces, while in Python a tab is equivalent only to another tab. A program that mixes tabs and spaces to indent code blocks will automatically generate an IndentationError from the interpreter in Python 3. A good practice is to use spaces only when indenting code, and to set text editor options to automatically use spaces when possible.

**Special Cases**
- The acceptable number of columns of text varies from 80 to 120. Good practice is to use the widely accepted standard of 80 columns. A few exceptions to the rules of indentation deal with very long statements that require more than one line and _wrap_ to the next line. Such special situations do not indicate new code blocks.
