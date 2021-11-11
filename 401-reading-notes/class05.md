# linked list 

A linked list is a linear data structure, in which the elements are not stored at contiguous memory locations. The elements in a linked list are linked using pointers as shown in the below image:


In simple words, a linked list consists of nodes where each node contains a data field and a reference(link) to the next node in the list.

## Linked List vs Array

Arrays store elements in contiguous memory locations, resulting in easily calculable addresses for the elements stored and this allows faster access to an element at a specific index. Linked lists are less rigid in their storage structure and elements are usually not stored in contiguous locations, hence they need to be stored with additional tags giving a reference to the next element. This difference in the data storage scheme decides which data structure would be more suitable for a given situation. 

![array](https://media.geeksforgeeks.org/wp-content/uploads/Arrays-1.png)

![linked list](https://media.geeksforgeeks.org/wp-content/cdn-uploads/gq/2013/03/Linkedlist.png)

## Inserting a node

In this post, methods to insert a new node in linked list are discussed. A node can be added in three ways 

**1) At the front of the linked list**
The new node is always added before the head of the given Linked List. And newly added node becomes the new head of the Linked List.

![insert at first](https://media.geeksforgeeks.org/wp-content/cdn-uploads/gq/2013/03/Linkedlist_insert_at_start.png)

**2) After a given node.**

We are given a pointer to a node, and the new node is inserted after the given node.

![after given nide](https://media.geeksforgeeks.org/wp-content/cdn-uploads/gq/2013/03/Linkedlist_insert_middle.png)


**3) At the end of the linked list.**

The new node is always added after the last node of the given Linked List

![add at last](https://media.geeksforgeeks.org/wp-content/cdn-uploads/gq/2013/03/Linkedlist_insert_last.png)


