
# DSA Q&A

* #### Why you should use linked list over array?
* The size of an array must be known in advance.
* Increasing the size of an array is time consuming.
* Inserting an element in the array needs shifting of all its predecessors.
On the otherhand,
* Linked list allocates memory dynamically. 
* Inserting an element doesn't demand a lot of process like array.
There are some disadvantages also,
* In linked list nodes occupy more memory than array. 
* Traversal is not easy in a linked list. Can access an element randomly. For example, if we need to access the 3rd node then we need to traverse all the nodes before it.

#### Why you should use array over linked list?

#### Usage of Stack?
* Strng reversal.
* Undo/redo.
* Graph can be traversed using various algorithms like BFS, DFS, both of which uses a stack data structure to keep track of the visited nodes. Stack is used to keep track of the nodes that are explored. When the algorithm visits a new node it pushes that node in the stack so that while backtracking it can pop the last node off and continue exploring from the previous node.  
#### How BFS uses stack data structure?
#### How DFS uses queue data structure?
