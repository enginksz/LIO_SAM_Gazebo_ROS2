# LIO SAM Gazebo ROS2 
LIO SAM Gazebo ROS2 

git clone https://github.com/TixiaoShan/LIO-SAM.git

cd lio-sam

git checkout ros2

cd ..

colcon build

# Run the package

Run the launch file:

source lio_sam_gazebo_ros2/install/setup.bash

## terminal 1 
ros2 launch lio_sam run.launch.py

## terminal 2 
ros2 launch robot_gazebo robot_sim.launch.py

