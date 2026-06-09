**The format() Method**
- The string **format()** method allows a programmer to create a string with placeholders that are replaces by values or variable values at execution. A placeholder surrounded by curly braces { } is called a **replacement field**

| Replacement Definition          | Example                                                                                        | Formatted String Result    |
| ------------------------------- | ---------------------------------------------------------------------------------------------- | -------------------------- |
| Positional replacement          | "The {1} in the {0} is {2}.".format("hat", "cat", "fat")                                       | The cat in the hat is fat. |
| Inferred positional replacement | "The {} in the {} is {}.".format("cat", "hat", "fat")                                          | The cat in the hat is fat. |
| Named replacement               | "The {animal} in the {headwear} is {shape}.".format(animal="cat", headwear="hat", shape="fat") | The cat in the hat is fat. |
- Named replacement allows a programmer to create a **keyword argument**, an argument that defines a name and value in the format() parentheses

**Format Specifications**
- A **format specification** inside a replacement field allows a value's formatting in the string to be customized
- A common format specification is to provide a **presentation type** for the value, such as integer (4), floating point (4,0), fixed precision decimal (4.000), percentage (4%), binary (100), etc.

| Type          | Description                                                          | Example                | Output       |
| ------------- | -------------------------------------------------------------------- | ---------------------- | ------------ |
| s             | String (default presentation type — can be omitted)                  | "{:s}".format("Aiden") | Aiden        |
| d             | Decimal (integer values only)                                        | "{:d}".format(4)       | 4            |
| b             | Binary (integer values only)                                         | "{:b}".format(4)       | 100          |
| x, X          | Hexadecimal in lowercase (x) and uppercase (X) (integer values only) | "{:x}".format(15)      | f            |
| e             | Exponent notation                                                    | "{:e}".format(44)      | 4.400000e+01 |
| f             | Fixed-point notation (six places of precision)                       | "{:f}".format(4)       | 4.000000     |
| .[precision]f | Fixed-point notation (programmer-defined precision)                  | "{:.2f}".format(4)     | 4.00         |
| 0[precision]d | Leading 0 notation                                                   | '{:03d}'.format(4)     | 004          |

**Referencing format() Values Correctly**

| Replacement Type                | Example                                                                                        | Output                           |
| ------------------------------- | ---------------------------------------------------------------------------------------------- | -------------------------------- |
| Inferred positional replacement | "{:s} ${:.2f} tacos is ${:.2f} total".format("Three", 1.50, 4.50)                              | Three $1.50 tacos is $4.50 total |
| Positional replacement          | "{0:s} ${2:.2f} tacos is ${1:.2f} total".format("Three", 4.50, 1.50)                           | Three $1.50 tacos is $4.50 total |
| Named replacement               | "{cnt:s} ${cost:.2f} tacos is ${sum:.2f} total".format(cnt = "Three", cost = 1.50, sum = 4.50) | Three $1.50 tacos is $4.50 total |
