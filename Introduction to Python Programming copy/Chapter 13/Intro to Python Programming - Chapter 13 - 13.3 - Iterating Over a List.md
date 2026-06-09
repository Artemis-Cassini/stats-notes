**List Iteration**
- Looping through a sequence such as a list is so common that Python supports a construct called a **for loop**, specifically for iteration purposes

**IndexError and enumerate()**
- Accessing an index that is out of range causes the program to automatically abort execution and generate an **IndexError**
- The built-in **enumerate()** function iterates over a list and provides an iteration counter 

**Built-In Functions that Iterate over Lists**

| Function  | Description                                                           | Example Code                                     | Example Output |
| --------- | --------------------------------------------------------------------- | ------------------------------------------------ | -------------- |
| all(list) | True if every element in list is True (!= 0), or is the list is empty | print(all([1, 2, 3]))  <br>print(all([0, 1, 2])) | True<br>False  |
| any(list) | True if any element in the list is True                               | print(any([0, 2]))  <br>print(any([0, 0]))       | Ture<br>False  |
| max(list) | Get the maximum element in the list                                   | print(max([-3, 5, 25]))                          | 25             |
| min(list) | Get the minimum element in the list                                   | print(min([-3, 5, 25]))                          | -3             |
| sum(list) | Get the sum of all elements in the list                               | print(sum([-3, 5, 25]))                          | 27             |
