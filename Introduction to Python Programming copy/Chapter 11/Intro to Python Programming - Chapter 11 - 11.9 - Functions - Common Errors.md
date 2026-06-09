**Copy-Paste Errors**
- A common error is to copy and paste code among functions by not complete all necessary modifications to the pasted code. For example, a programmer might have developed and tested a function to convert a temperature value in Celsius to Fahrenheit, and then copied and modified the original function into a new function to convert Fahrenheit to Celsius

**Return Errors**
- Another common error is to return the wrong variable, like if return temperature had been used in the temperature conversion program by accident. The function will work and sometimes even return the correct value
- Another common error is to fail to return a value for a function. If execution reaches the end of a function's statements without encountering a return statement, then the function returns a value of None. If the function is expected to return an actual value, then such an assignment can cause confusion 