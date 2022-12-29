# Linked Lists

## WHY

Linked lists are used to store sequences of data when the size of the data is not known in advance or when the data needs to be frequently modified, as they can be resized easily and efficiently.

## WHAT

A linked list is a linear data structure in which each element is a seperate object, called a node, and each node has a reference (pointer) to the next node in the list. The last node in the list has a reference to null, indicating the end of the list.

## HOW

To create a linked list, you need to define a class for the nodes, which should contain at least the data and the reference to the next node. You can then create a linked list by creating a series of nodes and linking them together using the references. To insert or remove a node from a linked list, you need to update the references of the surrounding nodes to point to the new node or to skip the removed node. Linked lists can be traversed by starting at the first node and following the references until the end of the list is reached.
