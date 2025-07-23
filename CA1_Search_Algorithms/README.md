Artificial Intelligence - Computer Assignment 1
Solving the Chaos Warehouse Problem with Search Algorithms
This is the first assignment for the Artificial Intelligence course. The main goal of this project is to use informed and uninformed search algorithms to find an optimal solution for a simulated problem. This project emphasizes the implementation, comparison, and analysis of various search algorithms.

Project Description
In this problem, the character Mike Wazowski must move boxes of scream capsules to their designated destinations within a warehouse. The warehouse map includes walls, empty spaces, boxes (Bi), their destinations (Gi), and up to two pairs of portals (Pi). Mike can push the boxes, but only one at a time. Passing through a portal transports him to the other portal in the same direction. The objective is to find a sequence of moves to get all the boxes to their destinations.





Required Algorithms
The following algorithms must be implemented in this project:

Uninformed Search:

DFS (Depth-First Search) 

BFS (Breadth-First Search) 

IDS (Iterative Deepening Search) 

Informed Search:

A* (A-Star) with at least one appropriate heuristic function 

Weighted A* with at least one weight value (w) 

Input and Output Format
Input
The input is a text map representing the initial state of the warehouse. The characters in the map are as follows:


H: Mike's position 


Bi: Box number i 


Gi: Destination for box number i 


W: Wall 


Pi: Portal number i 


.: Empty space 

Two elements can be in the same location, separated by a 

/ (e.g., G1/H).

Output
The output should be a string of moves (U, D, L, R) and the number of states visited. For BFS and A* algorithms, the solution must be optimal (the shortest path). If no solution exists, the output should be 


No solution.

Provided Tools
A 

game.py file is provided, which includes a class for simulating the game, although its use is not mandatory. This class offers functions for managing the game state, moving the player, and accessing map information. Additionally, a 





gui.py file is available for graphical visualization of the game, which requires the raylib library to be installed.

Key Implementation Points

State Definition: A more efficient definition for a state should be used, rather than a simple representation of the entire map at each moment.


Heuristics: For the A* algorithm, at least two suitable heuristic functions (which can be improved versions of the Manhattan distance) must be designed and analyzed for admissibility and consistency.



Report: A comprehensive report must be submitted, including an analysis of the algorithms, a comparison of the heuristics, and tables of results (execution time, number of states visited).
