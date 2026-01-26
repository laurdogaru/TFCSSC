## Project Overview: TFCSSC

The TFCSSC repository contains implementations of two advanced data structures: a Trie and a Treap. It serves as a practical example for engineers interested in understanding and utilizing efficient data structures for string and numeric manipulation in C programming.

### Main Components

1. **Trie Implementation ()**:
   - A Trie (prefix tree) is a specialized tree used primarily for storing strings.
   - **Key Features**:
     - **Insertion**: Strings are added to the trie, allowing for quick retrieval of prefixes.
     - **Deletion**: The trie enables removing strings while maintaining structural integrity.
     - **Traversal**: The trie can be traversed for counting occurrences, which is beneficial for applications like autocomplete.
   - **Structure**:
     - Each node contains an array of child pointers for 26 lowercase English letters and maintains a count of occurrences and the number of distinct sub-nodes.

2. **Treap Implementation ()**:
   - A Treap is a combination of a binary search tree and a heap, which governs the priority of nodes.
   - **Key Features**:
     - **Insertion & Deletion**: Maintains both the binary search tree property (ordering by keys) and the heap property (ordering by priorities).
     - **Balancing**: The treap automatically rebalances itself during insertion/deletion through rotations to ensure optimal performance.
     - **Traversal**: Supports in-order, pre-order, and post-order traversals for various use cases.
   - **Structure**:
     - Each node contains a key, a priority, and pointers to its left, right, and parent nodes.

### Tech Stack

- **Programming Language**: C
- **Memory Management**: Manual memory allocation via  and deallocation using                total        used        free      shared  buff/cache   available
Mem:        16374544     1013036     9549324       44284     6211160    15361508
Swap:        4194300           0     4194300, emphasizing efficient memory usage and management.
- **Data Structures**: Implementation of Trie and Treap, which are fundamental data structures for handling dynamic sets and associative arrays.

### Potential Use Cases

- **Text Processing**: The Trie can be used in applications where rapid string search and prefix matching are required, such as search engines and word prediction tools.
- **Dynamic Data Management**: The Treap can efficiently manage collections of unique integers with dynamic insertion and deletion, making it suitable for applications that require real-time data manipulation.

Overall, the TFCSSC repository provides a solid foundation for engineers seeking to understand the implementation intricacies and applications of these data structures in C programming.
