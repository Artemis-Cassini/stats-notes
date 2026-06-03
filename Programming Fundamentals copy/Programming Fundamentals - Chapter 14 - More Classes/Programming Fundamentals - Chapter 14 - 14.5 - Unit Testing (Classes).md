### Testbenches
- A **testbench** is a program whose job is to throughly test another program (or portion) via a series of input/output checks known as **test cases**
- **Unit testing** means to create and run a testbench for a specific item (or “unit”) like a function or a class

- Automatic checks. Ex: Values are compared, as in `testData.GetNum1() != 100`. For conciseness, only fails are printed.
- Independent test cases. Ex: The test case for GetAverage() assigns new values, vs. relying on earlier values.
- **100% code coverage**: Every line of code is executed. A good testbench would have more test cases than below.
- Includes not just typical values but also **border cases**: Unusual or extreme test case values like 0, negative numbers, or large numbers.
---
### Regression Testing
- **Regression testing** means to retest an item like a class anytime that item is changed; if previously-passed test cases fail, the item has "regressed"