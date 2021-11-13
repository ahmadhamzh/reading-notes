# Stack & queue 

## Stack

A stack normally is a structure of sequential and ordered elements and it’s based on the principle of last in first out (LIFO).

![LIFO](https://d585tldpucybw.cloudfront.net/sfimages/default-source/blogs/2020/2020-11/lifo.png)

### **A stack data structure has two fundamental operations :**

![stack visual](https://codefellows.github.io/common_curriculum/data_structures_and_algorithms/Code_401/class-10/resources/images/stack1.PNG)


### **A stack data structure has four fundamental operations:**


 **1- 'Push' This operation is responsible for inserting or pushing a new element to the stack.**

Pushing a Node onto a stack will always be an O(1) operation. This is because it takes the same amount of time no matter how many Nodes (n) you have in the stack.

![push Stack](https://codefellows.github.io/common_curriculum/data_structures_and_algorithms/Code_401/class-10/resources/images/pushStack3.PNG)

> ALOGORITHM push(value)//

> INPUT <-- value to add, wrapped in Node internally//

> OUTPUT <-- none

>   node = new Node(value)

>   node.next <-- Top

>   top <-- Node


 **2- 'POP' This operation is responsible for removing the most recent element from the stack. O(1)**

 ![pop](https://codefellows.github.io/common_curriculum/data_structures_and_algorithms/Code_401/class-10/resources/images/popStack4.PNG)

>   node = new Node(value)

>   temp <-- Top

>   top <-- Top.next
 
>   temp.next <-- null

 **3- 'Peek' This operation is responsible for given the value of the Top.**

 > return top.value

 **4- 'is empty' This operation is responsible for checking if the Stackis empty or not.**

 > return top.next === null

## Queue 

A Queue is a linear structure which follows a particular order in which the operations are performed. The order is First In First Out (FIFO).

![queue](https://media.geeksforgeeks.org/wp-content/cdn-uploads/gq/2014/02/Queue.png)

### **A Queue data structure has four fundamental operations:**

**1- 'Enqueue' When you add new node to a queue, you use the enqueue action and the node add to the rear . This is done with an O(1) operation**

 >ALGORITHM enqueue(value)//

 > INPUT <-- value to add to queue (will be wrapped in Node internally)//
 
 > OUTPUT <-- none

 >  node = new Node(value)

 >  rear.next <-- node

>   rear <-- node
 ![enQueue](https://codefellows.github.io/common_curriculum/data_structures_and_algorithms/Code_401/class-10/resources/images/Enqueue3.PNG)


**2- 'Dequeue' When you remove a node from a queue, you use the Dequeue action and the node removed from the front. This is done with an O(1) operation**

>ALGORITHM dequeue()//

> INPUT <-- none//

> OUTPUT <-- value of the removed Node//

>   Node temp <-- front

>   front <-- front.next

>   temp.next <-- null

![Dequeue](https://codefellows.github.io/common_curriculum/data_structures_and_algorithms/Code_401/class-10/resources/images/Dequeue3.PNG)


 **3- 'Peek' This operation is responsible for given the value of the Top.**

 > return front.value

 **4- 'is empty' This operation is responsible for checking if the Stackis empty or not.**

return front.value === null 
 


 



