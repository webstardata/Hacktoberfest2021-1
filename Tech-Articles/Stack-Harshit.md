
=======================================================

Article Title: Stack Data Structure
Author Name: Harshit Sharma
Author Profile: https://github.com/harshit-sharma-gits
Date: 13-10-21

=======================================================

What is Stack Data Structure?

Stack is an abstract data type with a bounded(predefined) capacity.
It is a simple data structure that allows adding and removing elements in a particular order.
Every time an element is added, it goes on the top of the stack and the only element that can be removed is the element that is at the top of the stack, just like a pile of objects.

Basic features of Stack

Stack is an ordered list of similar data type.
Stack is a LIFO(Last in First out) structure or we can say FILO(First in Last out).
push() function is used to insert new elements into the Stack and pop() function is used to remove an element from the stack. Both insertion and removal are allowed at only one end of Stack called Top.
Stack is said to be in Overflow state when it is completely full and is said to be in Underflow state if it is completely empty.

Implementation of Stack Data Structure

Stack can be easily implemented using an Array or a Linked List. Arrays are quick, but are limited in size and Linked List requires overhead to allocate, link, unlink, and deallocate, but is not limited in size. Here we will implement Stack using array.

Algorithm for PUSH operation

Check if the stack is full or not.
If the stack is full, then print error of overflow and exit the program.
If the stack is not full, then increment the top and add the element.

Algorithm for POP operation

Check if the stack is empty or not.
If the stack is empty, then print error of underflow and exit the program.
If the stack is not empty, then print the element at the top and decrement the top.
