**Writing to a File**
- Programs write to a file to store data permanently. The **file.write()** method writes a string argument to a file
- A **mode** indicates how a file is opened, such as whether or not writing to the file is allowed, if existing contents of the file are overwritten or appended, etc.

| Mode | Description                                                                                                                              | Allow read? | Allow write? | Create missing file? | Overwrite file? |
| ---- | ---------------------------------------------------------------------------------------------------------------------------------------- | ----------- | ------------ | -------------------- | --------------- |
| "r"  | Open the file for reading                                                                                                                | Yes         | No           | No                   | No              |
| "w"  | Open the file for writing. If the file does not exist, then the file is created. Contents of an existing file are overwritten            | No          | Yes          | Yes                  | Yes             |
| "a"  | Open the file for appending. If the file does not exist, then the file is created. Writes are added to the end of existing file contents | No          | Yes          | Yes                  | No              |
- A programmer can add a "+" character to the end or a mode to specify an update mode

**Output Buffer**
- The **flush()** file method can be called to force the interpreter to flush the output buffer to disk