- A **built-in module** comes pre-installed with Python; examples of built-in modules include sys, time, and math. If no matching built-in module is found, then the interpreter searches for the necessary module in **sys.path**, a built-in Python variable located in the sys module that has a list of directories containing modules
- The sys.path variable initially contains the following directories
	- The directory of the executing script
	- A list of directories specified by the environment variable PYTHONPATH
	  The directory where Python is installed
- An operating system **environment variable** is much like a variable in a Python script, except that an environment variable is stored by the computer's operating system and can be accessed by every program running on the computer