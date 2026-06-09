**Printing from a Function**
- A function with no return statement is called a **void function**, and such a function returns the value None
- A function that produces output can also return a value, but this material separates these operations for clarity. A function that both outputs and returns a value is not void.

**Calling a Print Function Multiple Times**
- One benefit of a print function is that complex output statements can be written in code once. Then the print function can be called multiple times to produce the output instead of rewriting complex statements for every necessary instance. Changes to output and formatting are made easier and are less prone to error.

**Example - Menu System**
```
def print_menu():
    print("Today's Menu:")
    print("   1) Gumbo")
    print("   2) Jambalaya")
    print("   3) Quit\n")

quit_program = False

while not quit_program :
    print_menu()
    choice = int(input("Enter choice: "))
    if choice == 3 :
        print("Goodbye")
        quit_program = True
    else :
        print("Order: ", end="")
        if choice == 1 :
            print("Gumbo")
        elif choice == 2 :
            print("Jambalaya")
        print()
```

