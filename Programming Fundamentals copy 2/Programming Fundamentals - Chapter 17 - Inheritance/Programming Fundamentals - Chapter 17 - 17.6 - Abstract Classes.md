### Abstract and Concrete Classes
- A **pure virtual function** is a virtual function that is not implemented in the base class, thus all derived classes must override the function
- An **abstract class** is a class that cannot be instantiated as an object, but is the superclass for a subclass and specifies how the subclass must be implemented. Any class with one or more pure virtual functions is abstract.
- A **concrete class** is a class that is not abstract, and hence _can_ be instantiated.