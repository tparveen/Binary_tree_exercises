### Searching and Tree Traversal Exercises
For each of these exercises be sure to talk to you pairs and understand the problem and figure out the right approach to solve the problem.

### Exercise 1
Given the following dataset

89 30 25 32 72 70 51 42 25 24 53
55 78 50 13 40 48 32 26 2 14
33 45 72 56 44 21 88 27 68 15
93 98 73 28 16 46 87 28 65 38
67 16 85 63 23 69 64 91 9 70
81 27 97 82 6 88 3 7 46 13
11 64 31 26 38 28 13 17 69 90
1 6 7 64 43 9 73 80 98 46
27 22 87 49 83 6 39 42 51 54
84 34 53 78 40 14 5 76 62

Write a function to find a particular value in the unsorted list.

### Exercise 2
Use the dataset from the previous exercise for this exercise. Use array.sort to sort the dataset. Then implement Binary search to find a particular value in the dataset.

### Exercise 3
Imagine you are looking for a book in a library with a Dewey Decimal index. How would you go about it? Can you express this process as a searching algorithm?

### Exercise 4
Use paper and pen for this part of the exercise.

What is the output for an in-order traversal through the following binary tree
[Binary tree](tree1.png)

What is the output for a post-order traversal through the following binary tree
[Binary tree](tree2.png)

What is the output for a Pre-order traversal through the following binary tree
[Binary tree](tree3.png)

### Exercise 5
Implement a Binary tree and its insertion function. Then implement in-order, pre-order, and post-order functions. Insert the following data in your binary tree - 

25 15 50 10 24 35 70 4 12 18 31 44 66 90 22

Check your answers:

A Pre-order traversal should give you the following order:
25, 15, 10, 4, 12, 22, 18, 24, 50, 35, 31, 44, 70, 66, 90

InOrder:
4, 10, 12, 15, 18, 22, 24, 25, 31, 35, 44, 50, 66, 70, 90

Post-order:
4, 12, 10, 18, 24, 22, 15, 31, 44, 35, 66, 90, 70, 50, 25

### Exercise 6
The share price for a company over a week's trading is as follows: [128, 97, 121, 123, 98, 97, 105]. If you had to buy shares in the company on one day, and sell the shares on one of the following days, write an algorithm to work out what the maximum profit you could make would be.

### Exercise 7 - This is func exercise to do - make this an optional one after you are done with all the exercises above
Imagine that you wanted to find what the highest floor of a 100 story building you could drop an egg was, without the egg breaking. But you only have two eggs. Write an algorithm to work out which floors you should drop the eggs from to find this out in the most efficient way.
