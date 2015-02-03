boring-stuff
==================

Boring Problems and Solutions :)

##Resources
- http://beust.com/algorithms.pdf
- http://www.codewars.com/dashboard
- http://www.geeksforgeeks.org/
- http://www.problee.com
- http://codingbat.com
- http://codepad.org
- http://crazyforcode.com
- http://www.cs.usfca.edu/~galles/visualization/Algorithms.html

##Problems

###Sorting

1. Selection Sort - Implement and describe complexity

###Arrays

1. Sum3EqualsZero - Given array of integers, return true if any 3 elements in array sum to zero
2. MaxContigSumArray - Given array of integers, return max sum of contiguous elements in array
3. MaxSum3Array - Given array of integers, return max sum of 3 element subset
4. SetMatrixToZero - If an element in a M x N matrix is zero, set its entire row and column to zero.
5. FindOnesInMatrix - Given a 2D SORTED matrix, return the row index with the most ones
6. MajorityElement - given a array of integers, print out the element that appears more than n/2 times. Otherwise print not found.

###Strings

1. IsAnagram - Return true if two strings are anagrams (each string contains the exact same alpha-numeric characters and the same count)
2. RemoveDuplicates - Given String of alpha-numeric characters, return String of distinct characters
3. ReverseString - Given String, return String with characters in reverse order
4. ReplaceSpaces - Given String, replace all spaces with HTML '%20'
5. IsRotation - Return true if str2 is rotation of str1
6. ReverseStringInplace - Reverses a string inplace

###Math

1. PowersOfTwo - Compute 2^2^n in linear time
2. Swap Integers - Swap two integers in an array without using temporary variables
3. Sum Two Arrays - Write method to sum 2 arrays and return a new array. Arrays can be of different lengths. e.g. [1,3] + [1,0,0] == [1,1,3]
4. Smallest Number > k - Write method to find the smallest number which is greater than a given number k and has SAME SET OF DIGITS as given number

###Hash Tables

1. Open Addressing - Write a HashTable class that uses "linear probing" to resolve collisions (methods Get, Put, Remove)
2. Chaining - Write a HashTable class that uses LinkedLists to resolve collisions (methods Get, Put, Remove)
3. Dynamic Resizing - Add dynamic resizing to either above implementations

###Linked Lists

1. Double Linked List - Implement a Doubly Linked List
2. Remove Duplicates - Remove duplicates from an unsorted Single Linked List
3. Delete Node - Delete node in middle of Single Linked List given access to only that node
4. Is Circular - Return true if single linked list is circular (corrupted)
5. Circular Node - Find the first node in a circular single linked list
6. Sum Two Lists - Add two numbers together. Each number's digits are stored in a Single Linked List in reverse order (e.g. 134 == 4 --> 3 --> 1) ** also done in c++ ** 
7. Find Intersection of Two lists - Given two lists, find the node at which they intersect and become one list

###Recursion

1. Fibonacci - Write method to generate the nth fibonacci number
2. Robot Squares - Imagine a robot sitting on the upper left hand corner of an NxN grid. The robot can only move in 2 directions: right and down. How many possible paths are there for the robot?
3. String Permutations - Compute all permutations of a given string
4. Powerset - Return all possible subsets of a set (Recursive solution, Iterative, Bit Manipulation no loops)
5. PowersetM - Return all subsets of a set having M elements (Recursive, Iterative)
6. Valid Parentheses Pairs - Print all valid (e.g. properly opened and closed) combinations of n-pairs of parentheses. Input: 3, Output: ((())), (()()), (())(), ()(()), ()()()
7. Cents Combos - Given an infinite number of coins (25 cents, 10, 5, 1), return the number of possible ways of representing N cents.
8. Paint Fill - Implement the "paint fill" function one might see on an image editing program. Given a 2 dimensional matrix array of Colors, fill in the surrounding area until you hit a border or another filled-in square.

###Trees
1. Count Nodes at k distance - Given a binary tree, print the nodes k distance away from a target node
2. Implement Tree - That stores integers and has methods getParent(), setParent(), getChildren(), addChild(), removeChild(), getValue(), setValue()
3. Implement BinaryTree - That stores Strings with methods setParent, setValue, setLeftChild, setRightChild
4. Parse Tree Equation - Use BinaryTree to implement a mathematical equation parser. From equations list this, (3 + (4 * 5)), return a Binary tree that holds this equation
5. Tree Traversals - Write methods to print out root nodes using PreOrder, InOrder, and PostOrder algorithms
6. First Common Ancestor - Find the first common ancestor of two nodes in a binary tree. Avoid using additional data structures if possible. *** Java and CPP solutions
7. Min Height Tree - Given a sorted Array of Strings build the Binary Search Tree of minimal height.
8. Binary Search Tree - Implement a Binary Search Tree with methods Get(), Put(), and Delete()
9. Sub Tree of Binary Tree - Given two binary trees, S and T, determine if S is a subtree of T.
10. In Order Traversal of binary tree
11. Sum of 2 Nodes in BST- Given a binary search tree and an integer k, find two nodes whose values sum up to k.
12. Is Subtree - Assume you have two Binary Trees--t1 has millions of nodes and t2 has hundreds of nodes. Return true if t2 is a subtree of t1 (i.e. root of t2 is a node in t1)
13. Find_paths - Given a binary tree and an integer k, print all paths that sum up to k

###Stacks
1. Implement Stack - Push and Pop methods
2. Single Array - Implement 3 stacks using a single array
3. Set of Stacks - Consider a Stack of plates. If one stack gets too high, create a new stack of plates. Implement a special stack that holds these multiple stacks. When the first stack passes some threshold, the class creates a new stack and continues. Implement both Push and Pop methods.
4. Towers of Hanoi - 
5. Sort Stack - Write a method to sort a stack in ascending order using Push, Pop, Peek, and IsEmpty.

###Queues
1. Implement Queue - Enqueue and Dequeue methods
2. Queue With Stacks - Implement a queue using 2 Stacks

###Heaps
1. Binary Heap - Implement a Binary Heap of integers with methods - isEmpty(), getSize(), getMin(), deleteMin(), buildBinaryTreeFromList(), insertElement()
2. Binary Heap in CPP - ""

###Graphs
1. Implement a Directed Graph using the Adjacent List technique
2. BFS - Find the Vertex in a Graph that holds the key "E" using Breadth First Search.
3. DFS - Implement Recursive and Iterative versions of Depth-First Search, which visit and print out every Vertex in Graph