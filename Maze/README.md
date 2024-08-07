# Reeborg's World - Maze

## Overview

This project involves solving a maze using the Reeborg's World platform. The solution is implemented in Python, and the goal is to guide Reeborg, the robot, through the maze to reach the final destination.

## Maze Link

You can access the maze on the Reeborg's World platform using the following link:
[Maze Link](https://reeborg.ca/reeborg.html?lang=en&mode=python&menu=worlds%2Fmenus%2Freeborg_intro_en.json&name=Maze&url=worlds%2Ftutorial_en%2Fmaze1.json)

## Instructions

1. Open the maze link provided above.
2. Copy the Python code provided below.
3. Paste the code into the editor on the Reeborg's World platform.
4. Run the code to solve the maze.

## Sample Code

```python
def turn_right():
    turn_left()
    turn_left()
    turn_left()
  
while at_goal() != True:
    if right_is_clear():
        turn_right()
        move()
    elif front_is_clear():
        move()
    else:
        turn_left()
'''