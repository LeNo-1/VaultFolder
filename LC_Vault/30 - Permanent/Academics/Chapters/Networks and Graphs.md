- **Graph Theory** is a branch of mathematics which is used to model, analyse and solve many real-life problems , and is very useful in problem-solving and mathematical modelling. In Graph Theory a graph has a wider meaning than the usual meaning we take, where we plot a series of points with two perpendicular axes

- DEF: A _graph_ consists of points (known as **vertices**  or __nodes__) which are connected by lines (known as **edges** or __arcs__ )
		Example graph:
		- 

>*Isomorphic* are graphs that have exactly the **same structure** of vertices and edges, but **labelling may be different** 

- Def. : The *degree* ( or __valency__ or __order__ ) of a a vertex is the number of edges incident to it
- *Handshaking Lemma:* In any graph the **sum of the degrees** will be precisely equal to **2 times the number of edges**

- Def. : A _subgraph_ pf any graph G is any graph, each of whose edges and vertices belong to graph G. It is simply part of the original graph G
- Def. : A _diagraph_ ( or **directed graph** ) is a graph where each of the edges has a **direction associated** with them
- Def. : A *loop* is an edge that **starts and finishes at the same vertex**

- Def. : A graph is a *simple graph* if:
	- It does **not contain any loops**
	- There is no more than **one edge joining any pair of vertices**

- Def. : A graph is *connected* if there is a **path connecting all the vertices** on the graph. A graph is *disconnected* if there are any **vertices on the graph between which there is no path**.
- Def. : A _tree_ is a connected graph with **no cycles**
- Def. : A _spanning tree_ of a graph G is any subgraph of G which includes all the vertices of G and is also a tree
#### Types of routes
- A _walk_ is a route through a graph, from one vertex to another, in which you are permitted to visit each vertex any number of times
	
- A _path_ is a route through a graph, from one vertex to another, in which you are only permitted to visit any vertex once
	
- A _cycle_ is a closed path, where the start and finish vertex of the path are the same, but no other vertex is visited more than once on the path

- Def. : A _tree_ is a connected graph with **no cycles**
- Def. : A _spanning tree_ of a graph G is any subgraph of G which includes all the vertices of G and is also a tree

## Algorithms
### Prim's
- ###### Graph Form
	1. Start at Any Vertex
		- Choose any vertex as the starting point.
		- Select the edge of least weight that is connected to this vertex
	2. Grow the Tree
		- From the set of vertices already included in the tree, choose the edge of least weight that connects to a vertex not yet in the tree.
	    - Ensure that the edge does not create a cycle (i.e., do not connect two vertices already in the tree)[
	
	3. Repeat
		- Continue selecting the lowest-weight edge that connects a vertex in the tree to a vertex outside the tree.
		- Repeat until all vertices are included in the tree
	
	4. Record the Order
		- Keep track of the order in which edges are added to the MST

- ###### Matrix From
	1. Select a Starting Vertex
		- Choose any vertex to start from.
		- Cross out the column for this vertex in the matrix.
		- Label the corresponding row with ‘1’
    
	
	2. Find the Minimum
		- Circle the lowest value in the labelled row (this represents the shortest edge from the current tree).
		- Add this edge to the tree.
		- Cross out the column of the vertex just added.
    
	3. Update Labels
	- Label the row of the newly added vertex with the next number.
	
	4. Repeat
		- Circle the lowest value in any labelled row.
		- Add the corresponding edge to the tree and cross out the relevant column.
		- Continue until all vertices are labelled and included in the tree.

### Dijkstra's
- ###### Graph Form
	
- ###### Matrix Form
	