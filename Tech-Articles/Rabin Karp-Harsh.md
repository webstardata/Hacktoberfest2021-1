
=======================================================

Article Title: Rabin Karp Algorithm
Author Name: Harsh Kumar 
Author Profile: https://github.com/Harshk408
Date: 22-10-2021

=======================================================

## Rabin Karp Algorithm
* Rabin karp algorithm is a pattern searching algorithm.

### Logic
* In this algo we check for every window of length M(pattern length) and slide the M length window on given text.
* we first calculate hash value of pattern and hash value of M - length text.

* for getting Hash value , we create a hash Function which gives us hash value for a given string.
* Now one by one we slide the pattern on text and 
   * if (Hahs_value_pattern == Hash_value_textWindow) , then we check every character of pattern and cuurent text and if they all match we retuen `True`.
   
   * if(patterns not match then compute Hash value for Hash_value_text[i+1] using Hash_value_text[i]).

* after loop termination we are sure that pattern is not present in the given text. So return `False`.

## Limitations of Rabin-Karp Algorithm
> Spurious Hit
* When the hash value of the pattern matches with the hash value of a window of the text but the window is not the actual pattern then it is called a spurious hit.

* Spurious hit increases the time complexity of the algorithm. In order to minimize spurious hit, we use modulus. It greatly reduces the spurious hit.

## Uses Of Rabin-Karp Algorithm 
* For pattern searching.
* For searching string in a large text.
