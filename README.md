# Linked List in CPP

# Aim:

To study and implement a Singly Linked List in C++ for creating nodes, linking them, and traversing the list.

# Tools Used:

IDE, C++ compiler, Node class, pointers.

# Theory:

A Linked List is a linear data structure where each element (called a node) contains:

Data – the value stored in the node.

Pointer – a reference to the next node in the sequence.

Unlike arrays, linked lists do not require contiguous memory and can grow or shrink dynamically.

Singly Linked List: Each node points only to the next node.

Doubly Linked List: Each node points to both previous and next nodes.

Circular Linked List: Last node points back to the first node.

🔹 Key Features of a Singly Linked List:

Dynamic memory allocation.

Efficient insertion and deletion at any position.

Sequential access via pointers.

🔹 Node Structure in C++:

class Node {
    public:
        int val;   // stores data
        Node* next; // points to the next node
};

# Program 1: Creating a Single Node

This program demonstrates how to create a single node and display its value.

ALGORITHM:
1> Start

2> Create a Node class with val and next.

3> Instantiate a node with a specific value (e.g., 20).

4> Display the value and next pointer of the node.

5> End

# Program 2: Creating and Traversing a Linked List

This program demonstrates how to create multiple nodes, link them, and traverse the linked list.

ALGORITHM:
1> Start

2> Create a Node class with val and next.

3> Instantiate multiple nodes with values (e.g., 10, 20, 30).

4> Link the nodes by assigning next pointers.

5> Use a temporary pointer to traverse the list from the head node.

6> Print the value of each node during traversal.

7> End

# Conclusion:

The experiment demonstrates the creation and traversal of a Singly Linked List in C++. Nodes can be dynamically created and linked using pointers. Traversal using a temporary pointer allows access to each element sequentially. This forms the foundation for advanced data structures such as stacks, queues, and graphs.
