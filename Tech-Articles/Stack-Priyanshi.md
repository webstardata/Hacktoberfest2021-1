
=======================================================

Article Title: Stack DS
Author Name: Priyanshi Agarwal
Author Profile: https://github.com/ipiyanshi1708
Date: 28-10-2021

=======================================================

What Does Stack Mean?
A stack is a conceptual structure consisting of a set of homogeneous elements and is based on the principle of last in first out (LIFO). It is a commonly used abstract data type with two major operations, namely push and pop. Push and pop are carried out on the topmost element, which is the item most recently added to the stack. The push operation adds an element to the stack while the pop operation removes an element from the top position. The stack concept is used in programming and memory organization in computers.

A stack represents a sequence of objects or elements in a linear data structure format. The stack consists of a bounded bottom and all the operations are carried out on the top position. Whenever an element is added to the stack by the push operation, the top value is incremented by one, and when an element is popped out from the stack, the top value is decremented by one. A pointer to the top position of the stack is also known as the stack pointer.

A stack may be fixed in size or may have dynamic implementation where the size is allowed to change. In the case of bounded capacity stacks, trying to add an element to an already full stack causes a stack overflow exception. Similarly, a condition where a pop operation tries to remove an element from an already empty stack is known as underflow.

A stack is considered to be a restricted data structure as only a limited number of operations are allowed. Besides the push and pop operations, certain implementations may allow for advanced operations such as:

* Peek — View the topmost item in the stack.
* Duplicate — Copy the top item’s value into a variable and push it back into the stack.
* Swap — Swap the two topmost items in the stack.
* Rotate — Move the topmost elements in the stack as specified by a number or move in a rotating fashion.
* Software implementations of the stack concept are done using arrays and linked lists where the top position is tracked using a variable or header pointer respectively. Many programming languages provide built-in features to support stack implementation.

Hardware stacks are implemented for the purpose of memory allocation and access using a fixed origin and size. Stack registers are used to store the value of the stack pointer.




