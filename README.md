# MICROMOUSE

## Introduction
MICROMOUSE is an autonomous robot designed for the International Micromouse Challenge 2022 at IIT Bombay. The challenge involves building a robot capable of rapidly navigating a labyrinth to reach the center in the shortest time possible.
A small autonomous bot called a Micromouse must navigate an unknown maze and locate the centre. The bot is judged by the time it takes to find the maze's centre. The bot that makes the fastest run from the start to the centre is declared the competition's winner. 

### Project Highlights
- **Techfest, IIT Bombay**
- **Duration:** Oct 2022 - Dec 2022


## Overview
Designed and built an autonomous bot with 18cm square cells set over a 16 x 16 grid, achieving the least traversal time to the goal in the maze-solving challenge.

## Technical Details
- Fabricated a custom PCB to boost the bot's performance through integrated electronics.
- Incorporated six sharp infrared (IR) sensors for superior data accuracy during maze exploration.
- Executed maze-solving algorithms, such as flood fill and wall-following, to determine the quickest and most efficient route to the maze's center.
- Implemented PID control for precise and smooth movement, optimizing the robot's path-finding capabilities.

The Micromouse model can be divided into two parts:

## I. HARDWARE-
The hardware is responsible for perceiving the environment and moving about the maze. The hardware components must be of manageable size. The different hardware components are: 

-Power

-Sensors

-Control Unit

-Drive train.

The power system consists of batteries and a voltage regulation system.
With the help of sensors, the Micromouse detects the walls and traverses the maze with proper alignment.
The drive train includes motors and motor drivers, which produce the robot's motion. 
Finally, the control unit controls each of the other three components. 

## Components

1. Sharp IR sensors / Ultrasonic sensors 

2. Motor drivers

3. N20 Motors with Encoders

4. Arduino Nano

5. Slim Fit wheels

6. 3-D printed chassis

7. Castor wheel

8. LIPO Batteries 

## II. SOFTWARE-
On the other hand, the software is responsible for navigating through the maze and sending control signals to the different hardware components. Our focus has been on the selection and development of algorithms for solving the complex maze since finding the maze's centre is the primary goal of the Micromouse. 
The algorithms that we analysed in detail are:
- Wall Following

- DepthFirst Search

- Flood-Fill

Wall-Following is a trivial algorithm that is usually unsuccessful if implemented for IITB Micromouse mazes.
 At the same time, Depth-First Search is an intuitive algorithm that proves ineffective due to wasted time searching the entire maze.
 As such, the Flood-Fill algorithm and its many variations result in the best searching techniques.

## Code Overview
The project utilizes Arduino Nano and two tires for a compact and speedy design.The code files consist of a wall-following algorithm and on ewit flood fill algorithm. For guaranteed finding of the goal, one must prefer flood fill algorithm. Wall folowing algorithm is successful only only in cases when the goal lies at one of the edges adjacent to the wall i.e on the outer most edges.

## Study Material
1.Maze solver bot using arduino: 

https://www.slideshare.net/GautamJagdhish/maze-solver-robot-using-arduino

2.Micromouse from scratch | Sensors and Motors | Piccola
https://medium.com/analytics-vidhya/mm-sensors-and-motors-7fa3a870db67


3.GITHUB 
https://github.com/Isuru-Dissanayake/piccola

4.Vidoes of the challenge 2021-22
https://youtube.com/playlist?list=PLAWsHzw_h0iiz1EQEvQ9neo4NVnsSTkIm


5.PID in detail
https://medium.com/@TowardInfinity/pid-for-line-follower-11deb3a1a643


