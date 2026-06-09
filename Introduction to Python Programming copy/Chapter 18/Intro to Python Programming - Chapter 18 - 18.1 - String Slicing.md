**String Slicing Basics**
- An **index** is an integer matching a specific position in a string's sequence of characters

**Slicing and Slicing Operations**
- The Python interpreter creates a new string object for the slice. Thus, creating a slice of the string variable `my_str`, and then changing the value of `my_str`, does not also change the value of the slice.

| Syntax        | Result                            | Description                                                          |
| ------------- | --------------------------------- | -------------------------------------------------------------------- |
| my_str[10:19] | wikipedia                         | Returns the character in indices 10-18                               |
| my_str[10:-5] | wikipedia.org/wiki/               | Returns the character in indices 10-28                               |
| my_str[8:]    | n.wikipedia.org/wiki/Nasa/        | Returns all characters from index 8 until the end of the string      |
| my_str[:23]   | http://en.wikipedia.org           | Returns every character up to index 23, but not including my_str[23] |
| my_str[:-1]   | http://en.wikipedia.org/wiki/Nasa | Returns all but the last character                                   |
**The Slice Stride**
- Slice notation also provides for a third argument known as the stride. The **stride** determines how much to increment the index after reading each element