# Linked List in CPP

# Aim:

To implement a Singly Linked List in C++ and demonstrate node creation, linking, and traversal.

# Tools Used:

IDE, C++ compiler, Node class, pointers.

# Theory:

A Linked List is a dynamic linear data structure where each node contains:

Data – the value stored in the node.

Pointer – reference to the next node.

Singly Linked List: Each node points only to the next node.
Key Features:

Dynamic memory allocation.

Efficient insertion/deletion.

Sequential access using pointers.

Node Structure in C++:

class Node {
    public:
        int val;       // stores data
        Node* next;    // points to next node
};

# Program 1: Single Node Creation

Purpose: Demonstrate creation of a single node.

 ALGORITHM: 

1> Start <br>
2> Define Node class with val and next. <br>
3> Instantiate a node with a specific value. <br>
4> Display node value and pointer. <br>
5> End

- Structure:

Node contains val and next.

next is initialized to NULL for a single node.

# Program 2: Linked List Traversal

Purpose: Demonstrate creation, linking, and traversal of multiple nodes.

 ALGORITHM:

1> Start <br>
2> Define Node class with val and next. <br>
3> Instantiate multiple nodes with values. <br>
4> Link nodes using next pointers.<br>
5> Traverse the list from head node using a temporary pointer. <br>
6> Print each node’s value. <br>
7> End

- Structure:

Multiple Node objects linked via next pointers.

Traversal uses a temporary pointer starting from the head node.

# Conclusion:

The experiment demonstrates Singly Linked List concepts: creating nodes, linking them, and traversing the list. It emphasizes the use of pointers for dynamic memory management and sequential access, forming the foundation for advanced data structures like stacks, queues, and graphs.
