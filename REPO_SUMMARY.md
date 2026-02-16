# TFCSSC Repository Summary

## Project Overview
The TFCSSC repository contains implementations of two fundamental data structures: a Trie and a Treap. The Trie is used primarily for storing strings and facilitating fast retrieval, while the Treap is a combination of a binary search tree and a heap, balancing itself on the priorities of its elements. These data structures are essential for optimizing search operations in various applications, such as dictionaries, databases, and more.

## Main Components
1. **Trie Implementation ()**
   - **Data Structure**:
     - A  struct consisting of an array of child nodes (one for each letter of the English alphabet), a count of strings that pass through that node, and a count of how many children it has (nrfii).
   - **Key Functions**:
     - : Initializes a new Trie node.
     - : Inserts a string into the Trie and updates counts.
     - : Removes a string from the Trie and manages child nodes.
     - : Recursively frees allocated memory for the Trie.
   - **Main Method**: Demonstrates inserting and deleting a string.

2. **Treap Implementation ()**
   - **Data Structure**:
     - A  struct representing each element in the Treap, which contains a , , and pointers to its left and right children as well as its parent.
   - **Key Functions**:
     - : Initializes a new node.
     - , : Perform rotations to maintain the Treap properties.
     - : Ensures the Treap maintains its heap property based on node priorities.
     - : Inserts a new key-value pair into the Treap while maintaining the binary search tree and heap properties.
     - : Removes a node and ensures the Treap remains balanced.
     - : Recursively frees allocated memory for the Treap.
     - , , : Methods for traversing the Treap in different orders.
   - **Main Method**: Demonstrates insertion and deletion in a Treap while providing an example of in-order traversal.

## Tech Stack
- **Programming Language**: C
- **Memory Management**: Dynamic memory management using  and                total        used        free      shared  buff/cache   available
Mem:        16378480      852700    13920068       45024     1958100    15525780
Swap:        3145724           0     3145724 for node creation and destruction.
- **Data Structures**: Implementations of Trie and Treap algorithms.

This repository serves as a foundational resource for engineers working on data structures in C and highlights efficient memory usage and algorithmic approaches to managing collections of strings and keys.
