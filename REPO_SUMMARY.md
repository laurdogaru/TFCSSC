## Summary of Repository: TFCSSC

### Project Overview
The TFCSSC repository implements two types of data structures: a Trie and a Treap, which are often used in various applications involving efficient data retrieval and management. The Trie is utilized for prefix-based string searches, while the Treap combines features of both binary search trees and heaps for efficient key insertions and deletions with priority management.

### Main Components
1. **Trie ()**:
   - Structure: The  structure consists of a count for storing how many times a particular string is present and an array of child nodes that represent subsequent characters.
   - Key Functions:
     - ****: Initializes a new Trie node.
     - ****: Inserts a string into the Trie, incrementing the count.
     - ****: Deletes a string from the Trie, decrementing the count as appropriate.
     - ****: Frees memory associated with the Trie.

2. **Treap ()**:
   - Structure: A  structure defines the elements of the Treap, including a key, a priority, and pointers to left and right children, as well as a parent.
   - Key Functions:
     - ****: Initializes a new node with a value and a priority.
     - ** / **: Balances the tree through rotations based on priorities.
     - ****: Inserts a node and rebalances the Treap.
     - ****: Deletes a node and maintains balance.
     - ****: Frees memory for the entire tree.
     - **Traversal Functions**: Includes in-order, pre-order, and post-order traversal functions to access tree data.

### Tech Stack
The project is written in C, utilizing fundamental libraries such as  for input/output and  for memory management. It does not rely on any external dependencies, ensuring that it can be easily compiled and run in any standard C environment.

### Usage
The provided  functions in both  and  demonstrate how to utilize the data structures. Users can initialize a data structure, perform insertions and deletions, and traverse to view stored values.

This repository provides robust implementations of a Trie and a Treap suitable for educational purposes and as a building block for more complex data applications.
