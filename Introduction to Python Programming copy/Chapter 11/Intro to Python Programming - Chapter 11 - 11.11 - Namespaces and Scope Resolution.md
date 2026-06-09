**Namespace**
- A **namespace** maps names to objects. The Python interpreter uses namespaces to track all of the objects in a program. For example, when executing z = x + y, the interpreter looks in a namespace to find the value of the objects referenced by x and y, evaluates the expression, and then updates z in the namespace with the expression's result
- A namespace is a normal Python dictionary whose keys are the names and whose values are the objects. A programmer can examine the names in the current local and global namespace by using the `locals()` and `globals()` built-in functions.
- By default, a few names already exist in the global namespace – those names have been omitted in the output for brevity. Notice that `my_var` and `my_func` are added into the namespace once assigned.

**Scope and Scope Resolution**
- **Scope** is the area of code where a name is visible. Namespaces are used to make scope work. Each scope, such as global scope or a local function scope, has its own namespace. If a namespace contains a name at a specific location in the code, then that name is visible and a programmer can use it in an expression
- At least three nested scopes are active at any point in a program's execution
	- Built-in scope - Contains all of the built-in names of Python, such as int(), str(), list(), range(), etc.
	- Global scope - Contains all globally defined names outside of any functions
	- Local scope - Refers to scope within the currently executing function but is the same as global scope if no function is executing
- When a name is referenced in code, the local scope's namespace is the first checked, followed by the global scope, and finally the built-in scope. If the name cannot be found in any namespace, the interpreter generates a NameError. The process of searching for a name in the available namespaces is called **scope resolution**

**More Scoping and Namespaces**
- The concept of scopes and namespaces explains how multiple variables can share the same name, yet have different values. Consider the following program that first creates a variable `tmp` in the global namespace, then creates another variable named `tmp` in a local function. The assignment statement in the `avg()` function creates a new variable within the function's local namespace. When the function returns, the namespace is deleted as well (since the local variables are now out of scope). The later statement `print f"Sum: {tmp:f}"` looks up the name `tmp` in the global scope, finding the `tmp` previously created with the statement `tmp = a + b`.
