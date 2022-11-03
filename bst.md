# Binary Search Trees

| Operation | Worst Time | Average Time | Best Time |
| ---   |   ---     | --- | --- |
| Insertion | $O(n)$ | $O(h)$ | $O(\log_2n)$ |
| Deletion | $O(n)$ | $O(h)$ | $O(\log_2n)$ | 
| Find | $O(n)$ | $O(h)$ | $O(\log_2n)$ |

Know how to:
- Convert from algebraic expression to postfix form (represented by expression tree)

## Properties
- $n_e$ = numbers of external nodes (nullptr)
- $n_i$ = number of internal nodes
- $n$ = number of nodes

The number of nodes at each 

### Depth vs Height
Depth is distance from root. Height is distance from bottom.

## Types of BST
### Proper/Full BST
All nodes have either 2 children or no children.

### Dense/Complete BST
Everything smooshed to the left.

## Traversals
- Preorder (root, left, right)
- Inorder (left, root, right)
- Postorder (left, right, root)

