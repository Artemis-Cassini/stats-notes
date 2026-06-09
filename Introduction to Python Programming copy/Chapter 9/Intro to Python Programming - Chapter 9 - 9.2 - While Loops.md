**Introduction to While Loops**
- A **while loop** runs a block of code repeatedly as long as the while loop's condition is True. If the while loop's condition if False, then the while loop ends. Ex. A guessing game is played until a player guesses the correct answer
```
while expression: # Loop expression
	# Loop body: Statements to execute
	# if the loop expression evaluates to True
	
# Statements to execute after the expression evaluates to False
```

**Sentinel Values**
- A **sentinel value** is a value that causes a loop to end. Ex. A while loop runs until a user inputs the sentinel value "stop", causing the loop to terminate. The user controls when the loop ends, thus distinguishing a loop with a sentinel value from other loops

**Infinite Loops**
- An **infinite loop** is a loop that never stops running because the loop's condition is always True. Ex. A loop that repeatedly prints a message without any condition to stop
- A common error is to accidentally create an infinite loop by assuming equality will be reached. Good practice is to include greater than or less than along with equality in a loop expression to help avoid unintended infinite loops
- An infinite loop can be valid in some programs. Ex. An infinite loop in a game checks for user input in real-time