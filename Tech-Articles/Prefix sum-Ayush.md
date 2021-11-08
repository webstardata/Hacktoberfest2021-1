
=======================================================

Article Title: Prefix sum
Author Name: Ayush Tiwari
Author Profile: https://github.com/ayush-0110
Date: 08/11/2021

=======================================================

Prefix array is a very vital tool in competitive programming. This helps to minimize the repeated calculation done in an array and thus reduces the time complexity of your program.

What is prefix array ?
Suppose you are given an array, A = { 2 , 6 , 5 , 8 , 7 , 1 }. Let us define a new array PA[ ], size of which is same as the size of array A. The element at the ith index of the array PA will contain the sum of all the elements from A[0] to A[i], i.e :

     PA[0] = A[0]
     PA[1] = A[0] + A[1]
     PA[2] = A[0] + A[1] + A[2]
         .
         .
         .
     PA[i] = A[0] + A[1] + A[2] + ........ + A[i]
         .
         .
         .
     PA[N-1] = A[0] + A[1] + A[2] + ......... + A[N-1]

So, the prefix array of the given array A will be , PA [ ] = { 2 , 8 , 13 , 21 , 28 , 29 }

Creating Prefix array
Prefix array can easily be constructed by travelling the array A once. This can be done by using the formula :
    PA[ i ] = PA [ i − 1 ] + A[i]
Here i varies from 1 to N − 1. PA[ 0 ] is initialize to A[ 0 ] before the loop starts.

Advantage
Suppose you are said to calculate the sum of first K elements of the array A. It is fine if you have to do the given task once, but if you are asked repeatedly to find the sum of first K elements of the array A (note : K may vary from 0 to N-1 ) then it may take lot of time. But if we construct prefix array of the given array then we can answer the query in O( 1 ) time by just printing PA[ K − 1 ].

Now suppose you are asked to calculate the sum of elements of array A from index L to index R ( L ≤ R) i.e, you have to calculate the summation of the series A[ L ] + A[ L + 1 ] + ........ + A [ R ], if you are asked to calculate once then it is fine but if you have to repeatedly calculate then prefix array would be a better option. We can answer the query in O( 1 ) time by just printing, PA[ R ] − PA[ L − 1 ].
Explanation
     PA[ R ] = A[ 0 ] + A [ 1 ] + A[ 2 ] + ....... + A[ L-1 ] + A[ L ] + ........ + A[ R ] (note L ≤ R)
     PA[ L-1 ] = A[ 0 ] + A [ 1 ] + A[ 2 ] + ....... + A[ L − 1 ]

substracting PA[ R ] by PA[ L − 1 ] we get:

     PA[ R ] − PA[ L − 1] = A[ L ] + ........ + A[ R ]

