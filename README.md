# C++ Implementation of the Traveling Salesperson Problem
CS 325 at Oregon State University


## Introduction ##

The problem: Given a set of cities and known distances between each pair of cities, find a tour in which each city is visited exactly once and the distance travelled is minimized. 


## Implementation ##

Uses Christofides’ algorithm to construct a tour and the 2-opt algorithm to improve it


## Requirements ##

Input specification: A problem instance (a particular input) will always be given to you as a text file. Each line defines a city and each line has three numbers separated by a white space. The first number is the city identifier, the second number is the city’s x-coordinate and the third number is the city’s y-coordinate.

Output specification: You must output your solution into another text file with n +1 lines where n is the number of cities. The first line is to be the length of your tour you find. The next n lines should contain the city identifiers in the order they are visited by your tour. Each city must be listed exactly once in this list. This is the certificate for your solution and your solutions will be checked. If they are not valid, you will not receive credit for them (verification is much easier than proving this problem).
