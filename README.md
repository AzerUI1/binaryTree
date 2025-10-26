Binary Trees Project
https://upload.wikimedia.org/wikipedia/commons/thumb/d/da/Binary_search_tree.svg/400px-Binary_search_tree.svg.png

📋 Project Overview
This repository contains implementations of various binary tree data structures and algorithms in C, including:

Binary Trees - Basic tree operations and traversals

Binary Search Trees (BST) - Sorted tree structures

AVL Trees - Self-balancing binary search trees

Binary Heaps - Priority queue implementations

🚀 Quick Navigation
🔧 Basic Operations
https://img.shields.io/badge/0-New_Node-blue
https://img.shields.io/badge/1-Insert_Left-green
https://img.shields.io/badge/2-Insert_Right-green
https://img.shields.io/badge/3-Delete_Tree-red

🔍 Tree Properties
https://img.shields.io/badge/4-Is_Leaf-yellow
https://img.shields.io/badge/5-Is_Root-yellow
https://img.shields.io/badge/9-Height-orange
https://img.shields.io/badge/10-Depth-orange

📊 Tree Traversals
https://img.shields.io/badge/6-Pre_order-purple
https://img.shields.io/badge/7-In_order-purple
https://img.shields.io/badge/8-Post_order-purple
https://img.shields.io/badge/20-Level_order-purple

🌳 Advanced Types
https://img.shields.io/badge/BST-Search_Insert_Remove-success
https://img.shields.io/badge/AVL-Balanced_Trees-success
https://img.shields.io/badge/Heap-Priority_Queue-success

📁 File Structure
text
binary_trees/
├── 📄 0-18*.c                 # Basic binary tree operations
├── 📄 100-104*.c              # Advanced tree operations
├── 📄 110-115*.c              # Binary Search Tree implementations
├── 📄 120-125*.c              # AVL Tree implementations  
├── 📄 130-135*.c              # Binary Heap implementations
├── 📄 binary_trees.h          # Header file with type definitions
├── 📄 binary_tree_print.c     # Tree visualization utility
└── 📁 tests/                  # Test files for each task
🛠️ Compilation Examples
bash
# Basic node creation
gcc -Wall -Wextra -Werror -pedantic binary_tree_print.c 0-main.c 0-binary_tree_node.c -o 0-node

# Tree traversals  
gcc -Wall -Wextra -Werror -pedantic binary_tree_print.c 6-main.c 6-binary_tree_preorder.c 0-binary_tree_node.c -o 6-pre

# BST operations
gcc -Wall -Wextra -Werror -pedantic binary_tree_print.c 110-main.c 110-binary_tree_is_bst.c 0-binary_tree_node.c -o 110-is_bst
📊 Complexity Analysis
Time Complexities
Operation	BST	AVL	Heap
Insert	O(h)	O(log n)	O(log n)
Search	O(h)	O(log n)	O(n)
Delete	O(h)	O(log n)	O(log n)
Where h is the height of the tree

🎯 Learning Objectives
Understand binary tree data structures and their properties

Implement various tree traversal algorithms

Work with self-balancing trees (AVL)

Implement priority queues using binary heaps

Analyze time and space complexity of tree operations

👨‍💻 Author
Azer Aslanov

<div align="center">
https://img.shields.io/badge/%F0%9F%94%97-Binary_Trees_Repo-blue?style=for-the-badge
https://img.shields.io/badge/%F0%9F%92%BB-C_Programming-green?style=for-the-badge
https://img.shields.io/badge/%F0%9F%93%9A-Data_Structures-red?style=for-the-badge

Mastering tree data structures one node at a time! 🌳

</div>
