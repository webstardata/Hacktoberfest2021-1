
=======================================================

Article Title: Array Introduction
Author Name: Ankur Bajpai
Author Profile: https://github.com/ankurbajpai125
Date: 30-10-2021

=======================================================

<Write-Your-Complete-Tech-Article-Here>
  
                                      ARRAY INTRODUCTION
  
Overview

An array is a collection of data items, all of the same type, accessed using a common name.
A one-dimensional array is like a list;  A two dimensional array is like a table;  The C language places no limits on the number of dimensions in an array, though specific implementations may.
Some texts refer to one-dimensional arrays as vectors, two-dimensional arrays as matrices, and use the general term arrays when the number of dimensions is unspecified or unimportant.

Declaring Arrays

Array variables are declared identically to variables of their data type, except that the variable name is followed by one pair of square [ ] brackets for each dimension of the array.
Uninitialized arrays must have the dimensions of their rows, columns, etc. listed within the square brackets.
Dimensions used when declaring arrays in C must be positive integral constants or constant expressions.
In C99, dimensions must still be positive integers, but variables can be used, so long as the variable has a positive value at the time the array is declared. ( Space is allocated only once, at the time the array is declared. The array does NOT change sizes later if the variable used to declare it changes. )

Initializing Arrays

Arrays may be initialized when they are declared, just as any other variables.
Place the initialization data in curly {} braces following the equals sign.  Note the use of commas in the examples below.
An array may be partially initialized, by providing fewer data items than the size of the array.  The remaining array elements will be automatically initialized to zero.
If an array is to be completely initialized, the dimension of the array is not required.  The compiler will automatically size the array to fit the initialized data. 


