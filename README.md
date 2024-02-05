# launch_file
How to write a launch file for a robot to visualise it 


# First we start by running the robot state publisher node.

![running_robot_state_publisher](https://github.com/kmlingaudhaya/launch_file/assets/134930329/ce51ea36-e065-41e8-b3bc-fb2e343985c9)

This is a general purpose node developed to publish the urdf model of any robot published to a certain ros2 topic

# Next we start the joint_state_publisher_gui node dispaly the gui controls of the movable joints.



This node starts the graphical user interface to control all the corresponding movable joints in our robot
