GRAPHS

Try the following problems :
Prime Path
Prayatna PR
Any Ideas ?

Def : Think graphs as a relation between node , related nodes are connected via edge.

How to store a graph ? ( space complexity )

Adjacency Matrix ( useful in dense graph) using 2-D array of bool/ints.
Adjacency List (useful in sparse graph) O(min(deg(v),deg(u))) using vector of ints.
You must know the following terminologies regarding Graphs :

Neighbours
Node
Edge
Degree of vertices
Directed Graph
Connected Graph
Undirected Graph
Connected components
Articulation Points
Articulation Bridges
Tree [[ connected graph with N nodes and N-1 edges]]

Leaves
Children
Parent
Ancestor
Rooted Tree
Binary Tree
K-ary Tree
Cycle in graph

Path
Walk
Directed Acyclic Graph [[ DAG ]]

Topological Sorting (Not very important, in my opinion)
Bipartite Graph ( Tree is an example of Bipartite Graph . Interesting Isn’t it.)

Breadth First Search/Traversal (BFS) [[ very important, master it as soon as possible]]

Application : Shortest path in unweighted graphs
Depth First Search/Traversal (DFS) [[very very important, master it as soon as possible]]

Infinitely many applications, just kidding :P (But Its true, Indeed !)
Now try the problems given at the beginning !

Practice Problems :
http://www.codechef.com/JUNE14/problems/DIGJUMP  </br>
http://www.spoj.com/problems/PRATA/ </br>
http://www.spoj.com/problems/ONEZERO/ </br>
http://www.spoj.com/problems/PPATH/ </br>
http://www.spoj.com/problems/PARADOX/ </br>
http://www.spoj.com/problems/HERDING/ </br>
http://www.spoj.com/problems/PT07Z/ </br>
http://www.spoj.com/problems/NICEBTRE/ </br>
http://www.spoj.com/problems/CERC07K/ </br>
http://www.spoj.com/problems/BUGLIFE/ </br>
http://www.spoj.com/problems/COMCB/ </br>
http://www.spoj.com/problems/NAKANJ/ </br>
http://www.codechef.com/IOPC2013/problems/IOPC13N/ </br>
http://www.codechef.com/IOPC2013/problems/IOPC13G/ </br>
http://www.codechef.com/IOPC2013/problems/IOPC13C </br>
Problem : You are given a Graph. Find the number of connected components in the Graph.

Hint : DFS or BFS.

Problem : You are given a grid with few cells blocked and others open. You are given a cell , call is source, and another cell , call it dest. You can move from some cell u to some another cell v if cell v is open and it is adjacent to cell u. You have to find the shortest path from source to dest.  

Hint : Try to think the grid as a Graph and apply some shortest path algorithm. Which one ? You think !

Problem : You are given a Tree. You need to find two vertices u and v such that distance between them maximum. [[http://www.spoj.com/problems/PT07Z/]]

Hint : Try to do it in O(1) number of DFS or BFS !
