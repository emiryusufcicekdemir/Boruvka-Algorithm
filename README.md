# Boruvka-Algorithm

The Borůvka algorithm is a graph algorithm used to construct the minimum spanning tree. The algorithm was developed by Czech mathematician Otakar Borůvka in 1926.

The minimum cutter tree of a graph is a tree that contains all the nodes of the graph and the least costly connections between these nodes. The Borůvka algorithm uses an iterative approach to construct this tree. The basic logic of the algorithm is to divide the graph into small sub-segments and choose the edge with the minimum cost for each segment.

The Borůvka algorithm is especially effective on large graphs because many nodes are processed at each step and therefore easy to parallelize. However, it may be less effective on slower growing charts.

Besides the minimum cutter tree problem, the Borůvka algorithm is also used in solving various problems used in data compression, DNA sequencing and many other areas.

The runtime of the algorithm can be expressed as O(m log n) when the number of nodes of the graph is n and the number of edges is m. The best case is when the graph is fully concatenated, in which case the runtime of the algorithm will be O(m). The worst case is when all edges of the graph are independent of each other, and in this case the runtime of the algorithm will be O(m log n).

In the average case, the runtime of the algorithm can range from O(m log n) to O(m log^2 n).

The running time of Boruvka algorithm is limited by a lower bound of at least the number of edges and an upper bound of n^2. The lower limit, because it is necessary to at least examine all the edges. The upper bound is n^2 since at least one edge is selected in each iteration.

The running time of the Boruvka algorithm depends on the structure of the graph. If the graphs are connected, the algorithm can run very fast. However, if the graph has multiple connections, the performance of the algorithm may degrade. Therefore, the graph structure to which the algorithm will be applied should be considered.
