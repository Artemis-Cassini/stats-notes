**Module Basics**
- Thus, a programmer will typically write Python code in a file, and then pass that file as input to the interpreter. Such a file is called a **script**
- A solution is to use a **module**, which is a file containing Python code that can be imported and used by scripts, other modules, or the interactive interpreter. To **import** a module means to execute the code contained by the module and make the definitions within that module available for use by the importing program
- A module being required by another program is often called a **dependency**

**Importing a Module**
- Evaluating an import statement initiates the following process to load the module
	- A check is conducted to determine whether the module has already been imported. If already imported, then the loaded module is used
	- If not already imported, a new module object is created and inserted in sys.modules
	- The code in the module is executed in the new module object's namespace
- A dictionary of the loaded modules is stored in **sys.modules**. A **module object** is simply a namespace that contains definitions from the module

**Using an Imported Module**
- Once a module has been imported, the program can access the definitions of a module using attribute reference operations
