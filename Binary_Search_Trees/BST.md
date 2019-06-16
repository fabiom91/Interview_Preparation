# Binary Search Trees
![BST](bst.jpg)
## Definition

- A binary tree is any tree where the nodes have at maximum two nodes. 
- Meanwhile a binary **search** tree is organised such that:
  - All nodes in any subtree to the left of a node x have a lower value than x
  - Subnodes of greater value go to the right, those of lower value go to the left

There are different ways you can implement a BST: 
- with a parent tree structure containing nodes (and where a single root for the tree is specified in the parent structure)
- Where every node is itself a tree with a root - this makes more intuitive sense perhaps

## Constructing a BST

BST's usually have the following methods:
- insert (add a node)
- contains (does the tree contain a specific value? This also involves search)
- delete (remove a node from the tree)

See the BST.py file for the code...
