# TFCSSC Repository Overview

## Project Description
The TFCSSC repository contains implementations of two data structures commonly used in computer science for efficient data storage and retrieval: a Treap (a combination of a binary search tree and a heap) and a Trie (prefix tree). These structures are developed in C, showcasing operations like insertion, deletion, traversal, and memory management.

## Main Components

1. **Treap Implementation ():**
   - **Node Structure**: Represents each node in the treap, containing a key, priority, and pointers to left, right, and parent nodes.
   - **Core Functions**:
     - : Initializes a new node with a given value and priority.
     - : Inserts a new value with a priority into the treap while maintaining the binary search tree properties and balancing the tree.
     - : Removes a specified value from the treap, ensuring the treap properties remain intact.
     -  and : Perform rotations to maintain the heap property of the treap.
     - : Checks and adjusts the treap as needed after insertions.
     - Traversal functions (, , ) to visit nodes in different orders.

2. **Trie Implementation ():**
   - **Node Structure**: Represents each node in the trie, containing a count of words that pass through that node and pointers to its children.
   - **Core Functions**:
     - : Initializes a Trie node with children set to NULL and initializes count values.
     - : Adds a string to the trie, incrementing the count at the relevant nodes.
     - : Removes a string from the trie and adjusts node counts accordingly.
     - : Frees allocated memory for the entire trie.

## Tech Stack
- **Programming Language**: C
- **Memory Management**: Manual allocation and deallocation using  and                total        used        free      shared  buff/cache   available
Mem:        16377740      882560    14248032       45520     1599668    15495180
Swap:        3145724           0     3145724 for dynamic memory management to handle node creation and deletion.

## Conclusion
The TFCSSC repository provides foundational implementations of the Treap and Trie data structures, offering efficient means of organizing and retrieving data. It serves as an educational resource for engineers interested in understanding and utilizing these data structures through practical C programming examples.
