### unique_ptr for single objects
- A **smart pointer** is a class that wraps around a pointer to an object to simplify the memory management of the object
- To distinguish a smart pointer from a pointer, the latter is referred to as a raw pointer in this section. **unique_ptr** is a smart pointer that permits only one owner over an object