
=======================================================

Article Title: Array Data Structure
Author Name: Rohan Tyagi
Author Profile: https://github.com/Tyagirohan
Date: 30-10-2021

=======================================================

What are Arrays?
An array is a data structure for storing more than one data item that has a similar data type. The items of an array are allocated at adjacent memory locations. These memory locations are called elements of that array.
The total number of elements in an array is called length. The details of an array are accessed about its position. This reference is called index or subscript

Why do we need arrays?
•	Arrays are best for storing multiple values in a single variable
•	Arrays are better at processing many values easily and quickly
•	Sorting and searching the values is easier in arrays


Creating an Array in C++
The following code illustrates how you can create an integer array in C++ to store Marks:
#include <iostream>
using namespace std;
int main()
{ int marks[3] = { 99, 95, 100 };
 for (int i = 0; i < 3; i++)
  {   cout << "value of i: " << marks[i] << endl;}	
  return 0;
}


Ways to Declare an Array in C++
Declaration by Size
Syntax  :   dataType arrayName[arraySize];
Example :  int marks[3];
Declaration Initialization Array Items Only
Syntax :   dataType arrayName[] = {array, items};
Example  :   int marks[] = { 99, 95, 100 };
Declaration by Size and Initialization Array Items
Syntax  :   dataType arrayName[arraySize] = {array, items};
Example :    int marks[3] = { 99, 95, 100 };


How to access a specific array value?
You can access any array item by using its index.
Syntax  :   arrayName[indexNum]
Example   :  marks[1]

Advantages of an Array in C/C++: 
1.	Random access of elements using array index.
2.	Use of less line of code as it creates a single array of multiple elements.
3.	Easy access to all the elements.
4.	Traversal through the array becomes easy using a single loop.
5.	Sorting becomes easy as it can be accomplished by writing less line of code.


Disadvantages of an Array in C/C++: 
1.	Allows a fixed number of elements to be entered which is decided at the time of declaration. Unlike a linked list, an array in C is not dynamic.

2.	Insertion and deletion of elements can be costly since the elements are needed to be managed in accordance with the new memory allocation.


