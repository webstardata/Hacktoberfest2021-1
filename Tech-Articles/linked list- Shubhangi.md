
=======================================================

Article Title: Linked List 
Author Name: Shubhangi Biltoria
Author Profile: https://github.com/shubhangibiltoria
Date: 18-10-21

=======================================================

<Write-Your-Complete-Tech-Article-Here>

Linked list is one of the most important data structures. We often face situations, where the data is dynamic in nature and number of data can’t be predicted or the number of data keeps changing during program execution. Linked lists are very useful in this type of situations.

The implementation of a linked list in C is done using pointers. You can go through the pointers chapter if you don’t have a strong grip over it. You can also practice a good number of questions from practice section.

A linked list is made up of many nodes which are connected in nature. Every node is mainly divided into two parts, one part holds the data and the other part is connected to a different node. In C, we achieve this functionality by using structures and pointers. Each structure represents a node having some data and also a pointer to another structure of the same kind. This pointer holds the address of the next node and creates the link between two nodes The first data member of the structure (named node) is an integer to hold an integer and the second data member is the pointer to a node (same structure). This means that the second data member holds the address of the next node and in this way, every node is connected
  So, if we have access to the first node then we can access any node of the linked list. For example, if ‘a’ is a node then a->next is the node next to the ‘a’ (the pointer storing the address of the next node is named ‘next’).

One thing you should notice here is that we can easily access the next node but there is no way of accessing the previous node and this is the limitation of singly linked list.
