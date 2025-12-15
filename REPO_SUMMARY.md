## Repository Summary: TFCSSC

### Project Overview
The TFCSSC (Two-Finger Complexity Search, Sort, and Comparison) repository implements a binary tree data structure with priority-based balancing. This project allows users to insert and delete nodes while maintaining tree properties through rotations, ensuring efficient data access and manipulation. The primary functions include inserting nodes with associated priority values, deleting nodes, and traversing the tree using various methods (in-order, pre-order, and post-order).

### Main Components
1. **Node Structure**: The  struct contains the integer key, priority, and pointers to left, right, and parent nodes. This structure is key to building the binary tree.
   
2. **Node Initialization**: The  function allocates memory for a new node, initializes its properties, and establishes its parent-child relationships.

3. **Insertion**: The  function places a new node in the correct position based on its key, followed by balancing
