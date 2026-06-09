**Counting With a While Loop**
- Counting is a common task in programming, often done using a loop. A **loop variable** can be used for counting and is updated during each iteration until the loop condition is False. Ex. If a while loop iterates 10 times, the loop variable can output values from 1 to 10 when incremented inside the loop body to count the iterations
- A common error is to forget to update the loop variable at the end of the loop, causing an unintended infinite loop

**Variations on Counting with a While Loop**
- A variation on counting with a while loop is to decrement the loop variable to count down. Another variation is to increment or decrement in steps greater than 1. Also, the loop variable can be modified using other arithmetic operations, including multiplication or division

**Other Compound Operators**
- variation += 5 increments variation by 5 (that is, variation - variation + 5)
- variation * = 5 multiplies variation by 5 (that is, variation = variation * 5)
- variation /= 5 divides variation by 5 (that is, variation = variation / 5)
- When changing how the loop variable is updated, the variable's initialization and the loop condition may also need to be adjusted for the loop to start, count, and end as expected 

**Applications of Counting with a While Loop**
- Counting with a while loop has applications for mathematics and sequence calculations. Ex. A loop variable can be used when programming the following
- N factorial (N!) id the product of all positive integers less than or equal to N (that is, N! = N * (N - 1) * (N - 2) * ... * 1)
- The Fibonacci sequence starts with 0 or 1, and each subsequent integer is the sum of the two preceding integers
- A savings interest program can calculate the yearly savings with interest (Ex. savings += (savings * interest_rate))