
## Linked Lists:
A Linked List is a sequence of Nodes that are connected/linked to each other. The most defining feature of a Linked List is that each `Node` references the next Node in the link.

There are two types of Linked List - Singly and Doubly.

* `Linked List` - A data structure that contains nodes that links/points to the `next` node in the list.
* `Singly` - Singly refers to the number of references the node has. A Singly linked list means that there is only one reference, and the reference points to the `Next` node in a linked list.
* `Doubly` - Doubly refers to there being two (double) references within the node. A Doubly linked list means that there is a reference to both the `Next` and `Previous` node.
* `Node` - Nodes are the individual items/links that live in a linked list. Each node contains the data for each link.
* `Next` - Each node contains a property called `Next`. This property contains the reference to the next node.
* `Head` - The Head is a reference type of type `Node` to the first node in a linked list.
* `Current` - The Current reference is a reference type of type `Node` that is currently being looked at. This node is traditionally used when traversing through a full linked list. 
When traversing, you typically reset the current to the head to guarantee you are starting from the beginning of the linked list.


## create a linked list

* First, we find the head node of the linked list.

* Next, we’ll make our new node, and set its pointer to the current first node of the list.

* Lastly, we rearrange our head node’s pointer to point at our new node.

# Big O Notation

- is a way of evaluating the performance of an algorithm.
- Big O Notation : takes into account: the speed and efficiency with which something functions when its input grows to be any (crazy big!) size.
- O (referred to as just “O” or sometimes as “order”), and a variable n, where n is the size of the input
- O(1) function : takes constant time, which is to say that it doesn’t matter how many elements we have, or how huge our input is: it’ll always take the same amount of time and memory to run our algorithm.
- O(n) : function is linear, which means that as our input grows (from ten numbers, to ten thousand, to ten million), the space and time that we need to run that algorithm grows linearly.
- O(n²) function : which clearly takes exponentially more time and memory the more elements that you have. It’s pretty safe to say that we want to avoid O(n²) algorithms, just from looking at that crazy red line!



#### Traversal

When traversing a linked list, you are not able to use a foreach or for loop. We depend on the `Next` value in each node to guide us where the next reference is pointing.
The `Next` property is exceptionally important because it will lead us where the next node is and allow us to extract the data appropriately.

The best way to approach a traversal is through the use of a `while()` loop. This allows us to continually check that the `Next` node in the list is not null. 
If we accidentally end up trying to traverse on a node that is null, a `NullReferenceException` gets thrown and our program will crash/end.

When traversing through a linked list, the `Current` node is the most helpful. 
The `Current` will tell us where exactly in the linked list we are and will allow us to move/traverse forward until we hit the end.


## Memory management

- The biggest differentiator between arrays and linked lists is the way that they use memory in our machines. Those of us who work with dynamically typed languages like Ruby, JavaScript, or Python don’t have to think about how much memory an array uses when we write our code on a day to day basis because there are several layers of abstraction that end up with us not having to worry about memory allocation at all.





# Linear data structures

If we really want to understand the basics of linked lists, it’s important that we talk about what type of data structure they are.
One characteristic of linked lists is that they are linear data structures, which means that there is a sequence and an order to how they are constructed and traversed. We can think of a linear data structure like a game of hopscotch: in order to get to the end of the list, we have to go through all of the items in the list in order, or sequentially. Linear structures, however, are the opposite of non-linear structures. In non-linear data structures, items don’t have to be arranged in order, which means that we could traverse the data structure non-sequentially.
