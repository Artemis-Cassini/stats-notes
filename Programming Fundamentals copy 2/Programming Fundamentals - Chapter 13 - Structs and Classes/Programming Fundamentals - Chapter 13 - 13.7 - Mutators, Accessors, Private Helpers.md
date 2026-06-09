### Mutators and Accessors
- A **mutator** function may modify ("mutate") a class' data members
- An **accessor** function accesses data members but does not modify a class' data members
- Commonly, a data member has two associated functions: a mutator for setting the value, and an accessor for getting the value, known as a **setter** and **getter** function, respectively, and typically with names starting with set or get. Other mutators and accessors may exist that aren't associated with just one data member, such as the Print() function below.
- The keyword **const** after a member function's name and parameters causes a compiler error if the function modifies a data member
---
### Private Helper Functions
- A programmer commonly creates private functions, known as **private helper functions**, to help public functions carry out tasks
