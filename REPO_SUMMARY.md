## Repository Overview: TFCSSC

### Project Purpose
The TFCSSC repository implements two foundational data structures in C: a Trie and a Treap. Both structures are designed for efficient operations related to searching, inserting, and deleting elements, making them ideal for various applications in software development and data management.

### Main Components

1. **Trie (trie.c)**:
    - A Trie is a tree-like data structure that stores a dynamic set of strings, enabling efficient retrieval and prefix-based searching.
    - **Key Functions**:
        - : Initializes a new Trie node.
        - : Inserts a string into the Trie, updating the count of occurrences.
        - : Removes a string from the Trie, adjusting counts and freeing nodes when necessary.
        - : Recursively frees all nodes in the Trie.
    - **Structure**:
        - Each node contains an array of children (for each alphabet letter) and counters to keep track of word occurrences.

2. **Treap (treap.c)**:
    - A Treap is a randomized binary search tree that maintains the properties of both a binary search tree and a heap, allowing for quick insertion, deletion, and search operations.
    - **Key Functions**:
        - : Creates a new node with a value and priority.
        - : Adds a node to the Treap, balancing the tree as necessary based on priorities.
        - : Removes a node while maintaining tree balance.
        - : Frees memory allocated for the Treap nodes.
        - Traversal functions: , , and  for various tree traversal methods.
    - **Structure**:
        - Each node includes pointers to its left and right children, a parent pointer, a key, and a priority value which helps maintain the heap property.

### Tech Stack
- **Programming Language**: C
- **Libraries Used**: Standard libraries for memory management () and standard input/output functions ().

### Usage Flow
- The project's main functionality is demonstrated via two  functions located in  and , showcasing basic usage of each data structure – inserting, deleting, and printing values or counts.

Overall, the TFCSSC repository serves as a practical resource for engineers looking to understand and implement Trie and Treap data structures, with examples of insertion and deletion operations clearly laid out.
