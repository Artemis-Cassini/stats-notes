- **Error-checking code** is a code that a programmer introduces to detect and handle errors that occur while the program executes. Python has special constructs known as **exception-handling** constructs because they handle exceptional circumstances, or errors, during execution
- Code that potentially may produce an exception is places in a **try** block. If the code in the try block causes an exception, then the code placed in a following **except** block is executed
- The try and except constructs are used together to implement **exception handling**, the process of responding to unexpected or unwanted events and errors during execution (handling exceptional conditions)

| Type              | Reason Exception is Raised                                            |
| ----------------- | --------------------------------------------------------------------- |
| EOFError          | input() hits an end-of-file condition (EOF) without reading any input |
| KeyError          | A dictionary key is not found in the set of keys                      |
| ZeroDevisionError | Divide by zero error                                                  |
| ValueError        | Invalid value (Ex. Input mismatch)                                    |
| IndexError        | Index is out of bounds                                                |
