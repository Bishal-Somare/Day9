# Day9
This implementation provides a basic circular doubly linked list (CDLL) with functionality for:

Adding elements to the list.
Displaying the elements in the list.
Deleting a specific element by its value.
Key Features
Circular linkage ensures that the last node connects to the first node, creating a loop.
Doubly linked structure allows traversal in both forward and backward directions.
Classes and Methods
Node
A helper class representing a single node in the list.

data: The value stored in the node.
next: Pointer to the next node.
prev: Pointer to the previous node.
CircularDoublyLinkedList
The main class for the CDLL.

append(data): Adds a node with the given data to the end of the list.
display(): Prints the elements of the list in order.
delete(key): Removes the first node with the specified value.
