# A* pathfinding visualization

Search algorithms are one of the most important areas of Artificial Intelligence. They are usually approaches to solving problems for which we start from a given state, and by performing a series of different possible actions, we seek to reach a goal state. For example, when searching for the shortest path to go from an initial position to a final position, or when searching for the best sequence of actions to win a game. All these types of problems can be represented as a tree. Among them is the A* Search algorithm.

A* Search algorithm is one of the best and popular technique used in path-finding and graph traversals.
It combines the strenghts of a greedy search with the strenghts of a branch and bound search because it uses as additional information both: 
> how far is the agent from the goal
> how much has the agent travelled from the initial state

The overall context is when we start from an initial cell and want to reach a final cell. This problem can easily be represented considering a 2D-grid having several obstacles.
