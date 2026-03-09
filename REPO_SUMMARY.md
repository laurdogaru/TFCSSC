## Repository Summary: TFCSSC

### Overview
The TFCSSC repository contains implementations of two data structures—Trie and Treap—written in C. These data structures are fundamental in computer science and are often utilized for efficient searching, inserting, and deleting of elements, making them useful in various applications such as dictionary implementations and priority queue management.

### Main Components

1. **Trie Implementation ()**:
   - A Trie (pronounced try), is a tree-like data structure that stores strings in a way that allows for efficient prefix-based searching.
   - Key Functions:
     - : Initializes a new Trie node.
     - : Inserts a string into the Trie.
     - : Deletes a string from the Trie, properly managing memory.
     - : Frees all allocated memory in the Trie.
     - Main function demonstrates the usage of insert and delete operations.

2. **Treap Implementation ()**:
   - A Treap is a hybrid data structure that combines properties of a binary search tree and a heap, making it efficient for random access and maintaining a prioritized structure.
   - Key Functions:
     - : Initializes a new Treap node with a given priority.
     -  and : Perform the necessary rotations to maintain the Treap properties.
     - : Balances the Treap by rotating nodes based on the priority.
     - : Inserts a new value with priority into the Treap.
     - : Deletes a node from the Treap while ensuring structural integrity.
     - : Frees all allocated memory in the Treap.
     - Traversal functions (, , and ) for displaying the Treap's elements.
     - Main function demonstrates inserting and deleting elements in a Treap and outputs the in-order traversal of the tree.

### Tech Stack
- **Programming Language**: C
- **Data Structures**: 
  - Trie for string storage and manipulation.
  - Treap for combined ordered and priority-based operations.

This repository serves as a practical demonstration of fundamental data structures, focusing on their implementation and manipulative operations in C programming. It provides engineers with insight into applying theoretical concepts to practical coding scenarios.
