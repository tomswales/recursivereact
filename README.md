# recursivereact
An illustration of recursive React components and a teaching aid in the form of balanced and unbalanced binary search trees.

These trees are staples of algorithms and data structures courses. They involve inserting ordered values into either the left or right subtree of a tree depending on whether the value is greater than  or less than the value of the current tree. If the values are the same, nothing happens. 

Using the files:

Just open the raw html files using the following links:

https://rawgit.com/tomswales/recursivereact/master/avltree.html

https://rawgit.com/tomswales/recursivereact/master/unbalancedbst.html

Unbalanced binary search tree:

Shows what happens when the tree is not rebalanced following insertion: the tree is much deeper, and search will take longer - with o(n) being the worst-case.

AVL Tree:

Shows what happens when the tree is rebalanced following insertion. Although rebalancing is more expensive, the retrieval will now take o(log(n)) time. 
