## Project Summary: TFCSSC

### Overview
The TFCSSC repository implements two fundamental data structures in C: a **Trie** and a **Treap**. 

- **Trie**: A tree-like data structure that efficiently stores a dynamic set of strings, supporting operations for insertion, deletion, and counting occurrences.
- **Treap**: A combination of a binary search tree and a heap, ensuring balanced operations through randomized priorities. It supports insertion, deletion, and traversal operations while maintaining the binary search tree properties.

### Main Components
1. **Trie Implementation ()**:
   - **Data Structure**:  struct representing nodes in the trie, with a count for the number of words and a child array for the next character in the alphabet (for lowercase letters only).
   - **Functions**:
     - : Initializes a new trie node.
     - : Inserts a string into the trie.
     - : Deletes a string from the trie and manages memory correctly.
     - : Recursively frees allocated memory for the trie.

2. **Treap Implementation ()**:
   - **Data Structure**:  struct representing each node in the treap, with a key, priority, and pointers to child nodes.
   - **Functions**:
     - : Initializes a new treap node.
     -  and : Implements rotation methods to maintain the heap property of the treap.
     - : Inserts a new node into the treap while balancing it.
     - : Deletes a node from the treap and rebalances.
     - : Recursively frees memory for the treap.
     - , , and : Provides methods for tree traversal.

### Tech Stack
- **Programming Language**: C
- **Memory Management**: Dynamic memory allocation is extensively used with  for creating nodes and  for deallocating them.

### Usage
The  function in both implementations showcases the functionality of the Trie and Treap. It includes example operations such as inserting, deleting, and traversing, demonstrating how each data structure can be utilized.

This project can be particularly useful for engineers interested in data structure implementations and memory management in C, as it provides a clear and efficient way to work with Tries and Treaps.
