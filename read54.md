# Tree Data Structure



- A tree is a nonlinear hierarchical data structure that consists of nodes(the node has its own value and the pointer to anther node),Root(is the first node in the tree ),ther is K value that represent the maximum number of connection for every node inside the tree and this node  connected by edges( It is the link between any two nodes).

![scanner](https://miro.medium.com/max/1194/1*ziYvZzrttFYMXkkV9u66jw.png)


## Tree Terminologies
I explen some in the first and here more:-
-  height of node: is the number of edges from the node to the deepest leaf
- depth of node: is the number of edges from the root to the node.
-  degree of node: is the total number of branches of that node.
-  Forest: A collection of disjoint trees is called a forest.

# Binary Tree Data Structure
- A binary tree is a tree data structure in which each parent node can have at most two children.

![scanner](https://cdn.programiz.com/sites/tutorial2program/files/binary-tree_0.png)

## Traversals tree :-
there are 2 type of traversals in trees:-
* Depth First
* Breadth First

## A Binary Tree node contains following parts.
- Data
- Pointer to left child
- Pointer to right child

## Binary Tree Vs K-ary Trees
* Binary Tree just can have tow child for every parents one in lift and one in right .
* but K-ary Trees  have any number of children for every parents and her we use K to refer to the maximum number of children that can be hold by every node .
# Binary Search Tree(BST)
![scanner](https://www.gatevidyalay.com/wp-content/uploads/2018/07/Binary-Search-Tree-Example.png)

- Binary search tree is a data structure that quickly allows us to maintain a sorted list of numbers.
- It is called a search tree because it can be used to search for the presence of a number in O(log(n)) time.

## properties:
- All nodes of left subtree are less than the root node
- All nodes of right subtree are more than the root node
