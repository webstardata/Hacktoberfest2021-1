
=======================================================

Article Title: Bitwise Operators
Author Name: Vishal Kumar
Author Profile: https://github.com/LahsivK4070
Date: 21-10-2021

=======================================================

What are Bitwise Operators?

As we all are familiar that numbers are stored in a computer’s memory in binary representation i.e. either 0 or 1.
The bitwise operators allow the operations to be performed faster than other operators since they work directly on the bits.
Bitwise operators are used to manipulate values for comparisons and calculations.

Types of Bitwise Operators

Following are the different bitwise operators
•	Bitwise AND (&)
  o	Syntax: A & B
  o	Value: A & B = 1 if and only if A = 1 and B = 1.
	
•	Bitwise OR (|)
  o	Syntax: A | B
  o	Value: A | B = 0 if and only if A = 0 and B = 0.

•	Bitwise NOT (~)
  o	Syntax: ~A (It works on a single operand)
  o	Value: ~A means inverse of A. 0 if A is 1 and 1 if A is 0.

•	Bitwise XOR (^)
  o	Syntax: A ^ B
  o	Value: A ^ B = 1 when A and B are different.

There are two more operators which are called left shift (<<) and right shift (>>) operators.

•	Left-shift operator (<<)
  o	Syntax: A << x
  o	A << x implies shifting the bits of A to the left by x positions. We can also say that 
    A << x is equal to A multiply by pow(2, x).

•	Right-shift operator (>>)
  o	Syntax: A >> x
  o	A >> x implies shifting the bits of A to the right by x positions. We can also say that 
    A >> x is equal to A divided by pow(2, x).

Thing to keep in mind

The result of logical operators (&&, || and !) is either 0 or 1, but bitwise operators return an integer value.
Also, the logical operators consider any non-zero operand as 1.



