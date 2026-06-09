**Interacting with a File System using the OS Module**
- The Python standard library's **OS module** provides an interface to operating system function calls and is thus a critical piece of a Python programmer's toolbox
- **Portability**, the ability to access an item easily from multiple locations, must be considered when reading and writing files outside the executing program's directory since file path representations often differ between operating systems
- The character between directories, "\\" or "/", is called the **path separator**, and using the incorrect path separator may result in that file not being found
- **os.path.sep** stores the path separator for the current operating system

**More os.path Functions**
- The **os.walk()** function "walks" a directory tree like the one above, visiting each subdirectory in the specified path