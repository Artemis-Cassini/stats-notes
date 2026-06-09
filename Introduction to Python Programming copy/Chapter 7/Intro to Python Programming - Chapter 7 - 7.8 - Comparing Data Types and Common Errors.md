**Comparing Integers, Strings, and Floating-Point Types**
- Floating-point types should not be compared using the equality operators, due to the imprecise representation of floating-point numbers
- The operators can also be used for the string type
- Strings are equal if they have the same number of characters and corresponding characters are identical
- Numbers are arithmetically compared
- Strings are compared by converting each character to a number value (ASCII or Unicode), and then comparing each character in order. Most string comparisons use equality operators "== " or "!=", as in today == "Friday"
- List and tuples are compared via an ordered comparison of every element in the sequence. Every element between the sequences must compare as equal for an equality operator to evaluate to True. Relational operators like < or > can also be used: The result is determined by the first mismatching elements in the sequences. For example, if x = [1, 5, 2] and y = [1, 4, 3], then evaluating `x < y` first evaluates that 1 and 1 match. Since the first list elements match, neither list can be considered to be less than the other, nor can the lists be declared equal without comparing more elements. So the next elements must be compared. The next elements do not match, so `5 < 4` is evaluated, which produces a value of False.
- Dictionaries are compared only with == and !=. To be equal, two dictionaries must have the same set of keys and the same corresponding value for each key.

**Common Branching Errors**
- A common error is to use = rather than == in an if-else expression
- Another common error is to use invalid character sequences like =>, !<, or <>. which are not valid operators 