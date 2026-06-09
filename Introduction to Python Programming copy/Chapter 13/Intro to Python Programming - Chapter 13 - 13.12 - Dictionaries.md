- The **dict** type implements a dictionary in Python
- The **dictionary comprehension**, which evaluates a loop to create a new dictionary, similar to how list comprehension creates a new list
- The **dict()** built-in function, using either keyword arguments to specify the key-value pairs or by specifying a list of tuple pairs

| Operation            | Description                                                                 | Example Code                 |
| -------------------- | --------------------------------------------------------------------------- | ---------------------------- |
| my_dict[key]         | Indexing operation - retrieves the value associated with the key            | jose_grade = my_dict["Jose"] |
| my_dict[key] = value | Adds an entry if the entry does not exist, else modifies the existing entry | my_dict["Jose"] = "B+"       |
| del my_dict[key]     | Deletes the key from a dict                                                 | del my_dict["Jose"]          |
| key in my_dict       | Tests for existence of key in my_dict                                       | if "Jose" in my_dict: # .... |
