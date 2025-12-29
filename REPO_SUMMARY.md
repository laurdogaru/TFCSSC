## TFCSSC Repository Overview

### Project Description
The TFCSSC repository contains an implementation of two fundamental data structures: a **Trie** and a **Treap**. These data structures are commonly used in computer science for efficient storage and retrieval of data.

1. **Trie**:
   - A Trie, also known as a prefix tree, is used for storing strings in a way that allows for efficient retrieval. This makes it particularly useful for applications such as autocomplete systems and spell checkers. 
   - This implementation includes functionalities to initialize the Trie, insert strings, delete strings, and free the allocated memory.

2. **Treap**:
   - A Treap is a randomized binary search tree that maintains the properties of both a binary search tree (BST) and a heap: it is ordered based on keys (BST property) and has a randomized priority for balancing. 
   - This implementation allows for inserting and deleting nodes while maintaining the balance of the tree and supports various traversal methods (in-order, pre-order, and post-order).

### Main Components
- **Trie** ():
  - Data structure with nodes storing counts of strings and child pointers for each character ('a' to 'z').
  - Functions:
    - : Initializes a new Trie node.
    - : Inserts a string into the Trie.
    - : Deletes a string from the Trie.
    - : Frees all allocated memory in the Trie.

- **Treap** ():
  - A node structure containing a key, priority, and pointers to left and right children.
  - Functions:
    - : Initializes a new Treap node.
    - : Inserts a key with a specific priority while balancing the Treap.
    - : Deletes a specified key from the Treap while maintaining the balance.
    - : Frees all allocated memory in the Treap.
    - Traversal functions to display the nodes in the desired order (in-order, pre-order, post-order).

### Tech Stack
- **Language**: C
- **Memory Management**: Manual memory allocation and deallocation using  and                total        used        free      shared  buff/cache   available
Mem:        16379468      947688     8996336       45324     6835444    15431780
Swap:        4194300           0     4194300.
- **Data Structures**: 
  - Trie for string manipulation.
  - Treap for balanced binary search tree operations.

### Potential Applications
The data structures implemented in this repository can be used in various applications, such as:
- Autocomplete features in search engines.
- Dictionary and spell-check functionalities.
- Managing and querying large datasets efficiently.

This repository serves as a foundation for engineers interested in understanding and utilizing these data structures in their software solutions.
