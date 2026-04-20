# TFCSSC Repository Overview

## Project Description
The TFCSSC repository contains implementations of two data structures: a Trie and a Treap. These structures are fundamental in computer science for efficient data storage and retrieval. The Trie is particularly useful for handling strings, while the Treap combines properties of binary search trees and heaps to maintain balance during insertions and deletions.

## Main Components
1. **Trie Implementation ()**:
   - **Data Structure**: A  is represented as a node with a count of words and an array of child pointers (one per alphabet letter, a-z).
   - **Functions**:
     - : Initializes a new Trie node.
     - : Inserts a string into the Trie.
     - : Deletes a string from the Trie.
     - : Frees all allocated memory associated with the Trie.

2. **Treap Implementation ()**:
   - **Data Structure**: A Treap node contains a key and a priority along with links to its left and right children and its parent.
   - **Functions**:
     - : Allocates and initializes a new Treap node.
     - : Inserts a new node, maintaining the heap properties.
     - : Deletes a node and rebalances the Treap as necessary.
     - : Frees the memory allocated for the Treap.
     - Utility functions for traversing the Treap with in-order, pre-order, and post-order methods, along with calculating its height.

## Tech Stack
- **Language**: C
- **Memory Management**: Manual memory allocation and deallocation using  and 
- **Data Structures**: The project primarily utilizes custom-defined structures and pointers, leveraging C's capabilities for low-level memory management.

## Conclusion
The TFCSSC repository provides fundamental data structure implementations that can be utilized in various applications requiring efficient string handling and balanced search tree operations. The straightforward approach to managing memory and data highlights C’s performance capabilities while providing an insightful exploration of Trie and Treap functionalities.
