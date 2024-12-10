# experimental_assignment_1
The project was developed using ROS2 humble therefore if you use foxy the launch file will probably have to be modified in line number 34 of the `gazebo.launch.py`, by replacing it with ```executable="spawner.py",```  
## How to run ##
In order to run the assignment after cloning the repository and moving the two repositories `robot_urdf` and `ros2_aruco` into the ros2 workspace. Then you need to open three terminals, moving to ROS2 workspace and run the commands in the following order (one for each terminal) 
1) `ros2 launch robot_urdf gazebo.launch.py`   
2) `ros2 run ros2_aruco aruco_node`
3) `ros2 run ros2_aruco marker_subscriber` or `camera_marker_subscriber`  

In addition to publishing the image on the custom topic as requested, it is also shown directly
