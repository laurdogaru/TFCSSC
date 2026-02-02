## Repository Summary: TFCSSC

### Project Overview
The TFCSSC repository consists of two primary implementations of data structures in C: a Trie and a Treap. These data structures are fundamental for various applications, such as text processing and efficient search operations. The project demonstrates how to perform basic operations like insertion, deletion, and traversal using these structures.

### Main Components

1. **Trie Implementation ()**:
   - **Structure Definition**: A  is defined with a count of words and a collection of child nodes, each representing a letter (from 'a' to 'z').
   - **Key Functions**:
     - : Initializes a new Trie node.
     - : Inserts a string into the Trie and updates the word count.
     - : Removes a string from the Trie and adjusts counts appropriately.
     - : Recursively frees the memory allocated to the Trie.
   - **Main Function**: Demonstrates initializing a Trie, inserting a string, and deleting it.

2. **Treap Implementation ()**:
   - **Structure Definition**: A Treap node contains a key, a priority for balancing, and pointers to left, right, and parent nodes.
   - **Key Functions**:
     - : Initializes a new Treap node with priority.
     - : Inserts a new key while maintaining the heap property based on priority.
     - : Deletes a key from the Treap while rebalancing it as needed.
     - : Frees the memory allocated to the Treap nodes.
     - Traversal functions (, , ) to print the tree nodes in different orders.
   - **Main Function**: Demonstrates inserting and deleting nodes, along with printing the in-order traversal of the Treap.

### Tech Stack
- **Programming Language**: C
- **Memory Management**: Manual memory allocation and deallocation using  and                total        used        free      shared  buff/cache   available
Mem:        16374544      947512    13870124       43488     1907532    15427032
Swap:        3145724           0     3145724.
- **Data Structures**: Trie and Treap, showcasing different techniques for storing hierarchical data.

This repository serves as a practical demonstration of how to implement and manipulate complex data structures in C, which can be beneficial for engineers looking to enhance their understanding of algorithms and data organization methods.
