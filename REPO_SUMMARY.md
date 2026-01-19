## Project Overview: TFCSSC

The TFCSSC repository implements two fundamental data structures, **Trie** and **Treap**, in C. These structures are essential for different types of applications in computer science, such as text processing, search operations, and priority-based data organization.

### Key Components

1. **Trie Implementation ()**:
   - A Trie (pronounced “try”) is a tree-like data structure that is used to store a dynamic set of strings, where the keys are usually strings.
   - **Main Functions**:
     - : Initializes a new Trie node.
     - : Inserts a string into the Trie.
     - : Removes a string from the Trie.
     - : Frees the memory allocated for the Trie.

2. **Treap Implementation ()**:
   - A Treap is a combination of a binary search tree and a heap, where each node maintains both a key and a priority.
   - **Main Functions**:
     - : Initializes a new node for the Treap.
     -  and : Handle rotations to maintain the heap property.
     - : Inserts a new key-priority pair into the Treap.
     - : Removes a key from the Treap while maintaining properties.
     - : Frees the nodes in the Treap.
     - Various traversal functions (, , ) to print the nodes in different orders.

### Technical Stack

- **Language**: C
- **Memory Management**: Uses dynamic memory allocation with  and                total        used        free      shared  buff/cache   available
Mem:        16379468      862872     9704392       43600     6210476    15516596
Swap:        4194300           0     4194300 for node creation and deletion.
- **Data Structures**: Implementations of Trie and Treap which leverage array-based child node references and dynamic pointers to manage node relationships.

### Summary

The **TFCSSC** repository serves as an educational tool for understanding the implementation of Trie and Treap data structures in C. It provides basic functionalities for insertion and deletion while maintaining the core properties of each data structure. This project can help engineers and computer science students to grasp fundamental concepts of data organization and retrieval techniques, facilitating further exploration into more complex algorithms and structures.
