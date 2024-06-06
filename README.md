# Graphs in C++

Welcome to your comprehensive guide to Graphs in C++! This repository equips you with a solid understanding of graph concepts, representations, algorithms, and provides practice problems from LeetCode and GeeksforGeeks to solidify your knowledge.

# Sections:

## Introduction : 

Define Graphs: Non-linear data structures consisting of vertices (nodes) connected by edges (links).

Explain their applications in various domains (modeling networks, social relationships, routing algorithms, etc.).

## Graph Representations :

Explore different ways to represent graphs in C++:

Adjacency Matrix: Two-dimensional array where rows and columns represent vertices, and values indicate edge presence/weight. (Efficient for dense graphs, but memory-intensive for sparse graphs)

Adjacency List: Array of linked lists, where each linked list stores vertices connected to a specific vertex. (Efficient for sparse graphs, may require extra traversal overhead)

Implement code examples for both representations, including methods to add/remove vertices and edges.

## Graph Traversal Algorithms :

Discuss fundamental graph traversal algorithms:

Depth-First Search (DFS): Explores as far as possible along a chosen branch before backtracking. (Useful for finding connected components, detecting cycles)

Breadth-First Search (BFS): Explores all neighboring nodes at the current level before moving to the next level. (Efficient for finding shortest paths, level-order traversal)

Provide code examples for both DFS and BFS algorithms (recursive and iterative approaches).

Consider including visualizations of traversal paths (using diagrams or ASCII art).

## Shortest Path Algorithms :

Explore two common shortest path algorithms:

Dijkstra's Algorithm: Finds the shortest path from a source vertex to all other vertices in a weighted graph (useful for network routing).

Briefly mention other algorithms like Bellman-Ford (handles negative edges) if applicable.

Implement code examples for Dijkstra's algorithm.

Minimum Spanning Tree Algorithms

Explore algorithms to find the minimum spanning tree (MST) of a weighted graph:

Prim's Algorithm: Similar to Dijkstra's but focuses on finding the minimum-cost edge connecting a new vertex to the existing tree.

Kruskal's Algorithm: Sorts edges by weight and keeps adding edges that don't create cycles, ensuring a minimum-cost spanning tree.

Implement code examples for Prim's or Kruskal's algorithm.

# Practice Problems : 

A categorized list of LeetCode and GeeksforGeeks problems on Graphs:

