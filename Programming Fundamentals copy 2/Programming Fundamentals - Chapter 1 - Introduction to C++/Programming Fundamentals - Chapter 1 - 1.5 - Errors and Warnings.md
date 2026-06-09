### Syntax Errors
- A kind of mistake, known as a **syntax error**, is to violate a programming language's rules on how symbols can be combined to create a program

---
### Fixing the First Error
- Some errors create an upsettingly long list of error messages. Good practice is to focus on fixing just the first error reported by the compiler and then recompiling. The remaining error messages may be real but are more commonly due to the compiler's confusion caused by the first error and are thus irrelevant.

---
#### Good practice for fixing errors reported by the compiler
1. Focus on FIRST error message, ignoring the rest
2. Look at reported line of first error message. If error found, fix. Else, look at previous few lines
3. Compile, repeat

---
### Logic Errors
- Because a syntax error is detected by the compiler, a syntax error is known as a type of **compile-time error**
- A **logic error**, also called a **bug**, is an error that occurs while a program runs

---
### Compiler Warnings
- A compiler will sometimes report a **warning**, which doesn't stop the compiler from creating an executable program but indicates a possible logic error