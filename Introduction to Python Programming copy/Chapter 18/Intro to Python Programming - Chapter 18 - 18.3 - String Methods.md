**Finding and Replacing**
- **replace(old, new)** - Returns a copy of the string with all occurrences of the substring old replaced by the string new. The old and new arguments may be string variables or string literals
- **replace(old, new, count)** - Same as above, except replace(old, new, count) only replaces the first count occurrences of old
- **find(x)** - Returns the index of the first occurrence of item x in the string, otherwise, find(x) returns -1. x may be a string variable or string literal. Recall that in a string, the index of the first character is 0, not 1
- **find(x, start)** - Same as find(x), but begins the search at index start
- **find(x, start, end)** - Same as find(x, start), but stops the search as index end -1
- **rfind(x)** - Same as find(x) but searches the strings in reverse, returning the last occurrence in the string
- **count(x)** - Returns the number of times x occurs in the string

**Comparing Strings**

| Example                         | Expression Result | Why?                                                                                                                                                                           |
| ------------------------------- | ----------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ |
| "Hello" == "Hello"              | Ture              | The strings are exactly identical values                                                                                                                                       |
| "Hello" == "Hello!"             | False             | The left hand string does not end with "!"                                                                                                                                     |
| "Yankee Sierra" > "Amy Wise"    | True              | The first character of the left side "Y" is "greater than" the first character of the right side "A"                                                                           |
| "Yankee Sierra" > "Yankee Zulu" | False             | The character of both sides match until the second word. The first character of the second word on the left "S is not "greater than" the first character on the right side "Z" |
| "seph" in "Joseph"              | True              | The substring "seph" can be found starting at the 3rd position of "Joseph"                                                                                                     |
| "jo" in "Joseph"                | False             | "jo" is not in "Joseph"                                                                                                                                                        |
- An **ASCII table** provides a quick lookup of ASCII values
- **isalnum()** - Returns True is all characters in the string are lowercase or uppercase letters, or the numbers 0-9
- **isdigit()** - Returns True if all characters are the numbers 0-9
- **islower()** - Returns True if all cased characters are lowercase letters
- **isupper()**  - Returns True if all cased characters are uppercase letters
- **isspace()** - Returns True if all characters are whitespace
- **startswith(x)** - Returns True if the string starts with x
- **endswith(x)** - Returns True if the string ends with x

**Creating New Strings from a String**
- **capitalize()** - Returns a copy of the string with the first character capitalized and the rest lowercased
- **lower()** - Returns a copy of the string with all characters lowercased
- **upper()** - Returns a copy of the string with all characters uppercased
- **strip()** - Returns a copy of the string with leading and trailing whitespace removed
- **title()** - Returns a copy of the string as a title, with first letters of word capitalized