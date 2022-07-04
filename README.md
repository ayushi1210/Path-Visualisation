# Path-Visualisation
It finds the shortest path between two points using **A<sup>*</sup> Search Algorithm**

## About A* Search Algorithm
One of the best and most widely used methods for pathfinding and graph traversals is the **A<sup>*</sup> Search Algorithm**<br/>
Assume that we are given a beginning cell and a target cell in a square grid with numerous obstacles. If at all feasible, we want to go as rapidly from the starting cell to the target cell.<br/>
The **A<sup>*</sup> Search Algorithm** selects the node at each stage based on a value, **f**, which is a parameter equal to the sum of two additional factors, **g** and **h**. It chooses the node or cell with the lowest **f** at each step and processes that node or cell.<br/>
Here,<br/>
**g** is the cost in movement to move along the created path from the beginning point to a specific square on the grid.<br/>
**h** is the calculated cost of moving from a specific grid square to the target position. Due to the possibility of obstructions, we truly can't tell the distance until we find the path (walls, water, etc.). 


### Initial Map
<img width="801" alt="Screenshot 2022-07-04 at 2 21 40 PM" src="https://user-images.githubusercontent.com/93306058/177123952-31b727be-7791-4bb4-a283-7888baab9fc8.png">

### Shortest Path using A* algorithm
<img width="798" alt="Screenshot 2022-07-04 at 2 46 50 PM" src="https://user-images.githubusercontent.com/93306058/177123958-a286fe02-f934-41a2-b5a2-4e346677111e.png">
