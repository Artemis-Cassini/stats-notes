- A programmer often needs to append an additional item to a dynamically allocated array. As the memory locations after the existing array may be used by other dynamically allocated data, a new array with increased capacity must be allocated. The program must also use a variable to hold the array's size.

- Appending a new element to a dynamically allocated array should:
1. Dynamically allocate a new array with space for the additional element.
2. Copy the existing array's elements to the new array.
3. Delete the existing array.
4. Assign the array's pointer with the new array's address.
5. Add the new element to the last index in the new array.
6. Increment the variable holding the array's size.