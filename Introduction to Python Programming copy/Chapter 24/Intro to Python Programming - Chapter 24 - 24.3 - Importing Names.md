- A programmer can specify names to import a module by using the **from** keyword in an import statement

| Description                        | Example Import Statement       | Using Imported Names      |
| ---------------------------------- | ------------------------------ | ------------------------- |
| Import an entire module            | import HTTPServer              | print(HTTPServer.address) |
| Import specific name from a module | from HTTPServer import address | print(address)            |
- The program below imports names from the **hashlib** module, a Python standard library module that contains a number of algorithms for creating a secure **hash** or a text message