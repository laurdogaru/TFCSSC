## Repository Summary: TFCSSC

### Project Overview
The TFCSSC repository includes two main data structure implementations: a Trie and a Treap. Both structures are fundamental in various applications like search engines, databases, and memory management, enabling efficient data insertion, deletion, and retrieval.

### Main Components

1. **Trie ()**
   - A Trie is a tree-like structure that stores strings efficiently. It supports operations like insertion, deletion, and counting occurrences of strings.
   - Key Functions:
     -  - Initializes a new Trie node.
     -  - Inserts a string into the Trie and increments the count of that string.
     -  - Decreases the count of the string and deletes nodes if necessary.
     -  - Frees the memory allocated for the Trie.

2. **Treap ()**
   - A Treap is a hybrid of a binary search tree (BST) and a heap. It keeps keys sorted while maintaining a heap property based on randomly assigned priorities.
   - Key Functions:
     -  - Initializes a new Treap node.
     -  /  - Rotates the nodes to maintain the heap property.
     -  - Inserts a new key with an associated priority, maintaining BST and heap properties.
     -  - Deletes a node and readjusts the tree to maintain structure.

### Tech Stack
- **Programming Language**: C
- **Memory Management**: Utilizes manual memory allocation through  and deallocation with                total        used        free      shared  buff/cache   available
Mem:        16377696     1372336    12743436       43596     2631956    15005360
Swap:        3145724           0     3145724.
- **Data Structures**: Custom implementations of Trie and Treap.

### Conclusion
This repository provides efficient implementations for Trie and Treap data structures in C, offering key functionalities that can be employed in various applications requiring fast data retrieval and manipulation.
