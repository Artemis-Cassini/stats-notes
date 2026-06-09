- A **pointer** is a variable that contains a memory address
---
### Vectors use Dynamically Allocated Arrays
- The C++ vector class is a container that internally uses a **dynamically allocated array**, an array whose size can change during runtime
---
### Inserting/erasing in vectors vs. linked lists
- If a program has a vector with thousands of elements, a single call to insert() or erase() can require thousands of instructions and cause the program to run very slowly, often called the **vector insert/erase performance problem**
- A **linked list** consists of items that contain both data and a pointer (or link) to the next list item
---
### Pointers used to Call Class Member Functions
- When a class member function is called on an object, a pointer to the object is automatically passed to the member function as an implicit parameter called the **this** pointer
