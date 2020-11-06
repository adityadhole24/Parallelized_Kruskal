Kruskal's algorithm is a well known greedy technique of finding the Minimum Spanning Tree (MST) of an undirected weighted connected graph.
However, the strictly ordered examination of the graph’s edges in order to decide whether they are part of the MST, prohibits the usage of well known parallel strategies. 
This project attempts to overcome the restrictions imposed by the inherently sequential nature of the algorithm, by using a Helper Threading (HT) scheme.
A speedup of upto 1.7 and 1.97 was achieved on dual-core and quad-core systems, vis-a-vis the sequential implementation.