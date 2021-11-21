# trees

### Sample Tree

![Sample Tree](https://codefellows.github.io/common_curriculum/data_structures_and_algorithms/Code_401/class-15/resources/images/BinaryTree1.PNG)

### Traversals

An important aspect of trees is how to traverse them. Traversing a tree allows us to search for a node, print out the contents of a tree, and much more.

There are two categories of traversals when it comes to trees:
  
  * Depth First 
   Depth first traversal is where we prioritize going through the depth (height) of the tree first. There are multiple ways to carry out depth first traversal, and each method changes the order in which we search/print the root
    
    * Pre-order: root >> left >> right
    * In-order: left >> root >> right
    * Post-order: left >> right >> root

 * Breadth First 
  
    Breadth first traversal iterates through the tree by going through each level of the tree node-by-node.

...

     ALGORITHM breadthFirst(root)
     //INPUT  <-- root node
    // OUTPUT <-- front node of queue to console

     Queue breadth <-- new Queue()
     breadth.enqueue(root)

     while breadth.peek()
     node front = breadth.dequeue()
     OUTPUT <-- front.value

       if front.left is not NULL
         breadth.enqueue(front.left)

       if front.right is not NULL
         breadth.enqueue(front.right)
...


### Binary Tree K-ary Trees

There is no specific sorting order for a binary tree. Nodes can be added into a binary tree wherever space allows. Here is what a binary tree looks like:

![binary tree](https://codefellows.github.io/common_curriculum/data_structures_and_algorithms/Code_401/class-15/resources/images/BinaryTree2.PNG)

### K-ary Trees

If Nodes are able have more than 2 child nodes, we call the tree that contains them a K-ary Tree. In this type of tree we use K to refer to the maximum number of children that each Node is able to have.

**Breadth First Traversal**

Traversing a K-ary tree requires a similar approach to the breadth first traversal. We are still pushing nodes into a queue, but we are now moving down a list of children of length k, instead of checking for the presence of a left and a right child.

![k-ary trees](https://codefellows.github.io/common_curriculum/data_structures_and_algorithms/Code_401/class-15/resources/images/KaryTree1.png)

ALGORITHM breadthFirst(root)
// INPUT  <-- root node
// OUTPUT <-- front node of queue to console

    Queue breadth <-- new Queue()
     breadth.enqueue(root)

    while breadth.peek()
      node front = breadth.dequeue()
       OUTPUT <-- front.value

    for child in front.children
        breadth.enqueue(child)


