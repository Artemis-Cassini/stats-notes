### Polymorphism
- **Polymorphism** refers to determining which program behavior to execute depending on data types
- **Compile-time polymorphism** is when the compiler determines which function to call at compile-time
- **Runtime polymorphism** - is when the compiler is unable to determine which function to call at compile-time, so the determination is made while the program is running.
- The program above uses a C++ feature called **derived/base class pointer conversion**, where a pointer to a derived class is converted to a pointer to the base class without explicit casting.
---
### Virtual Functions
- A **virtual function** is a member function that may be overridden in a derived class and is used for runtime polymorphism
- The **override** keyword is an optional keyword used to indicate that a virtual function is overridden in a derived class
---
### Pure Virtual Functions
- A **pure virtual function** is a virtual function that provides no definition in the base class, and all derived classes must override the function
- A class that has at least one pure virtual function is known as an **abstract base class**