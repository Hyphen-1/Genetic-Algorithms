# Genetic-Algorithms

Write a program using a Genetic Algorithm to solve the delivery problem below:
The Delivery Problem:
A Delivery company has a set of boxes to deliver. Each box has a value and a weight. It has one delivery vehicle.
You are given a capacity c, which is the maximum total weight that can be transported and a quota q, which is the
minimum total value v that you want to carry at any one time. The problem is to find a subset of the objects whose
total weight w is at most equal to the capacity (w ≤ c) and whose total value is at least equal to the quota v ≥ q.
For example, given these three objects:
Object Weight Value
A 70 80
B 50 50
C 50 50
and a capacity of 110 and a quota of 90, then a solution to the problem is the set {B, C}. Note that there is no
solution involving object A, because once you have loaded A, you cannot load any of the other two. (You are not
allowed to choose a fraction of an object.)
The program should take its input from an input file that will contain a number of problems in sequence. Each
problem has the following format.
• First line: ***
• Second line: Capacity.
• Third line: Quota.
• Fourth line: Number of objects
• Remaining lines: 1 line per object. Name, weight, and value, separated by blanks.
There can be any number of blank lines separating problems.You may assume that:
• There are at most 20 objects.
• A name is a single alphabetical character.
• All quotas, capacities, weights, and values are integers.
An input file containing one example will have the following form:
***
100
400
9
A 70 260
B 60 245
C 50 200
D 40 100
E 30 80
F 20 65
G 10 60
H 10 60
I 1 10
