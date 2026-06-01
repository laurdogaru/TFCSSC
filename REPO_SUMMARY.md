## Repository Summary: TFCSSC

### Project Overview
The TFCSSC project implements two distinct data structures in C: a **Treap** and a **Trie**. A treap is a combination of a binary search tree and a heap, allowing for efficient storage and retrieval of key-value pairs while maintaining a randomized balance based on priority. A trie is a tree-like data structure primarily used for storing strings, providing efficient prefix-based searches. This repository includes implementations of both data structures along with functions for insertion, deletion, and traversal operations.

### Main Components

1. **Treap Implementation ()**:
   - **Node Structure**: The  structure encapsulates each treap node with properties for key, priority, and pointers to left, right, and parent nodes.
   - **Initialization**:  function creates a new node with specified values.
   - **Insertion**:  function adds elements to the treap and invokes balancing operations to maintain the treap properties.
   - **Deletion**: The  function removes an element and performs necessary rotations to keep the treap balanced.
   - **Balancing**: The  function utilizes left and right rotations to ensure that the treap structure remains valid after insertions and deletions.
   - **Traversal**: Functions for in-order, pre-order, and post-order traversals (, , ) output keys in different sequences.

2. **Trie Implementation ()**:
   - **Trie Structure**: The  structure holds counts for inserted strings and provides pointers to children nodes (26 for each letter of the English alphabet).
   - **Initialization**: The  function creates the root node of the trie.
   - **Insertion**: The  function places strings into the trie, increasing the count as characters are added.
   - **Deletion**: The  function removes strings from the trie and manages node deallocation if nodes become unused.
   - **Memory Management**: The  function recursively frees allocated memory for the trie's nodes.

### Tech Stack
- **Programming Language**: C
- **Key Concepts**: 
  - Dynamic memory allocation (via  and )
  - Pointer manipulation for tree structures
  - Recursive algorithms for insertion, deletion, and traversal

### Usage
Each file contains a  function demonstrating usage of the respective data structures, including inserting and deleting elements in both the treap and the trie. Engineers can utilize or enhance these implementations in their projects or for educational purposes in data structure studies.
