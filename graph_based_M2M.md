# Graph based M2M optimization in an IoT environment [4]

The number of sensors used by electronic devices is expected to grow by thousand times in the age of smart cities and autonomous driving. Hence, the communication and interaction between these devices is an important and active area of research.

A popular way of modelling this problem, is to consider every machine as a node, and model this as a graph problem (V, E), V is the set of vertices in the graph, and E is the set of edges/connections between any two vertices in the graph. In telecommunication networks, the ability to communicate with all termminal nodes is addressed by finding a subgraph with least cost, wihthin this whole graph, referred to as Minimum Spanning Tree approach.[1 - 3] But in Machine-2-Machine communication, modelling this as a Directed Acyclic Graph is being explored in this paper.

This paper attempts to map all the machines that communicate within a network as using the concept of isomorphic graphs. Two graphs are isomorphic, if their structure remains the same, even after renaming/reassigning the vertices of the graphs. In M2M communication, irrespective of the distance/position of the machine, the interacting machines can be modelled as an isomorphic graph.

The nodes are first sorted in topological order, and are visited in the same order. The process of finding a node involves calculating the area, sorting the area and labelling the nodes. The time complexity of this algorithm is $$ |V|log(|v|) $$. This paper also shows impressive experimental results, and can theoritically handle any number of devices that are communicating with one another. 


### References:
1. S. Pandey, M-S. Mup, M-H. C, and J W Hong, 2011. Towards Management of Machine to Machine Networks. Network operation and management symposium (APNOMS) 13 th Asia-Pacific, 1-7, September 21-23, (2011)
2. ETSI M2M functional architecture technical, report http://www.etsi.org/deliver/etsi_ts/102600_102699/102690/01.01.01_60/ts_102690v010101p.pdf
3. Paul A, YC Jiang, JF Wang, and JF Yang. 2012. Parallel Reconfigurable Computing-Based Mapping Algorithm for Motion Estimation in Advance Video Coding ACM Transaction on Embedded Computing Systems (TECS)Vol.11, Issue S2. (2012).
4. Paul, Anand. "Graph based M2M optimization in an IoT environment." Proceedings of the 2013 Research in Adaptive and Convergent Systems. ACM, 2013.
