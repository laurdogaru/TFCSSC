### TFCSSC Repository Overview

The TFCSSC repository presents an implementation of two distinct data structures: a Trie and a Treap. The primary objective of the project is to explore and demonstrate the functionalities and operations of these data structures through C programming, which are fundamental in efficient data retrieval and manipulation scenarios.

#### Project Components

1. **Trie (File: )**
   - **Description**: A Trie, also known as a prefix tree, is utilized for dynamic set or associative array data structures where the keys are usually strings. The Trie provides efficient retrieval and storage of strings.
   - **Main Functions**:
     - ****: Initializes a new Trie node with zero counts and no children.
     - ****: Adds a string to the Trie. If a string already exists, it increments the count for that string.
     - ****: Removes a string from the Trie, decrementing the count and correctly freeing memory if required.
     - ****: Recursively frees all nodes in the Trie to prevent memory leaks.
     
2. **Treap (File: )**
   - **Description**: A Treap is a randomized binary search tree that maintains heap properties based on priority of nodes. This structure combines properties of a binary search tree and a heap, providing efficient insertions, deletions, and searches.
   - **Main Functions**:
     - ****: Initializes a new Treap node with a specified key and priority.
     - ** and **: Functions to balance the Treap through rotations, ensuring that it maintains both BST and heap properties.
     - ****: Inserts a new node, balances the tree as necessary using rotations.
     - ****: Removes a node from the Treap and ensures that it continues to uphold its structural properties.
     - **Traversal Functions**: , , and  are provided for different tree traversal methods.

#### Tech Stack
- **Programming Language**: C
- **Data Structures**: Trie (for string storage and retrieval) and Treap (for key-value pairs with efficient balancing through priority).

This repository functions as both an educational tool and a base for further enhancements, featuring implementations that illustrate key operations of these essential data structures frequently employed in various applications that require effective management of sets of strings and key-value pairs.
