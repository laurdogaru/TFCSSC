## Repository Summary: TFCSSC

### Project Overview
The TFCSSC project contains implementations of two data structures: a Trie and a Treap. This repository is designed to provide engineers with foundational algorithms for string manipulation (with the Trie) and efficient search and priority functionality (with the Treap) in C programming.

### Main Components
1. **Trie Implementation ():**
   - **Structure:** Implements a Trie (prefix tree) to handle string insertions, deletions, and traversals.
   - **Key Functions:**
     - : Initializes a new Trie node.
     - : Adds a string to the Trie, updating the count and number of children nodes.
     - : Removes a string and manages the node memory appropriately.
     - : Recursively frees the allocated memory for the Trie.
   - **Usage:** Demonstrates basic operations by inserting and deleting a sample string .

2. **Treap Implementation ():**
   - **Structure:** Combines properties of a binary search tree and a heap (based on node priority) to maintain balanced tree structure during insertions and deletions.
   - **Key Functions:**
     - : Creates and initializes a new treap node.
     -  and : Implements rotations to maintain heap properties during insertion/deletion.
     - : Checks and adjusts the tree to keep it balanced.
     - : Inserts a new key-value pair while maintaining treap properties.
     - : Deletes a key from the treap and rebalances the tree as necessary.
     - : Frees all allocated memory of the treap nodes.
     - , , and : Traversal functions to examine nodes in different orders.
   - **Usage:** Demonstrates functionality by inserting multiple values, deleting one, and printing the in-order traversal.

### Tech Stack
- **Programming Language:** C
- **Data Structures:** 
  - Trie for efficient prefix-based searches in strings.
  - Treap for combined search and priority queue functionality in a balanced binary search format.
  
### Conclusion
TFCSSC serves as a resource for engineers looking to understand and implement fundamental data structures in C. It provides clear function definitions and examples to manipulate Tries and Treaps, facilitating learning and practical application of these algorithms in software development.
