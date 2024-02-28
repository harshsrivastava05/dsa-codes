A Graph Data Structure is a collection of nodes connected by edges. It’s used to represent relationships between different entities. Graph algorithms are methods used to manipulate and analyze graphs, solving various problems like finding the shortest path or detecting cycles.

Components of a Graph

Vertices: Vertices are the fundamental units of the graph. Sometimes, vertices are also known as vertex or nodes. Every node/vertex can be labeled or unlabelled.

Edges: Edges are drawn or used to connect two nodes of the graph. It can be ordered pair of nodes in a directed graph. Edges can connect any two nodes in any possible way. There are no rules. Sometimes, edges are also known as arcs. Every edge can be labelled/unlabelled.

![image](https://github.com/harshsrivastava05/dsa-codes/assets/130855160/20cfd22b-e705-45be-8785-a7ffaab1ff98)

Types Of Graph

1. Null Graph: 
A graph is known as a null graph if there are no edges in the graph.

2. Trivial Graph: 
Graph having only a single vertex, it is also the smallest graph possible.

![image](https://github.com/harshsrivastava05/dsa-codes/assets/130855160/cea4c6fa-16a4-43a1-b187-c5ab5c6ef387)

3. Undirected Graph: 
A graph in which edges do not have any direction. That is the nodes are unordered pairs in the definition of every edge. 

4. Directed Graph: 
A graph in which edge has direction. That is the nodes are ordered pairs in the definition of every edge.

![image](https://github.com/harshsrivastava05/dsa-codes/assets/130855160/0d5b4325-f810-427c-ac2d-eae8c3880799)

5. Connected Graph: 
The graph in which from one node we can visit any other node in the graph is known as a connected graph. 

6. Disconnected Graph: 
The graph in which at least one node is not reachable from a node is known as a disconnected graph.

![image](https://github.com/harshsrivastava05/dsa-codes/assets/130855160/3ad1c8d2-531b-47fa-af46-5dc6939cc94b)

7. Regular Graph: 
The graph in which the degree of every vertex is equal to K is called K regular graph.

8. Complete Graph: 
The graph in which from each node there is an edge to each other node.

![image](https://github.com/harshsrivastava05/dsa-codes/assets/130855160/08d338bd-e390-488b-b060-3d1c97fb709a)

Representation of Graphs
There are two ways to store a graph:

1. Adjacency Matrix

2. Adjacency List

Adjacency Matrix:
In this method, the graph is stored in the form of the 2D matrix where rows and columns denote vertices. Each entry in the matrix represents the weight of the edge between those vertices. 

![image](https://github.com/harshsrivastava05/dsa-codes/assets/130855160/d0c6a158-b1d6-4094-a3e1-2c56bf728087)

Adjacency List: 
This graph is represented as a collection of linked lists. There is an array of pointer which points to the edges connected to that vertex. 

![image](https://github.com/harshsrivastava05/dsa-codes/assets/130855160/320f15bd-b70e-4774-b5b8-3daf173bc466)



