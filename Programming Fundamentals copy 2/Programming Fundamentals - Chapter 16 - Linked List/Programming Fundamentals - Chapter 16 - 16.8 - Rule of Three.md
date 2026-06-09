### Rule of Three
- The **rule of three** describes a practice that if a programmer explicitly defines any one of three special member functions (namely, a destructor, copy constructor, or copy assignment operator), then the programmer should explicitly define all three
- Those three special member functions are sometimes called **the big three**
---
### Default destructor, copy constructor, and copy assignment operator
- A **default destructor** does nothing.
- A **default copy constructor** initializes an object's data members with a copy, by value, of another object's corresponding members. Such a copy is called a shallow copy.
- A **default copy assignment operator** assigns an object's data members with a copy, by value, of another object's corresponding members.