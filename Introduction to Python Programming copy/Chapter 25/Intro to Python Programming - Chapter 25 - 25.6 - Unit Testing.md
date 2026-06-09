- Maintaining a **test suite**, or a set of repeatable tests, that run after changing the source code of a program is critical
- A programmer commonly performs **unit testing**, or testing the individual components of a program, such as specific methods, class interfaces, data structures, and so on. The Python standard library **unittest** module implements unit testing functionality
- A unit test performs **assertions** to check if a computed value meets certain requirements

| Method                   | Checks That          |
| ------------------------ | -------------------- |
| assertEqual(a, b)        | a == b               |
| assertNotEqual(a,b)      | a != b               |
| assertTrue(x)            | bool (x) is True     |
| assertFalse(x)           | bool (x) is False    |
| assertIs(a, b)           | a is b               |
| assertIsNot(a,b)         | a is not b           |
| assertIsNone(x)          | x is None            |
| assertIsNotNone(x)       | x is not None        |
| assertIn(a, b)           | a in b               |
| assertNoneIn(a, b)       | a not in b           |
| assertAlmostEqual(a, b)  | round(a - b, 7) == 0 |
| assertGreater(a, b)      | a > b                |
| assertGreaterEqual(a, b) | a >= b               |
| assertLess(a, b)         | a < b                |
| assertLessEqual(a, b)    | a <= b               |
