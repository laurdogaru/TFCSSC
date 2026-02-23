### Summary of the Repository

**Project Title**: TFCSSC

**Project Overview**:  
The TFCSSC repository implements two key data structures commonly used in computer science for efficient storage and retrieval of information: a Trie and a Treap. These structures serve essential roles in various algorithms, particularly in tasks involving string manipulation (Trie) and maintaining sorted data with heap properties (Treap).

---

### Main Components

1. **Trie**:
   - **File**: 
   - **Description**: The Trie (prefix tree) is designed to facilitate the storage and retrieval of strings in a way that supports efficient prefix searches. It allows for operations like insertion, deletion, and memory cleanup. Each node in the Trie represents a character and supports children for subsequent characters, making it especially useful for applications like autocomplete and spell checking.
   - **Key Functions**:
     - : Initializes a new Trie node.
     - : Inserts a string into the Trie.
     - : Removes a string from the Trie, adjusting the structure as necessary.
     - : Frees the allocated memory for the Trie and its nodes.

2. **Treap**:
   - **File**: 
   - **Description**: The Treap is a randomized binary search tree that maintains a priority for each node, ensuring that it remains balanced. This structure combines properties of both binary search trees (for order) and heaps (for balancing based on priority). It supports insertions, deletions, and traversal operations (in-order, pre-order, post-order).
   - **Key Functions**:
     - : Initializes a new node with a specified value and priority.
     - : Inserts a new node into the Treap, maintaining the binary search tree properties and balancing it based on priority.
     - : Removes a node while keeping the structure balanced.
     - : Cleans up the allocated memory for the Treap and its nodes.
     - Traversal methods: Implemented for in-order, pre-order, and post-order outputs.

---

### Tech Stack

- **Programming Language**: C
- **Libraries**: Standard C libraries (stdlib.h for memory management, stdio.h for input and output)

This repository is structured to provide clear implementations and operations for both data structures. It showcases fundamental techniques in dynamic memory management and algorithm design that are crucial for efficient data handling in software engineering.
