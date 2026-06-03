### A First Program
- A **program** starts in main(), executing the statements within main's braces {}, one at a time
- Each statement typically appears alone on a line and ends with a **semicolon**, as English sentences end with a period
- The ***int wage*** statement creates an integer variable named wage. The ***wage = 20*** statement assigns wage with 20
- The cout statements output various values
- The ***return 0*** statement ends the program (the - tells the operating system the program ended without error)

- **Code** is the textual representation of a program. Many code editors color words to assist humans to understand various words' roles

---
### Basic Input
- Programs commonly get input values, perform some processing on that input, and put output values to a screen or elsewhere. Input is commonly gotten from a keyboard, a file, fields on a web form or app, etc.
- The following statement gets an input value and puts that value into variable x: **ch**>> x; cin is short for *characters in*
```
#include <iostream>
using namespace std;

int main(){
	int wage;
	
	cin >> wage;
	
	cout << "Salary is ";
	cout << wage * 40 * 52;
	cout << end1;
	
	return 0;
}
```

---
### Basic Output Text
- The **cout** construct supports output; cout is short for *character out*. Outputting text is achieved via: ***cout << "desired text";***
- Text in double quotes " " is known as a **string literal**. Multiple cout statements continue printing on the same output line
- The statement ***cout << end1;*** starts a new output line, called a **newline**
- Note: **endl** is short for "end line" *A common error is to type the number "1" of a capital I as in "in", instead of a lowercase l as in "end line"*
- 