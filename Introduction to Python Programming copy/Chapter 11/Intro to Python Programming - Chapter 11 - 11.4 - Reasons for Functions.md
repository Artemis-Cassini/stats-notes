**Improving Program Readability**
- Programs can become hard for humans to read and understand. Decomposing a program into functions can aid program readability, yield an initially correct program, and ease future maintenance. The following program contains two user-defined functions, making the main program (after the function definitions) easier to read and understand. For larger programs, the effect is even greater 

**Modular Program Development** 
- Programmers commonly use functions to write programs modularly. **Modular development** is the process of dividing a program into separate modules that can be developed and tested separately and integrated into a single program
- A programmer can use function stubs (described in depth elsewhere) to capture the high-level behavior of the required functions (or modules) before diving into the details of each function, like planning a route for a road trip before starting to drive

**Avoid Writing Redundant Code**
- A function can be defined once, then called from multiple places in a program, this avoiding redundant code. Examples of such functions are math module functions like sqrt() that relieve a programmer from having to write several lines of code each time a square root needs to be computed 
- The skill of decomposing a program's behavior into a good set of functions is a fundamental part of programming that helps characterize a good programmer. Each function should have easily recognizable behavior, and the behavior of the main program (and any function that calls other functions) should be easily understandable via the sequence of function cells
- A general guideline (especially for beginner programmers) is that a function's definition usually shouldn't have more than about 30 lines of code, although this guideline is not a strict rule