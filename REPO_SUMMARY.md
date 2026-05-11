## Summary of the Repository

This repository contains an implementation of two fundamental data structures in C: a Trie and a Treap. These structures are essential for efficiently managing dynamic sets of strings and integers respectively.

### Project Overview
- **Trie**: A Trie, or prefix tree, is designed to store strings in a way that optimizes prefixes and enables fast retrieval, insertion, and deletion of words.
- **Treap**: A Treap is a hybrid data structure that combines properties of binary search trees and heaps. It supports efficient insertion, deletion, and lookup while maintaining a heap property based on priority.

### Main Components
1. **Trie Implementation ()**:
   - **Data Structure**: A  struct which includes a count of occurrences and an array of child pointers for 26 lowercase letters.
   - **Functions**:
     - : Initializes a new Trie node.
     - : Inserts a string into the Trie, incrementing counts as necessary.
     - : Removes a string from the Trie, managing node memory correctly.
     - : Recursively frees all nodes in the Trie.

2. **Treap Implementation ()**:
   - **Data Structure**: A  struct with a key, priority, and pointers to left, right, and parent nodes.
   - **Functions**:
     - : Allocates and initializes a new node with its key and priority.
     - : Inserts a key with a given priority into the Treap, applying rotations to maintain heap order.
     - : Deletes a specified key while maintaining structure integrity and balancing.
     - : Recursively frees all nodes in the Treap.
     - Traversal functions (, , ) to visit nodes in different orders.

### Tech Stack
- **Language**: C
- **Memory Management**: Uses dynamic memory allocation via  and                total        used        free      shared  buff/cache   available
Mem:        16373468      950812    13310564       45312     2481576    15422656
Swap:        3145724           0     3145724.
- **Data Structures**: The repository employs pointers and structs for explicit management of data structures.

Overall, this project provides foundational implementations that demonstrate the usage of Trie and Treap for string and integer data management, important concepts in computer science.
