# Ford-Fulkerson-Algorithm-Python

Ford-Fulkerson algorithm is a greedy approach for calculating the maximum possible flow in a Network or a graph.

A term, Flow network, is used to describe a network of vertices and edges with a Source (S) and a Sink (T) node. Each vertex, except S and T, can receive and send an equal amount of stuff through it. S can only send and T can only receive stuff.

We can visualize the understanding of the algorithm using a flow of liquid inside a network of pipes of different capacities. Each pipe has a certain capacity of liquid it can transfer at an instance. For this algorithm, we are going to find how much liquid can be flowed from the source to the sink at an instance using the network.

![image](https://user-images.githubusercontent.com/22562694/120909751-e1768600-c695-11eb-9dcb-b2123a016ceb.png)

Fig. 1: Flow Network graph

Terminologies Used:

1.Augmenting Path: It is the path available in a flow network.

2.Residual Graph: It represents the flow network that has additional possible flow.

3.Residual Capacity: It is the capacity of the edge after subtracting the flow from the maximum capacity.

How Ford-Fulkerson Algorithm works?

The algorithm follows:

1.Initialize the flow in all the edges to 0.

2.While there is an augmenting path between the source and the sink, add this path to the flow.

3.Update the residual graph.

Note: We can also consider reverse-path if required because if we do not consider them, we may never find a maximum flow.

Ford-Fulkerson Applications are: 

1.Water distribution pipeline

2.Bipartite matching problem

3.Circulation with demands
