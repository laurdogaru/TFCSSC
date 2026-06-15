# TFCSSC - Project Overview

## Description
The TFCSSC repository contains an implementation of two classic data structures: a Trie and a Treap, both written in C. These data structures are fundamental in computer science for efficient data storage and retrieval, with specific applications in text processing and maintaining balanced trees in dynamic datasets, respectively.

## Main Components
1. **Trie Implementation ()**:
   - A Trie, or prefix tree, is designed for storing strings efficiently. It allows for operations such as insertion of strings, deletion of strings, and querying the number of occurrences of a string.
   - The  structure consists of:
     - : Tracks how many times a string is stored.
     - : Number of children (sub-tries).
     - : Array of pointers for the 26 lowercase alphabet characters.

   - Key Functions:
     - : Initializes a new Trie node.
     - : Inserts a string into the Trie and updates the relevant counts.
     - : Removes a string from the Trie while managing node memory and counts.
     - : Cleans up the allocated memory for the Trie.

2. **Treap Implementation ()**:
   - A Treap is a combined structure that maintains both a binary search tree (BST) property and a heap property. Each node has a key and a priority used for balancing.
   - The  structure consists of:
     - : The value stored.
     - : A randomly assigned value for heap balancing.
     - Child pointers: , , and .

   - Key Functions:
     - : Initializes a new Treap node.
     - : Inserts a node while maintaining both BST and heap properties through rotations.
     - : Removes a node and rebalances the tree as needed.
     - : Cleans up the allocated memory for the Treap.
     - : Ensures that the Treap maintains its heap property after insertion or deletion.

## Tech Stack
- **Programming Language**: C
- **Memory Management**: Manual memory allocation and deallocation using  and .
- **Data Structures**: Custom implementations of Trie and Treap algorithms.

## Usage Example
Each component has a  function demonstrating basic usage, such as inserting and deleting elements, and displaying the tree structure. Users can expand upon these demonstrations to implement more complex scenarios tailored to specific applications.

This repository serves as a foundational study and reference implementation of these data structures, suitable for engineers and developers looking to deepen their understanding of algorithmic design and data structure efficiency in C.
