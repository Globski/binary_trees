# c - Binary Trees

## Description
The Binary Trees Project is a collection of functions and algorithms for working with binary trees, including binary search trees (BSTs) and binary heaps. This project provides functionality for creating, manipulating, and traversing binary trees efficiently in the C programming language.

## Introduction

A binary tree is a data structure in which each node has at most two children, referred to as the left child and the right child. This project implements various binary tree operations such as creating a node, inserting nodes, traversing the tree, and measuring different properties of the tree.


## Project Structure

| Task                   | Description                                                          | Deliverable                  |
|------------------------|----------------------------------------------------------------------|------------------------------|
| 0. New Node            | Write a function that creates a binary tree node                     | 0-binary_tree_node.c         |
| 1. Insert Left         | Write a function that inserts a node as the left-child of another node| 1-binary_tree_insert_left.c  |
| 2. Insert Right        | Write a function that inserts a node as the right-child of another node| 2-binary_tree_insert_right.c |
| 3. Delete              | Write a function that deletes an entire binary tree                   | 3-binary_tree_delete.c       |
| 4. Is Leaf             | Write a function that checks if a node is a leaf                      | 4-binary_tree_is_leaf.c      |
| 5. Is Root             | Write a function that checks if a given node is the root              | 5-binary_tree_is_root.c      |
| 6. Pre-order Traversal | Write a function that goes through a binary tree using pre-order traversal | 6-binary_tree_preorder.c   |
| 7. In-order Traversal  | Write a function that goes through a binary tree using in-order traversal | 7-binary_tree_inorder.c    |
| 8. Post-order Traversal| Write a function that goes through a binary tree using post-order traversal | 8-binary_tree_postorder.c  |
| 9. Height              | Write a function that measures the height of a binary tree             | 9-binary_tree_height.c      |
| 10. Depth              | Write a function that measures the depth of a node in a binary tree   | 10-binary_tree_depth.c      |
| 11. Size               | Write a function that measures the size of a binary tree              | 11-binary_tree_size.c       |
| 12. Leaves             | Write a function that counts the leaves in a binary tree              | 12-binary_tree_leaves.c     |
| 13. Nodes              | Write a function that counts the nodes with at least 1 child in a binary tree | 13-binary_tree_nodes.c   |
| 14. Balance Factor     | Write a function that measures the balance factor of a binary tree    | 14-binary_tree_balance.c    |
| 15. Is Full            | Write a function that checks if a binary tree is full                 | 15-binary_tree_is_full.c    |
| 16. Is Perfect         | Write a function that checks if a binary tree is perfect              | 16-binary_tree_is_perfect.c |
| 17. Sibling            | Write a function that finds the sibling of a node in a binary tree    | 17-binary_tree_sibling.c    |
| 18. Uncle              | Write a function that finds the uncle of a node in a binary tree      | 18-binary_tree_uncle.c      |
| 19. Lowest Common Ancestor | Write a function that finds the lowest common ancestor of two nodes in a binary tree | 100-binary_trees_ancestor.c |
| 20. Level-order Traversal | Write a function that goes through a binary tree using level-order traversal | 101-binary_tree_levelorder.c |
| 21. Is Complete        | Write a function that checks if a binary tree is complete             | 102-binary_tree_is_complete.c |
| 22. Rotate Left        | Write a function that performs a left-rotation on a binary tree       | 103-binary_tree_rotate_left.c |
| 23. Rotate Right       | Write a function that performs a right-rotation on a binary tree      | 104-binary_tree_rotate_right.c |
| 24. Is BST             | Write a function that checks if a binary tree is a valid Binary Search Tree | 110-binary_tree_is_bst.c  |
| 25. BST - Insert       | Write a function that inserts a value in a Binary Search Tree         | 111-bst_insert.c            |
| 26. BST - Array to BST | Write a function that builds a Binary Search Tree from an array       | 112-array_to_bst.c          |
| 27. BST - Search       | Write a function that searches for a value in a Binary Search Tree    | 113-bst_search.c            |
| 28. BST - Remove       | Write a function that removes a node from a Binary Search Tree       | 114-bst_remove.c            |
| 29. Big O #Binary Tree | Identify the average time complexities of various Binary Tree operations | 115-O                       |
| 30. Is AVL             | Write a function that checks if a binary tree is a valid AVL Tree     | 120-binary_tree_is_avl.c    |
| 31. AVL - Insert       | Write a function that inserts a value in an AVL Tree                  | 121-avl_insert.c            |
| 32. AVL - Array to AVL | Write a function that builds an AVL Tree from an array                | 122-array_to_avl.c          |
| 33. AVL - Remove       | Write a function that removes a node from an AVL Tree                 | 123-avl_remove.c            |
| 34. AVL - From sorted array | Write a function that builds an AVL tree from a sorted array     | 124-sorted_array_to_avl.c   |
| 35. Big O #AVL Tree    | Identify the average time complexities of various AVL Tree operations | 125-O                       |
| 36. Min Binary Heap    | Write a function that creates a Min Binary Heap from an array         | 130-heap_insert.c           |
| 37. Heap - Extract     | Write a function that extracts the root node of a Max Binary Heap     | 133-heap_extract.c          |
| 38. Heap - Sort        | Write a function that converts a Binary Max Heap to a sorted array    | 134-heap_to_sorted_array.c  |
| 39. Big O #Binary Heap | Identify the average time complexities of operations on a Binary Heap | 135-O                       |


## Requirements

1. The project should be written in C programming language.
2. All code must follow the Betty style guide.
3. The project must be compiled with GCC 4.8.4 using the flags -Wall -Werror -Wextra and -pedantic.
4. Only the following standard library functions are allowed: `malloc`, `free`, and `perror`.
5. The code must be thoroughly tested with unit tests using the check framework.
6. The project must be hosted on a version control system such as GitHub.

## Learning Objectives

- What is a binary tree
- What is the difference between a binary tree and a Binary Search Tree
- What is the possible gain in terms of time complexity compared to linked lists
- What are the depth, the height, the size of a binary tree
- What are the different traversal methods to go through a binary tree
- What is a complete, a full, a perfect, a balanced binary tree

## How to Use

1. Clone the repository to your local machine:

    ```bash
    git clone https://github.com/your_username/binary_trees.git
    ```

2. Compile the source files using your preferred compiler:

    ```bash
    gcc -Wall -Wextra -Werror -pedantic *.c -o binary_trees
    ```

3. Run the main program to see example usage of the implemented binary tree operations:

    ```bash
    ./binary_trees
    ```

## Compilation & Testing

To compile the project, you can use the following command:

```bash
gcc -Wall -Wextra -Werror -pedantic *.c -o binary_trees
```

This will compile all the `.c` files and create an executable named `binary_trees`.

To test the functions, you can use the test files provided in the repository.
