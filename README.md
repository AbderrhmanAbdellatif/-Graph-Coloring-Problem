# Graph Coloring Problem
Graph Coloring (or Vertex Coloring) problem is defined as assignment of smallest number of colors to the vertices of an undirected graph, such that no adjacent vertices are of the same color. A coloring using at most k colors is called a (proper) k-coloring. The smallest number of colors needed to color a graph G is called its chromatic number and is often denoted χ(G). The goal is to color all vertices of the graph, such that number of colors used (k) is as close as possible to the optimal result, i.e. χ(G). Since this problem is NP-Hard, it is very difficult to find the optimal solution especially for large instances.

Project Specification:
You are asked to design and implement an algorithm for Graph Coloring problem described above. Your goal is not to design an algorithm for the optimal solution, but you are requested to do your best. This is an open-ended assignment.

Input format: Inputs will always be given as a text file. Input file format should be as follows: The first line is the problem line which indicates the number of vertices and the number of edges. It starts with “p”, and there is only one such line.
p <NumVertices> <NumEdges>
The rest of the lines are edge lines. Each line starts with “e” and indicates an edge between
two vertices.
e <VertexNumber1> <VertexNumber2>
The above line means that there is an edge between VertexNumber1 and VertexNumber2.
Here is a sample graph:  


Algorithms Step 
Assign colors to all vertices such that no adjacent vertices have the same color and print the assigned colors.
1) First add an edge and form a graph by adding different vertices. 
2)Assign the first color to the first vertex
3)A temporary array to store the available colors.
4)True value of available[cr] would mean that the
5)Color cr is assigned to one of its adjacent vertices 
6)Assign colors to the remaining V-1 vertices
7)Process all adjacent vertices and flag their colors as unavailable 
8)Find the first available color
9)Assign the found color
10)Reset the values back to false for the next iteration 
11) Print the result

We run the code by first ad
1) First add an edge and form a graph by adding different vertices.
 2)Assign the first color to the first vertex
3)A temporary array to store the available colors.
4)True value of available[cr] would mean that the
5)Color cr is assigned to one of its adjacent vertices 
 values back to false for the next iteration
