**List Basics**
- A **container** is an object that groups related objects together. A **list** is a **mutable** container, meaning the size of the list can grow or shrink and elements within the list can change
- The **list()** function accepts a single iterable object argument, such as a string, list, or tuple, and returns a new list object

**Accessing List Elements**
- An **index** is a zero-based integer matching to a specific position in the list's sequence of elements

**Common List Operations and In-Place List Modification**
- Such growing and shrinking capability is called **in-place modification**

| Operation           | Description                                                          | Example Code                                             | Example Output  |
| ------------------- | -------------------------------------------------------------------- | -------------------------------------------------------- | --------------- |
| my_list = [1, 2, 3] | Creates a list                                                       | my_list = [1, 2, 3]<br>print(my_list)                    | [1, 2, 3]       |
| list(iter)          | Creates a lit                                                        | my_list = list("123")<br>print(my_list)                  | ['1', '2', '3'] |
| my_list[index]      | Gets an element from a list                                          | my_list = [1, 2, 3]<br>print(my_list[1])                 | 2               |
| my_list[start:end]  | Gets a *new* list containing some of another list's elements         | my_list = [1, 2, 3]<br>print(my_list[1:3])               | [2, 3]          |
| my_list1 + my_list2 | Gets a *new* list with elements of my_list2 added to end of my_list1 | my_list = [1, 2] + [3] <br>print(my_list)                | [1, 2, 3]       |
| my_list[i] = x      | Changes the value of the element at index i in-place                 | my_list = [1, 2, 3]<br>my_list[2] = 9 <br>print(my_list) | [1, 2, 9]       |
| del my_list[i]      | Deletes the element from index i from a list                         | my_list = [1, 2, 3]<br>del my_list[1]<br>print(my_list)  | [1, 3]          |
