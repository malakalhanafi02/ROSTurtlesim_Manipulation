# Manipulate with Turtlesim Package in ROS1 Noetic:

1. Install Turtlesim Package:
```bash
sudo apt update
sudo apt install ros-noetic-turtlesim
```

2. Run Turtlesim Node:
```bash
roscore
```
3. Open a new terminal and run:
```bash
rosrun turtlesim turtlesim_node
```
4. Run Turtlesim Teleop Node:
Open another terminal and run:
```bash
rosrun turtlesim turtle_teleop_key
```
<img width="496" alt="image" src="https://github.com/malakalhanafi02/ROSTurtlesim_Manipulation/assets/122760944/1f8a4149-73e0-401a-9ea8-7baea919c1eb">

# Manipulate with Turtlesim Package in ROS2 Foxy

1. Install Turtlesim Package:
```bash
sudo apt update
sudo apt install ros-foxy-turtlesim
```
2. Run Turtlesim Node:
```bash
source /opt/ros/foxy/setup.bash
ros2 run turtlesim turtlesim_node
```
3. Run Turtlesim Teleop Node:
Open another terminal and run:
```bash
source /opt/ros/foxy/setup.bash
ros2 run turtlesim turtle_teleop_key
```
<img width="495" alt="image" src="https://github.com/malakalhanafi02/ROSTurtlesim_Manipulation/assets/122760944/d513a64d-1eb6-4716-b769-4bf7798f296c">


