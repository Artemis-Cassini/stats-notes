- **Class customization** is the process of defining how an instance of a class should behave for some common operations. To customize a class, a programmer implements instance methods with **special method names** that the Python interpreter recognizes
- Class customization can redefine the functionality of built-in operators like <, >=, +, -, and * when used with class instances, a technique known as **operator overloading**
- Methods like **__lt__** above are known as **rich comparison methods**

| Rich Comparison Method | Overloaded Operator           |
| ---------------------- | ----------------------------- |
| lt (self, other)       | less than (<)                 |
| le (self, other)       | less than or equal to (<=)    |
| gt (self, other)       | greater than (>)              |
| ge (self, other)       | greater than or equal to (>=) |
| eq (self, other)       | equal to (==)                 |
| ne (self, other)       | not equal to (!=)             |
