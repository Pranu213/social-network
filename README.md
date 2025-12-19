# social-network
Graph-based social network analysis system built in C++ to model synthetic friendship networks. Implements BFS, DFS, and Union-Find for connectivity analysis, centrality measures (degree, betweenness, PageRank) for influence detection, and a recommendation engine using mutual connections and community structure.

how to run code :
1. you can use already existing datasets by running : python3 main.py < g1.txt
2. Or can generate a new input graph by doing :
   1. python3 gen.py
   2. A new input.txt is created, add last 2 lines according to your choice from menu (yes/no ; 1-6 options)
   3. options for visualisation and what visualisation are needed.
   4. then run python3 main.py < input.txt
