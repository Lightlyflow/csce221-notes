# 2-4 Trees 
AKA B-trees or multiway trees (if you google this, but these are the general names)

| Property | Value |
| --- | --- |
| Height | $O(\log n)$ |
| Search | $O(\log n)$ |
| Insertion | $O(\log n)$

### Nodes
| Name | Values | Pointers |
| --- | --- | --- |
| 2 Node | 1 | 2 |
| 3 Node | 2 | 3 |
| 4 Node | 3 | 4 |

### Insertion
Insertion causes an overflow when a node has values = $b$. If this happens, then we can split the node where the overflow happened.

### Traversal 
Know:
- Pre
- In
- Post

