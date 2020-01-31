# roboticsLabAssignmentAndProject

to run the two projects use the following commands and directions

# to run the assignment 

1. insert the folder "robot_arm" into your catkin workspace
2. run on your command line > catkin_make
3. then run on the same directory the command > source devel/setup.bash
4. finally run > roslaunch robot_arm arm.launch

This contains a model design for a 3 link arm model with a gripper attached to it and plugin file that moves the joins 

# to Run the project

1. insert the folder "gazebo_robot" into your catkin workspace
2. run on your command line >> catkin_make
3. then run in the same directory the command >> source devel/setup.bash
4. finally run >> roslaunch gazebo_robot hello.launch

This project contains a model for a wheeled robot which incorporates Ray(laser) noise sensor and Camera sensor 
and a plugin which is used for moving the robot.

Nodes can be launched by following the above command