## Easy :
Graph and Types (https://bit.ly/3gpY19t)

Graph Representation | C++ (https://bit.ly/3dGuwyv)

Graph Representation | Java (https://bit.ly/3dGuwyv)

Connected Components | Logic Explanation (https://leetcode.com/problems/number-of-connected-components-in-an-undirected-graph/)

BFS (https://practice.geeksforgeeks.org/problems/bfs-traversal-of-graph/1)

DFS (https://practice.geeksforgeeks.org/problems/depth-first-traversal-for-a-graph/1)

## Problems on BFS/DFS :

Number of provinces (leetcode) (https://leetcode.com/problems/number-of-provinces/#:~:text=A%20province%20is%20a%20group,the%20total%20number%20of%20provinces.)

Connected Components Problem in Matrix (https://bit.ly/3AxzhDG)

Rotten Oranges (https://leetcode.com/problems/rotting-oranges/)

Flood fill (https://leetcode.com/problems/flood-fill/)

Cycle Detection in unirected Graph (bfs) (https://practice.geeksforgeeks.org/problems/detect-cycle-in-an-undirected-graph/)

Cycle Detection in undirected Graph (dfs) (https://practice.geeksforgeeks.org/problems/detect-cycle-in-an-undirected-graph/)

0/1 Matrix (Bfs Problem) (https://leetcode.com/problems/01-matrix/)

Surrounded Regions (dfs) (https://leetcode.com/problems/surrounded-regions/)

Number of Enclaves [flood fill implementation - multisource] (https://leetcode.com/problems/number-of-enclaves/)

Word ladder - 1 (https://leetcode.com/problems/word-ladder/)

Word ladder - 2 (https://leetcode.com/problems/word-ladder-ii/)

Number of Distinct Islands [dfs multisource] (https://leetcode.com/problems/number-of-distinct-islands-ii/)
 
Bipartite Graph (DFS) (https://leetcode.com/problems/is-graph-bipartite/)

Cycle Detection in Directed Graph (DFS) (https://leetcode.com/problems/course-schedule-ii/discuss/293048/detecting-cycle-in-directed-graph-problem)

## Topo sort and problems :

Topo Sort (https://practice.geeksforgeeks.org/problems/topological-sort/1)

Kahn's Algorithm (https://bit.ly/3c690mm)

Cycle Detection in Directed Graph (BFS) (https://practice.geeksforgeeks.org/problems/detect-cycle-in-a-directed-graph/1)

Course Schedule - I (https://leetcode.com/problems/course-schedule/)

Course Schedule - II (https://leetcode.com/problems/course-schedule-ii/)

Find eventual safe states (https://leetcode.com/problems/find-eventual-safe-states/)

Alien dictionary (https://leetcode.com/problems/alien-dictionary/solution/)

## Shortest Path Algorithms and Problems :

Shortest Path in UG with unit weights (https://bit.ly/3UVQD4C)

Shortest Path in DAG (https://bit.ly/3Eo1mhq)

Djisktra's Algorithm (https://practice.geeksforgeeks.org/problems/implementing-dijkstra-set-1-adjacency-matrix/1)

Why priority Queue is used in Djisktra's Algorithm (https://bit.ly/3Et6alk)

Shortest path in a binary maze (https://leetcode.com/problems/shortest-path-in-binary-matrix/)

Path with minimum effort (https://leetcode.com/problems/path-with-minimum-effort/)

Cheapest flights within k stops (https://leetcode.com/problems/cheapest-flights-within-k-stops/)

Network Delay time (https://leetcode.com/problems/network-delay-time/)

Number of ways to arrive at destination (https://leetcode.com/problems/number-of-ways-to-arrive-at-destination/)

Minimum steps to reach end from start by performing multiplication and mod operations with array elements (https://bit.ly/3QAEsrY)

Bellman Ford Algorithm (https://practice.geeksforgeeks.org/problems/distance-from-the-source-bellman-ford-algorithm/1)

Floyd Warshal Algorithm (https://practice.geeksforgeeks.org/problems/implementing-floyd-warshall2042/1)

Find the city with the smallest number of neighbors in a threshold distance (https://leetcode.com/problems/find-the-city-with-the-smallest-number-of-neighbors-at-a-threshold-distance/)

## Minimum Spanning Tree / Disjoint Set and Problems :

Minimum Spanning Tree (https://practice.geeksforgeeks.org/problems/minimum-spanning-tree/1)

Prim's Algorithm (https://practice.geeksforgeeks.org/problems/minimum-spanning-tree/1)

Disjoint Set [Union by Rank] (https://bit.ly/3QSGvHz)

Disjoint Set [Union by Size] (https://bit.ly/3QSGvHz)

Kruskal's Algorithm (https://practice.geeksforgeeks.org/problems/minimum-spanning-tree/1)

Number of operations to make network connected (https://leetcode.com/problems/number-of-operations-to-make-network-connected/)

Most stones removed with same rows or columns (https://leetcode.com/problems/most-stones-removed-with-same-row-or-column/)

Accounts merge (https://leetcode.com/problems/accounts-merge/)

Number of island II (https://leetcode.com/problems/number-of-islands-ii/)

Making a Large Island (https://leetcode.com/problems/making-a-large-island/)

Swim in rising water (https://leetcode.com/problems/swim-in-rising-water/)
 
## Other Algorithms : 

Bridges in Graph (https://leetcode.com/problems/critical-connections-in-a-network/discuss/382385/find-bridges-in-a-graph)

Articulation Point (https://bit.ly/3T2LPKu)

Kosaraju's Algorithm (https://bit.ly/3TbvByL)
