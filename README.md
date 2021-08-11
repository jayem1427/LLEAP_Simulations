# LLEAP_Simulations

This repository is for ROS-based Exo-skeleton simulations developed by Cal Poly's LLEAP. 

Controlling the hip assembly:

1) roslaunch the gazebo file within /hip_assembly
2) roslaunch the controller file within /hip_control
3) use the format "rostopic pub -1 /hip_assembly/hip_revolute_joint_position_controller/command std_msgs/Float64 INSERT_NUM_HERE" to control the hip. Change the INSERT_NUM_HERE value to a position in radians.