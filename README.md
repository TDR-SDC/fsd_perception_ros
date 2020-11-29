# TDR-SDC's Perception Stack

Welcome to the TDR-SDC Formula Student perception repo

## Bulding code
```bash
mkdir -p catkin_ws/src
cd catkin_ws/src
git clone https://github.com/TDR-SDC/fsd_perception
cd ..
catkin_make
```
### Run Gazebo and ROS simulation
Run the following command:
```bash
roslaunch simulation simulation.launch
```
### Run LIDAR processing node 
Run the following command:
```bash
rosrun pointcloudprocessing final.py
```