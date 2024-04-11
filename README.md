# 0x1D. C - Binary trees

# 0. New node
mandatory
Write a function that creates a binary tree node
Write a function that inserts a node as the left-child of another node
Write a function that deletes an entire binary tree
Write a function that checks if a node is a leaf
Write a function that checks if a given node is a root
Write a function that goes through a binary tree using pre-order traversal
Write a function that goes through a binary tree using in-order traversal
Write a function that goes through a binary tree using post-order traversal
Write a function that measures the height of a binary tree
Write a function that measures the depth of a node in a binary tree

Prototype: binary_tree_t *binary_tree_node(binary_tree_t *parent, int value);
Where parent is a pointer to the parent node of the node to create
And value is the value to put in the new node
When created, a node does not have any child
Your function must return a pointer to the new node, or NULL on failure

