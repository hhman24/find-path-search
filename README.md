# Finding path by search algorithm
Research and implement the searching algorithm. In addition, students have to visualize the result of the searching algorithm

## Problem

- Problem description:
    - Maze of size M x N, and the robot has to find the path 
from the Source (starting position) to the Goal (ending position)
    - `Breadth-first search`
    - `Uniform-cost search`
    - `Interative deepening search`
    - `Greedy-best first search`
    - `Graph-search A*`


- Input/output format:
    - Input:
        - First line: the size of the maze width, height
        - Second line: the position of the Source and Goal. For example: 2 2 19 16 meaning source point is (2, 2) and goal point is (19, 16).
        - Third line: the number of the obstacles in the maze
        - The next following line, defining the obstacle by the rule
            - The obstacle is a Convex polygon
            - A polygon is a set of points that are next to each other clockwise. The last point will be implicitly concatenated to the first point to form a valid convex polygon
    
    - Output:
        - Graphical representation of polygons
        - Graphical representation of expanded node
        - Graphical representation of final path
        - Cost of expanded node (total number of expanded nodes)
        - Cost of final path (total number of nodes in the final path)
