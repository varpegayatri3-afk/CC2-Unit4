
Develop a stock ticker application using an AVL tree to display the tree sideways after each stock ID insertion.
## 1. Problem Statement

Managing stock records using traditional sequential data structures, such as static arrays, can create limitations due to fixed memory allocation and costly insertion and searching operations. As the number of stock records increases, maintaining and organizing the data becomes more difficult.

The objective of this project is to develop a Stock Ticker Application using an AVL Tree in C++ to store and manage Stock ID, Stock Name, and Stock Price. The application supports stock insertion, searching, and display operations while maintaining tree balance through rotations. It also displays the AVL tree sideways to visualize the hierarchical arrangement of stock records.

## 2. Objectives

- To implement an AVL Tree using C++ for efficient stock record management.
- To store Stock ID, Stock Name, and Stock Price in dynamically allocated nodes.
- To maintain tree balance using LL, RR, LR, and RL rotations.
- To provide efficient insertion and searching of stock records.
- To display stock records in ascending order of Stock ID using inorder traversal.
- To visualize the hierarchical structure through sideways tree display.
- To apply pointers, dynamic memory allocation, recursion, and tree traversal concepts.

## 3. Technology Objectives

- Programming Language: C++ for implementing the stock management application.
- Data Structure: AVL Tree for storing stock records in a self-balancing binary search tree.
- Dynamic Memory Allocation: Use of `new` to create stock nodes dynamically.
- Pointers: Use of left and right pointers to connect tree nodes.
- Recursion: Used in insertion, searching, traversal, and tree display functions.
- AVL Rotations: Implementation of LL, RR, LR, and RL rotations to maintain balance.
- Development Environment: Visual Studio Code with a C++ compiler such as GCC (`g++`).
- User Interface: A menu-driven console interface for inserting, searching, and displaying stock records.

Expected outcome: A working C++ application that organizes stock records efficiently using an AVL tree. Stock prices are entered manually; live stock market data is not included in the current implementation.
