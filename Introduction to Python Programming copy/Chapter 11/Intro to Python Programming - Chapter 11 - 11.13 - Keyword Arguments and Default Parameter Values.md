**Keyword Arguments**
- Sometimes a function requires many arguments. In such cases, a function call can become very long and difficult to read. Furthermore, a programmer might easily make a mistake when calling such a function if the ordering of the arguments is giving incorrectly. 
- Python provides for **keyword arguments** that allow arguments to map to parameters by name, instead of implicitly by position in the argument list. When using keyword arguments, the argument list does not need to follow a specific order
- Keyword arguments provide a bit of clarity to potentially confusing function calls. 
- Keyword arguments can be mixed with positional arguments, provided that the keyword arguments come last

**Default Parameter Values**
- Sometimes a function has parameters that are option. A function can have a **default parameter value** for one or more parameters, meaning that a function call can optionally omit an argument, and the default parameter value will be substituted for the corresponding omitted argument 
- A parameter's **default value** is the value used in the absence of an argument in the function call

**Mixing Keyword Arguments and Default Parameter Values**
- Mixing keyword arguments and default parameter values allows a programmer to omit arbitrary arguments from a function call. Because keyword arguments use names instead of position to match arguments to parameters, any argument can be omitted as long as that argument has a default value.