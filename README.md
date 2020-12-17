# Discrete_path_planning

This is one of the straight forward approaches out all the path planning algorithm

In discrete planning , we explicitly discretize the robot’s workspace into a connected graph, and apply a graph-search algorithm to calculate the best path. This procedure is very precise (in fact, the precision can be adjusted explicitly by changing how fine you choose to discretize the space) and very thorough, as it discretizes the complete workspace. 
Due to this nature, discrete planning can be very computationally expensive especially with more configuration space to be covered.

The following methods were implemented and discussed
1. Breadth First Search (BFS)
2. A* Search Algorithm
