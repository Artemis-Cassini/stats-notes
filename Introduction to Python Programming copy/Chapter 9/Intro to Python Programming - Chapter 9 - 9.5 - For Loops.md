**Introduction to For Loops**
- A common programming task is to access all of the elements in a container, one by one, so that the elements can be used. Ex. Printing every item in a list. A **for loop** statement iterates over each element in a container one at a time, assigning a variable to the next element to use in the loop body. Each iteration updates the variable with the next element. The container is typically a list, string, or dictionary. A for loop is made of a for statement, followed by an indented loop body

```
for variable in container:
	# Loop body: Statements to execute
	# for each item in the container
	
# Statements to execute after the for loop is complete
```

**For Loops with Strings and Dictionaries**
- A for loop can iterate over other containers such as strings and dictionaries. A string is a sequence type like a list, so the behavior of the loop is identical. Each iteration assigns the loop variable with the next character in the string. Ex. A for loop iterates over each character in the string "blue" beginning with "b" as the leftmost character, then each following character in the string
- Iterating over a dictionary using a for loop assigns the loop variable with each key in the dictionary in the order the keys were inserted. The key's value can then be accessed using the key

**For Loop Examples**
- For loops can be used to perform action during each loop iteration. A simple example is printing the value, as above examples demonstrated. The program below uses an additional variable to sum list elements to calculate weekly and average daily revenue
- A for loop may also iterate backward over a sequence, starting at the last element and ending with the first element, by using the **reversed()** function to reverse the order of the elements