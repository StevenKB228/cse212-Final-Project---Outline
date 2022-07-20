# TREE:

A tree is a widely used abstract data type that are used to store the data in the hierarchical structure. They are nonlinear data structure, compared to arrays, linked lists, stacks and queues which are linear data structures. 

![binary_search_tree](https://user-images.githubusercontent.com/92330348/179665226-0dfbe4f2-88ed-43a6-8a05-fcf5ff4af6b6.jpeg)

They are used to store data that has an inherent hierarchical structure. They are also dynamic, which means that it is easy to add and delete nodes.

![tree](https://user-images.githubusercontent.com/92330348/179665833-b9f46957-5a3c-4196-ba63-4a689a09a44e.png)

Trees have two operating systems:


. Binary tree which is a tree that links to no more than two other nodes, the two children are usually called the left and right nodes.



. Binary search tree (BST) which is a binary tree that follows rules for data that is put into the tree. In this data is placed into the BST by comparing the data with the value in the parent node but if the data being added is less than the parent node, then it is put in the left subtree.



# Implementing Trees:

create a node class that has data and an insert class. The insert class will compare the value of the node to the parent node and decides to add it as a left node or a right node. Finally the PrintTree class is used to print the tree.

 This is just me creating a Node class and adding an assigned value to the node. This becomes tree with only a root node.       
       
       
       class Node:
           def __init__(self, data):
              self.left = None
              self.right = None
              self.data = data
           def PrintTree(self):
              print(self.data)

        root = Node(22)
        root.PrintTree()
        
        
        
 # Tree problem:       
        
        
 















 - [0-welcome.md](0-welcome.md)




