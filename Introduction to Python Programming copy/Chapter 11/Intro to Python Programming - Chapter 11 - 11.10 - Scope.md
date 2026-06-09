**Variable and Function Scope**
- A variable or function object is only visible to part of a program, known as the object's **scope**. When a variable is created inside a function, the variable's scope is limited to inside that function. In fact, because a variable's name does not exist until bound to an object, the variable's scope is actually limited to after the first assignment of the variable until the end of the function
- The following program highlights the scope of variable total_inches. The function's variables total_inches and centimeters are invisible to the code outside of the function and cannot be used. Such variables defined inside a function called **local variables**

**Global Variables**
- In contrast, a variable defined outside of a function is called a **global variable**. A global variable's scope extends from the assignment to the end of the file and can be accessed inside of functions
- A **global** statement must be used to change the value of a global variable inside of a function.