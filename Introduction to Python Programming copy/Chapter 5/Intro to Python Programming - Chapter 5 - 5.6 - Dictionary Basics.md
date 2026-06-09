**Creating a Dictionary**
- A dictionary is a Python container used to describe associative relationships
- It is represented by the dict object type
- A key is a term that can be located in a dictionary
- A value describes some data associated with a key, such as a definition 

**Accessing Dictionary Entries**
- If no entry with a matching key exists in the dictionary, then a KeyError runtime error occurs and the program is terminated

**Adding, modifying, and removing dictionary entries**

- A dictionary is mutable, so entries can be added, modified, and deleted as necessary by a programmer. A new dictionary entry is added by using brackets to specify the key: `prices["banana"] = 1.49`. A dictionary key is unique; attempting to create a new entry with a key that already exists in the dictionary _replaces_ the existing entry. The del keyword is used to remove entries from a dictionary: `del prices["papaya"]` removes the entry whose key is "papaya". If the requested key to delete does not exist, then a KeyError occurs.

**Adding new entries to a dictionary:**

- dict[k] = v: Adds the new key-value pair k-v, if dict[k] does not already exist.  
    Example: `students["John"] = "A+"`

**Modifying existing entries in a dictionary:**

- dict[k] = v: Updates the existing entry dict[k], if dict[k] already exists.  
    Example: `students["Jessica"] = "A+"`

**Removing entries from a dictionary:**

- del dict[k]: Deletes the entry dict[k].  
    Example: `del students["Rachel"]`