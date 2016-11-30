## Graphs [Back](./../data_structure.md)

The study of networks has become one of the great scientific hotbeds (熱點) of this century, though mathematicians and others have been studying networks for many hundreds of years.

In this chapter, we'll look at how networks are modeled with graphs in JavaScript.

### Graphs Definitions

A graph consists of a set of **vertices** (頂點) and **edges**, which mainly consists of two kinds: A **digrapth** (directed graph) and an **unordered graph**.

A graph whose pairs are ordered is called a directed graph (*Figure 1*), or just a digraph.

<p align="center">
    <img src="./a_digraph.png" title="diagraph" alt="diagraph" />
</p>

<p align="center">
    <strong>Figure 1</strong> A diagraph (directed graph)
</p>

A graph, which is not ordered, is called an unordered graph (*Figure 2*), or just a graph.

<p align="center">
    <img src="./an_unordered_graph.png" title="unordered graph" alt="unordered graph" />
</p>

<p align="center">
    <strong>Figure 2</strong> An unordered graph
</p>

A **path** is a sequence of vertices in a graph such that all vertices in the path are connected by edges. The **length** of a path is the number of edges from the first vertex in the path to the last vertex. A path can also consist of a vertex to itself, which is called a **loop**. Loops have a length of 0. 

A **cycle** is a path with at least one edge whose first and last vertices are the same. A simple cycle is one with no repeated edges or vertices for both directed and undirected graphs. Paths that repeat other vertices besides the first and last vertices are called **general cycles**. 

Two vertices are considered **strongly** connected (強連接) if there is a path from the first vertex to the second vertex, and vice versa (反之亦然). If the graph is a directed graph, and all its vertices are strongly connected, then the directed graph is considered strongly connected.
