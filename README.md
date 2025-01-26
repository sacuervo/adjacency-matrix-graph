# Adjacency Matrix Graph Creation Process

## Overview
- This process describes how to represent an unweighted-undirected graph as an adjacency matrix

## GraphNode Class
1. Create GraphNode class
2. Add graph node name and index as instance attributes
3. Create the GraphNode constructor with name and index as parameters

## Graph Class
1. Create Graph class
2. Add a GraphNode list (variable-size graph) or array (fixed-size graph) as instance attribute
3. Add an Adjacency Matrix two-dimensional array as instance attribute
4. Create a constructor with the GraphNode list as parameter. Initialize the adjacency matrix with the graph node list length (it's a square matrix).
5. Create a method to add an undirected vertex that has the GraphNode indices as parameters
6. Create a method to print the adjacency matrix

## Main
1. Declare a GraphNode array (fixed-size graph) or list (variable-size graph)
2. Instantiate the Graph class
3. Add the edges using the Graph class method
4. Print the resulting adjacency matrix using the Graph method
