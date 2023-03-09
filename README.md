Jack Mahoney
CS 124 project 03
3/8/23
Binary search tree of 100 in order integers(x = value, y = depth):

The root node is 1 and all the other nodes are right children because they are larger than the node before them. The depth of the tree is 99 because it was one branch with 100 nodes.


Binary search tree of 100 integers in a random order(x = value, y = depth):

The root node is 75 and the depth of the tree is 13.


Binary search tree of custom objects(x = value, y = depth):

This tree is very similar to the in order binary search tree because the unique ID for my objects is their row number. The tree is the same as first binary search tree but with more objects. It’s root node is also 1 but it’s depth is 1098 because there are 1099 nodes in the tree.
Avl tree of 100 in order integers(x = value, y = depth):

The root node is 64 and the depth is 6;

Avl tree of 100 integers in a random order(x = value, y = depth):

The root node is 52 and the depth is 7.

Avl tree of custom objects(x = value, y = depth):

The root node is 511 and the depth is 10.

The avl trees have different depth and roots than the regular binary search trees because they are complete trees and their branches cannot differ in length by more than one. This means that as the tree is being made, it’s depth and root are being modified to maintain the AVL properties.

Splay search tree of 100 in order integers(x = value, y = depth):

The root node is 1. Because each node has a depth of one when you search for it, the depth of the tree cannot be determined from this graph. This makes sense because every time a node is found, it is splayed up to the root, a depth of zero, and the next node is moved up to a depth of one.

Splay search tree of 100 integers in a random order(x = value, y = depth):

The root node is 1 and you cannot tell the depth from this graph because the nodes are moved to the root after being searched for so the depth can change after each search.
Splay search tree of custom objects(x = value, y = depth):

The root node is 1. Because each node has a depth of one when you search for it, the depth of the tree cannot be determined from this graph.



Splay Experiments
Splaying each object 5 times:
When each object is splayed 5 times, the recorded depths are five zero’s for the first node, followed by 5 ones for each node after resulting in 500 entries.
Changing splay on add to “true”:
In the splayTests2.cpp file experiment, when the nodes were splayed splayed on add, the average depth was 5.579, and when they weren’t, the average depth increased to 6.628. It makes sense that the average depths are different because everytime a node is splayed, it is moved to the root and affect the depths of other nodes throughout the tree, thus affecting the average depth of the tree.

