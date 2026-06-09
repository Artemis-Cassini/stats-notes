**Conversion Specifiers**
- A **string formatting expression** allows a programmer to create a string with placeholders that are replaces by the variables. Such a placeholder is called a **conversion specifier**, and programmers use different conversion specifiers to perform a conversion of the given variable value to a different type when creating the string

| Conversion Specifier(s) | Notes                                                                                | Example             | Output       |
| ----------------------- | ------------------------------------------------------------------------------------ | ------------------- | ------------ |
| %d                      | Substitute as integer                                                                | print("%d" % 10)    | 10           |
| %f                      | Substitue as floating-point decimal                                                  | print("%f" % 15.2)  | 15.200000    |
| %s                      | Substitute as string                                                                 | print("%s" % "ABC") | ABC          |
| %x, %X                  | Substitute as hexadecimal in lowercase (%x) or uppercase (%X)                        | print("%x" % 31)    | lf           |
| %e, %E                  | Substitute as floating-point exponential format in lowercase (%e) or uppercase (%E). | print("%E" % 15.2)  | 1.520000E+01 |
