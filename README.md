MazeRobot
=========

Arduino Uno Maze Solving Robot Algorithm
 * This is the code for the Arduino Uno Microcontroller
 * Input: the sensor array at the front of the vehicle
 * Outputs signals to the motors to control movement
 
 * Algorithm: "Left-Hand-on-Wall" Algorithm to solve maze (priorities of checking movements are Left, Straight, Right, Back)
 * Optimization: We use substituion with the list of moves anytime the robot went back in order to optimize the path. For example: Left, Back, Left becomes Straight 
 ![image](https://user-images.githubusercontent.com/53126149/61595052-efd96700-ac0f-11e9-90df-4e8e758c4fe0.png)


**NOTE: Sorry about the video it is too big to see here but you can download it
