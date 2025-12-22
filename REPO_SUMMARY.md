## Project Summary: TFCSSC

### Overview
The TFCSSC repository contains implementations of two advanced tree data structures in C: a Trie and a Treap. These structures facilitate efficient storage and retrieval of data, with the Trie optimized for prefix queries and the Treap combining binary search tree properties with heap properties for dynamic data management.

### Main Components

1. **Trie Implementation ()**:
   - **Structure**: 
     - Each Trie node contains an array of children pointers (one for each letter of the alphabet), a count of strings that pass through this node, and a count of how many child nodes exist.
   - **Functions**:
     - : Initializes a new Trie node.
     - : Inserts a string into the Trie, updating counts as necessary.
     - : Deletes a string from the Trie, managing both count and memory.
     - : Recursively frees allocated memory for the Trie.
   - **Example Usage**: The main function demonstrates basic insert and delete operations.

2. **Treap Implementation ()**:
   - **Structure**:
     - Each Treap node consists of a key, priority, pointers to left and right children, and a pointer to the parent node.
   - **Functions**:
     - : Initializes a new Treap node.
     -  and : Perform rotations required to maintain the heap property.
     - : Ensures the Treap retains the correct structure after insertions or deletions.
     - : Inserts keys into the Treap while balancing it based on node priorities.
     - : Deletes a key from the Treap while maintaining structure.
     - : Recursively frees the Treap’s memory.
     - Tree traversal functions (, , ) are implemented to print keys in various orders.
   - **Example Usage**: The main function demonstrates inserting and deleting nodes, along with tree traversal.

### Tech Stack
- **Programming Language**: C
- **Memory Management**: Manual memory allocation with  and                total        used        free      shared  buff/cache   available
Mem:        16379472     1025332     8925536       45092     6828372    15354140
Swap:        4194300           0     4194300.
  
### Conclusion
The TFCSSC project provides robust implementations of Trie and Treap data structures, showcasing efficient string and numerical data handling while providing functions for insertion, deletion, and traversal. The choice of C for this implementation ensures low-level memory control, vital for performance-sensitive applications.
