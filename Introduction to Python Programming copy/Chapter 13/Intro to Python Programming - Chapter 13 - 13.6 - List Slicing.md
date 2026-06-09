- A programmer can use **slice notation** to read multiple elements from a list, creating a new list that contains only the desired elements
- An optional component of slice notation is the **stride**, which indicates how many elements are skipped between extracted items in the source list

| Operation                 | Description                                                    | Example Code                                             | Example Output      |
| ------------------------- | -------------------------------------------------------------- | -------------------------------------------------------- | ------------------- |
| my_list[start:end]        | Get a list from start to end (minus 1)                         | my_list = [5, 10, 20]  <br>print(my_list[0:2])           | [5, 10]             |
| my_list[start:end:stride] | Get a list of every stride element from start to end (minus 1) | my_list = [5, 10, 20, 40, 80]  <br>print(my_list[0:5:3]) | [5, 40]             |
| my_list[start:]           | Get a list from start to end of the list                       | my_list = [5, 10, 20, 40, 80]  <br>print(my_list[2:])    | [20, 40, 80]        |
| my_list[:end]             | Get a list from beginning of the list to the end (minus 1)     | my_list = [5, 10, 20, 40, 80]  <br>print(my_list[:4])    | [5, 10, 20, 40]     |
| my_list[:]                | Get a copy of the list                                         | my_list = [5, 10, 20, 40, 80]  <br>print(my_list[:])     | [5, 10, 20, 40, 80] |
