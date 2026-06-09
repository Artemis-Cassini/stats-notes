**Generating a Random Number**
- The random module, in the Python Standard Library, provides methods that return random values
- The random() method returns a random floating-point value each time the function is called, in the range 0 to 1
- Python's randrange() method generates random integers within a specified range

**Pseudo-random**
- For the first call to any random method, no previous random number exists, so the method uses a built-in integer based on the current time, called a seed, to help generate a random number.