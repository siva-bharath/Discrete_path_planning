## Problem Definition 
The purpose of this task is to find the shortest path for a robot moving inside a 5x6 map from start to goal position using A* path planning algorithms. 
The robot can only move in four directions: up, left, down, and right. 
At first, the problem is modeled using classes in C++ and later solve it with the mentioned graph search algorithm.

Given
Grid(5x6):
| C1  | C2 | C3  | C4 | C5  | C6 |
| ------------- | ------------- |------------- | ------------- |------------- | ------------- |
|0 |1 |0 | 0 |0 | 0 |

|0 |1 |0 | 0 |0 | 0 |
|0 |1 |0 | 0 | 0 | 0 |
|0 |1 |0 | 0 | 0 | 0 |
|0 |1 | 0 | 0 |0 |0 |
|0 |0 |0 |1 |1 | 0 |

Where 1's represent obstacles and 0's represent free space.

Robot Start position: 0,0
Robot Goal Position: 4,5

Direction of Movement: Up(-1,0) - left(0,-1) - down(1,0) - right(0,1)
The Direction of Movement vector is a collection of four different 2D vectors each of which enables you to move between grid cells in the map.

Movement Arrows: Up(^) - left(<) - down(v) - right(>)
The Movement Arrows vector store the robot actions, this vector will be used later in this lab to visualize the robot orientation at each grid cell on the shortest path.

Cost of Movement: 1
The Cost of Movement value indicates how much it cost to move from one cell to another. Here, the cost is equal for all possible movements.
