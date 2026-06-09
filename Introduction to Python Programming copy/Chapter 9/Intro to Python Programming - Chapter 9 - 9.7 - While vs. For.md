**While Loop and For Loop Correspondence**
- Both while loops and for loops can be used to count a specific number of loop iterations. A for loop combined with range() is generally preferred over while loops, since for loops are less likely to become stuck in an infinite loop situation. A programmer may easily forget to increment a while loop's variable (causing an infinite loop), but for loops iterate over a finite number of elements in a container and are thus guaranteed to complete

- As a general rule
1. Use a for loop when the number of iterations is computable before entering the loop, as when counting down from X to 0, printing a string N times, etc
2. Use a for loop when accessing the elements of a container, as when adding 1 to every element in a list, or printing the key of every entry in a dict, etc
3. Use a while loop when the number of iterations is not computable before entering the loop, as when iterating until a user enters a particular character

