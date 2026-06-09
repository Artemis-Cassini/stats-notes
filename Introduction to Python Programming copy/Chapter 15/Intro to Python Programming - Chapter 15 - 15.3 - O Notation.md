**Big O Notation**
- **Big O notation** is a mathematical way of describing how a function (running time, or runtime, of an algorithm) behaves in relation to the input size
- Given a function that describes the runtime of an algorithm, the Big O notation for that function can be determined using the following rules:
	1. If f(x) is a sum of several terms, the highest order term (the one with the fastest growth rate) is kept and others are discarded.
	2. If f(x) has a term that is a product of several factors, all constants (those that are not in terms of x) are omitted.

| Composite Function | Big O Notation    |
| ------------------ | ----------------- |
| c * O(f(x))        | O(f(x))           |
| c + O(f(x))        | O(f(x))           |
| g(x) * O(f(x))     | O(g(x) * O(f(x))) |
| g(x) + O(f(x))     | O(g(x) + O(f(x))) |

**Runtime Growth Rate**

| Function | N = 10 | N = 50     | N = 100 | N = 1000 | N = 10000  | N = 100000 |
| -------- | ------ | ---------- | ------- | -------- | ---------- | ---------- |
| log_2N   | 3.3 μs | 5.65 μs    | 6.6 μs  | 9.9 μs   | 13.3 μs    | 16.6 μs    |
| N        | 10 μs  | 50 μs      | 100 μs  | 1000 μs  | 10 ms      | 0.1 s      |
| Nlog_2N  | .03 ms | .28 ms     | .66 ms  | .099 s   | .132 s     | 1.66 s     |
| N^2      | .1 ms  | 2.5 ms     | 10 ms   | 1 s      | 100 s      | 2.7 hours  |
| N^3      | 1 ms   | .125 s     | 1 s     | 16.7 min | 11.57 days | 31.7 years |
| 2^N      | .001 s | 35.7 years | *       | *        | *          | *          |
