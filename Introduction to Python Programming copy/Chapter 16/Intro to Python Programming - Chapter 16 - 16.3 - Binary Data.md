**Binary Data Basics**
- Some files consist of data stored as a sequence of bytes, known as **binary data**, that is not encoded into readable text using an encoding like ASCII or UTF-8
- A **bytes object** is used to represent a sequence of single byte values, such as binary data read from a file. Bytes objects are immutable, just like strings, meaning the value of a bytes object cannot change once created. A byte object can be created using the **bytes()** built-in function
- Programs can also access files using a **binary file mode** by adding a "b" character to the end of the mode strings to a call to open()
- This sequence constitutes the **header** of the binary file, which describes the bitmap's contents

**The Struct Module**
- The **struct** module is commonly used Python standard library module for packing values into sequences of bytes and unpacking sequences of bytes into values (like integers and strings). The **struct.pack()** function packs values such as strings and integers into sequences of bytes
- The "<" character indicates the **byte-order**, or **endianness**, of the conversion, which determines whether the most significant or least significant byte is placed first in the byte sequence ">"
- The **struct.unpack()** module performs the reverse operation of struct.pack(), unpacking a sequence of bytes into a new object