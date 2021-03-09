# 0x1D. C - Binary trees
---

## Description :newspaper:
This project was created with learning purposes at Holberton School; on `Ubuntu 14.04`; and is about Binary Trees in C.

---

A binary tree is a tree data structure in which each node has at most two children, which are referred to as the `left child` and the `right child`.
A binary tree has the benefits of both an ordered array and a linked list as search is as quick as in a sorted array and insertion or deletion operation are as fast as in linked list.
![BinaryTree_parts](https://www.tutorialspoint.com/data_structures_algorithms/images/binary_tree.jpg)
#### Important Terms
Following are the important terms with respect to tree.
- *`Path`* − Path refers to the sequence of nodes along the edges of a tree.
- *`Root`* − The node at the top of the tree is called root. There is only one root per tree and one path from the root node to any node.
- *`Parent`* − Any node except the root node has one edge upward to a node called parent.
- *`Child`* − The node below a given node connected by its edge downward is called its child node.
- *`Leaf`* − The node which does not have any child node is called the leaf node.
- *`Subtree`* − Subtree represents the descendants of a node.
- *`Visiting`* − Visiting refers to checking the value of a node when control is on the node.
- *`Traversing`* − Traversing means passing through nodes in a specific order.
- *`Levels`* − Level of a node represents the generation of a node. If the root node is at level 0, then its next child node is at level 1, its grandchild is at level 2, and so on.
- *`keys`* − Key represents a value of a node based on which a search operation is to be carried out for a node.

---

### Resources :blue_book: :orange_book: :green_book:
Read or watch:
- [Tree](https://www.tutorialspoint.com/data_structures_algorithms/tree_data_structure.htm)
- [Tree Traversal](https://www.tutorialspoint.com/data_structures_algorithms/tree_traversal.htm)
- [Binary Search Tree](https://www.tutorialspoint.com/data_structures_algorithms/binary_search_tree.htm)
- [Binary Tree](https://www.youtube.com/watch?v=H5JubkIy_p8)

---

### Tasks :white_check_mark:
| Task No. | Description | prototype |
| -------- | ----------- | --------- |
| 0. New node | Write a function that creates a binary tree node | `binary_tree_t *binary_tree_node(binary_tree_t *parent, int value);` |
| 1. Insert left | Write a function that inserts a node as the left-child of another node | `binary_tree_t *binary_tree_insert_left(binary_tree_t *parent, int value);` |
| 2. Insert right | Write a function that inserts a node as the right-child of another node | `binary_tree_t *binary_tree_insert_right(binary_tree_t *parent, int value);` |
| 3. Delete | Write a function that deletes an entire binary tree | `void binary_tree_delete(binary_tree_t *tree);` |
| 4. Is leaf | Write a function that checks if a node is a leaf | `int binary_tree_is_leaf(const binary_tree_t *node);` |
| 5. Is root | Write a function that checks if a given node is a root |`int binary_tree_is_root(const binary_tree_t *node);` |
| 6. Pre-order traversal | Write a function that goes through a binary tree using pre-order traversal | `void binary_tree_preorder(const binary_tree_t *tree, void (*func)(int));` |
| 7. In-order traversal | Write a function that goes through a binary tree using in-order traversal | `void binary_tree_inorder(const binary_tree_t *tree, void (*func)(int));` |
| 8. Post-order traversal | Write a function that goes through a binary tree using post-order traversal | `void binary_tree_postorder(const binary_tree_t *tree, void (*func)(int));` |
| 9. Height | Write a function that measures the height of a binary tree | `size_t binary_tree_height(const binary_tree_t *tree);` |
| 10. Depth |Write a function that measures the depth of a node in a binary tree | `size_t binary_tree_depth(const binary_tree_t *tree);` |
| 11. Size | Write a function that measures the size of a binary tree | `size_t binary_tree_size(const binary_tree_t *tree);` |
| 12. Leaves | Write a function that counts the leaves in a binary tree | `size_t binary_tree_leaves(const binary_tree_t *tree);` |
| 13. Nodes | Write a function that counts the nodes with at least 1 child in a binary tree | `size_t binary_tree_nodes(const binary_tree_t *tree);` |
| 14. Balance factor | Write a function that measures the balance factor of a binary tree | `int binary_tree_balance(const binary_tree_t *tree);` |
| 15. Is full | Write a function that checks if a binary tree is full | `int binary_tree_is_full(const binary_tree_t *tree);` |
| 16. Is perfect | Write a function that checks if a binary tree is perfect | `int binary_tree_is_perfect(const binary_tree_t *tree);` |
| 17. Sibling | Write a function that finds the sibling of a node | `binary_tree_t *binary_tree_sibling(binary_tree_t *node);` |
| 18. Uncle | Write a function that finds the uncle of a node | `binary_tree_t *binary_tree_uncle(binary_tree_t *node);` |

---

## Author :bust_in_silhouette:
- [Adrian Vides] | [Twitter] | [GitHub]


---

[GitHub]: <https://github.com/AdrianVides56>
[Twitter]: <https://twitter.com/termi56661>
[Adrian Vides]: <https://www.linkedin.com/in/adrian-felipe-vides-jimenez-a201401b7>   
