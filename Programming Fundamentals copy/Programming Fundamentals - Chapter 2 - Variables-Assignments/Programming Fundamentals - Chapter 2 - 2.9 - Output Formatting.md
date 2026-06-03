### Floating-Point Manipulators 
- A **manipulator** is a function that overloads the insertion operator << or extraction operator >> to adjust the way output appears

| Manipulator     | Description                                                                                                                                                                                                                                                    |
| --------------- | -------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| fixed           | Use fixed-point notation.  <br>From < iostream >                                                                                                                                                                                                               |
| scientific      | Use scientific notation.  <br>From < iostream >                                                                                                                                                                                                                |
| setprecision(p) | If stream has not been manipulated to fixed or scientific:  <br>Sets max number of digits in number<br>If stream has been manipulated to fixed or scientific:  <br>Sets max number of digits in fraction only (after the decimal point).  <br>From < iomanip > |
| showpoint       | Even if fraction is 0, show decimal point and trailing 0s.  <br>Opposite is noshowpoint.  <br>From < iostream >                                                                                                                                                |

| Manipulator | Description                                                                                                                                                                                                            |
| ----------- | ---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| setw(n)     | Sets the number of characters for the next output item only  <br>(does not persist, in contrast to other manipulators).  <br>By default, the item will be right-aligned, and filled with spaces.  <br>From < iomanip > |
| setfill(c)  | Sets the fill to character c.  <br>From < iomanip >                                                                                                                                                                    |
| left        | Changes to left alignment.  <br>From < iostream >                                                                                                                                                                      |
| right       | Changes back to right alignment.  <br>From < iostream >                                                                                                                                                                |

| Manipulator | Description                                                                                                                     |
| ----------- | ------------------------------------------------------------------------------------------------------------------------------- |
| endl        | Inserts a newline character '\n' into the output buffer  <br>and informs the system to flush the buffer.  <br>From < iostream > |
| flush       | Informs the system to flush the buffer.  <br>From < iostream >                                                                  |
