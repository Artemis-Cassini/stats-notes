### Generating a Random Number
- The **rand()** function, in the C standard library, returns a random integer each time the function is called, in the range 0 to RAND_MAX

---
### Pseudo-Random
- Internally, the rand() function has an equation to compute the next "random" integer from the previous one, (invisibly) keeping track of the previous one. For the first call to rand(), no previous random integer exists, so the function uses a built-in integer known as the **seed**
- The function **time()** returns the number of seconds since Jan 1, 1970