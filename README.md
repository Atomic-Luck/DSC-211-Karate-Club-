# DSC-211-Karate-Club-Assignment
This project applies Newman’s Recursive Spectral Bisection method to detect communities in the well-known Zachary’s Karate Club network. The algorithm repeatedly splits the graph into communities based on the leading eigenvector of the modularity matrix, revealing meaningful structure in the network. The Zachary Karate Club graph is a classic social network of 34 members, representing friendships in a karate club that eventually split into two factions. Nodes = members, Edges = social ties

References
1. Newman, M. E. J. (2006). Modularity and community structure in networks. PNAS, 103(23), 8577–8582.
2. Zachary, W. W. (1977). An information flow model for conflict and fission in small groups.

Dependencies
1. networkx
2. numpy
3. scipy
4. matplotlib

A) Community Detection Results
The algorithm prints:
1. Leading eigenvalues per split
2. ΔQ (modularity gain)
3. Nodes in each group
4. Final set of communities

B) Visualizations
The notebook generates:
1. Graph plot for each iteration, showing how the network is split
2. Final colored community structure
3. Centrality metric plots across iterations (degree, betweenness, closeness, clustering)

C) Analysis
Observations include:
1. Nodes 0 and 33 consistently remain the most central
2. Community structure is strongly aligned with known factions
3. Centrality values remain stable across splits, confirming inherent structure
