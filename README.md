# Task-3

## 1. Prerequisites
### 1.1 **Ubuntu** and **ROS**
Ubuntu 64-bit 18.04.

ROS Melodic. [ROS Installation](http://wiki.ros.org/ROS/Installation)

### 2.2. **ROS Package**
```
sudo apt-get install ros-melodic-hector-trajectory-server ros-melodic-slam-gmapping ros-melodic-navigation
```

## 3. Build 
### 3.1 Clone repository:
```
    cd ~/catkin_ws/src
    git clone https://github.com/wh200720041/warehouse_navigation.git
    cd ..
    catkin_make
    source ~/catkin_ws/devel/setup.bash
```

### 3.2 Launch ROS
```
    roslaunch warehouse_simulation warehouse_simulation.launch
```
Note that it takes a few minutes to load model upon first launch

### 3.3 Robot Control
You can use keyboard (arrow keys) to manually control the robot (select cmd window first)

### 3.4 Autonomous Navigation
You may set target points in RVIZ and the robot will navigate to the location in gazebo.
1. click 2d nav goal button on rviz
2. click any points you want on the map

### resourse 
https://github.com/Amg0z/Task-4

https://github.com/Amg0z/warehouse_simulation_toolkit#33-robot-control






![Screenshot from 2021-07-02 15-19-15](https://user-images.githubusercontent.com/54133895/127747795-d24b59ed-a724-484a-b61f-41f1792a95d0.png)
