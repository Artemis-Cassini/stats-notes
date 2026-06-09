**Common List Methods**
- A **list method** can perform a useful operation on a list such as adding or removing elements, sorting, reversing, etc

**Adding Elements

| List Method       | Description                            | Code Example                                  | >Final my_list value |
| ----------------- | -------------------------------------- | --------------------------------------------- | -------------------- |
| list.append(x)    | Add an item to the end of list         | my_list = [5, 8]  <br>my_list.append(16)      | [5, 8, 16]           |
| list.extend([x])  | Add all items in [x] to list           | my_list = [5, 8]  <br>my_list.extend([4, 12]) | [5, 8, 4, 12]        |
| list.insert(i, x) | Insert x into list *before* position i | my_list = [5, 8]  <br>my_list.insert(1, 1.7)  | [5, 1.7, 8]          |
**Removing Elements**

| List Method    | Description                                  | Code Example                                   | Final my_list value |
| -------------- | -------------------------------------------- | ---------------------------------------------- | ------------------- |
| list.remove(x) | Remove first item from list with value x     | my_list = [5, 8, 14]  <br>my_list.remove(8)    | [5, 14]             |
| list.pop()     | Remove and return last item in list          | my_list = [5, 8, 14]  <br>val = my_list.pop()  | [5, 8]<br>val is 14 |
| list.pop(i)    | Remove and return item at position i in list | my_list = [5, 8, 14]  <br>val = my_list.pop(0) | [8, 14]<br>val is 5 |
**Modifying Elements**

| List Method    | Description                           | Code Example                                | Final my_list value |
| -------------- | ------------------------------------- | ------------------------------------------- | ------------------- |
| list.sort()    | Sort the items of list in-place       | my_list = [14, 5, 8]  <br>my_list.sort()    | [5, 8, 14]          |
| list.reverse() | Reverse the elements of list in-place | my_list = [14, 5, 8]  <br>my_list.reverse() | [8, 5, 14]          |
**Miscellaneous**

| List Method   | Description                                     | Code Example                                            | Final my_list value |
| ------------- | ----------------------------------------------- | ------------------------------------------------------- | ------------------- |
| list.index(x) | Return index of first item in list with value x | my_list = [5, 8, 14]  <br>print(my_list.index(14))      | Prints "2"          |
| list.count(x) | Count the number of times value x is in list    | my_list = [5, 8, 5, 5, 14]  <br>print(my_list.count(5)) | Prints "3"          |
