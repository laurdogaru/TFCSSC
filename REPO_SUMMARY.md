# TFCSSC Repository Overview

The **TFCSSC** repository implements two fundamental data structures: a **Trie** and a **Treap**. Both structures demonstrate basic operations such as insertion, deletion, and traversal, providing a foundation for efficient data processing and organization.

## Main Components

1. **Trie (trie.c)**
    - A Trie is a tree-like data structure used for storing a dynamic set of strings or associative arrays. It is particularly useful for tasks involving prefix-based searching, such as autocompletion or spell checking.
    - **Key Functions**:
        - : Initializes a new Trie node.
        - : Inserts a string into the Trie.
        - : Deletes a string from the Trie.
        - : Recursively frees the memory allocated to the Trie.
    - **Data Members**:
        - : Tracks the number of times a string is inserted.
        - : The number of children nodes, indicating how many links to other nodes exist.

2. **Treap (treap.c)**
    - A Treap is a hybrid data structure that combines properties of a binary search tree and a heap, maintaining a balanced structure based on the priority of each node.
    - **Key Functions**:
        - : Initializes a new Treap node.
        - : Inserts a node while maintaining Treap properties.
        - : Deletes a node and rebalances the Treap if necessary.
        - : Frees memory allocated for the Treap recursively.
        - , , : Methods for traversing the Treap in different orders.
    - **Data Members**:
        - : The value of the node.
        - : Used to maintain the heap property, allowing for efficient balancing.

## Tech Stack

- **Programming Language**: C
- **Memory Management**: Manual (using  and                total        used        free      shared  buff/cache   available
Mem:        16373468     1409528    12690616       45168     2646072    14963940
Swap:        3145724           0     3145724 for node allocation and deallocation)

## Usage

The implementation in both  and  includes a  function demonstrating the usage of the data structures through various function calls, including the insertion and deletion of nodes (or strings) and basic traversal operations.

This repository serves as a solid educational foundation for engineers seeking to understand and implement Tries and Treaps in C, emphasizing their respective algorithms and memory management techniques.
