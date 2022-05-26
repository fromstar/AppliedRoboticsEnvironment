# Project of Apply robotics laboratory 
In this course the student will be introduced to a complete methodology for designing modern robot applications. The target applications will be those for which system intelligence plays a prominent role, first and foremost planning, task optimisation and perception. The student activities will revolve around a motivational application proposed in the form of a simple robotic competition, in which the robot has to complete a number of tasks in minimum time avoiding obstacles and dangerous spots. Contrary to a standard robotic competition, the student will have to discuss the theoretical underpinning of the method she/he chose to adopt for the competition. 

## Project objectives
- development and implementation of sensing algorithms to recognise objects and obstacles in the competition field
- development and implementation of motion planning algorithms to move the robot from an initial to a final position in minimum time avoiding obstacles
- development and implementation of intelligent planning algorithms to decide the optimal game strategy
- testing of the solution in simulation and on the field

## Prerequisites/Dependencies
* Linux 16.04
* Gazebo >= 7.16
* ROS Kinetic
* make >= 4.1
* gcc/g++ >= 5.4
* Boost Libraries
* Fast Forward Planner

## Installation

Just execute the "install_lab.sh" script. It will install ROS, Gazebo, the planner and all the necessary dependecies.

## Run the project
Open terminator and split it in 3 terminals. Move in workspace/project/build folder and use the command "make" to compile the project.
In a terminal use the command "AR_simulator_gui" (or "AR_simulator" if you don't want the gui) to start the simulator. In the second terminal use "AR_pipeline" to start the pipeline. If it is necessary to specify the number of robots present, it must be done both at the start of the simulator and the pipeline with the option "n:=NumberOfRobots" (Ex. AR_simulator_gui n:=2, AR_pipeline n:=2). In the last terminal type AR_run to execute the program.
