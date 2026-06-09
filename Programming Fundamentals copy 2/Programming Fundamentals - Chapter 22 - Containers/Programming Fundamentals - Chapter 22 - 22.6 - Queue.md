### queue class
- The **queue** class defined within the C++ Standard Template Library (STL) defines a container of ordered elements that supports element insertion at the tail and element retrieval from the head.
- A queue's **push()** function adds an element to the tail of the queue and increases the queue's size by one
- A queue's **front()** function returns the element at the head of the queue
- And a queue's **pop()** function removes the element at the head of the queue. If a queue is empty, front() results in undefined behavior, thus one should check a queue's size before using front().