# BLG-335E-Project-4-solution

Download Here: [BLG 335E Project 4 solution](https://jarviscodinghub.com/assignment/blg-335e-project-4-solution/)

For Custom/Original Work email jarviscodinghub@gmail.com/whatsapp +1(541)423-7793

Problem: In this project, you are expected to implement certain basic Red–Black Tree operations and then augment your data structure with extra operations for order statistics. Part A. Implementation (70 points)
1. (40 points) Implement a basic Red–Black Tree that supports insertion and printing. You do NOT have to implement updating and deletion.
The key for each of the nodes should be the corresponding person’s name. Age and gender values should be kept as extra attributes within your nodes.
Your insertion operation should insert a new node into the relevant position in the Red–Black Tree and then recolor and rotate existing nodes in order to meet the constraints and rebalance the tree.
2. (30 points) Augment your Red–Black Tree implementation with two new methods, nth woman and nth man, that return the name of the nth woman and man respectively.
Include the num_woman[x] and num_man[x] fields in your tree nodes, respectively holding the number of women and men in the sub-tree rooted at x, including x itself. Your implementation should make use of these fields in parallel with the size[x] field in the OS_SELECT example1. Make sure you update these fields as necessary whenever you modify the tree by another operation.
Execution: You are given an input file (input.txt) containing rows of data, each denoting a person. A name, an age value and a gender value is encoded for each person. Read the contents of the file and use your insertion operation to insert each person into your Red–Black Tree.
Your program should run from the command line with the following format:
