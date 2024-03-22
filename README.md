This project intends to build a robot capable follow a wall. The robot follows the wall by its left side.
(Images are in portuguese)

![image](https://github.com/FelipMa/wall-follower-robot/assets/105306441/45e38f54-507b-41ba-855c-54b33b86cee6)

![image](https://github.com/FelipMa/wall-follower-robot/assets/105306441/c3b2173c-2ba4-46a2-95ed-3c7550de625a)

In part a) of fig. 1, the robot world is a matrix of cells, in which each component is free (white cells) or occupied by a wall (dark cells).

The robot, shown as a triangle, is placed in any free cell, respecting one of the directions parallel to the matrix grid (horizontal or vertical), with its front facing any of the 4 possible directions (North, South, East or West).

The robot has 2 binary sensors: head (sensor located in front of the robot, which returns 1 when the cell located in front of the robot is occupied by a wall – otherwise, it returns 0) and left (sensor located on the left side of the robot, which returns 1 when the cell on the left side
left of the robot is occupied by a wall - otherwise returns 0).

Regarding movement, the robot is capable of only 2 types of movement: moving forward a free cell in front of you or rotate 90o to the left, staying in the same cell as which is found. Each movement consumes 1 clock pulse.
