Tingfeng Wan 917912728

Question 1&2:
Implemented DPS and BPS using the pseudocode given in lecture slides.

Question 3&4:
Since UFS is equivalent to A* with null heuristic, implementation of null heuristic is used for UFS.
A* implementation uses PriorityQueue, which uses the heuristic algorithm to track which node to pop from 
frontier. Since traversed path can no longer be tracked simultaneously, it is now also tracked in the 
PriorityQueue.

Question 5&6:
Added trivial function (getStartState and isGoalState), and used getSuccessors() from other search problem
to fill out getSuccessors for this problem. The heuristic algorithm estimate the distance to the closest
corner, then from that corner to closest other corners.

Question 7:
Uses the mazeDistance function to determine the heuristic. High time complexity, but less nodes are 
expanded. Consistency is guaranteed since mazeDistance returns a constant value.

Question 8:
Used code from BPS, but changed goalState to all food. Since BPS always check the closest position first,
the first goalState found will always be the closest food.