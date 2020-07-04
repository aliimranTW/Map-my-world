# Map-my-world

The goal of the project is implement SLAM on a robot which has been deployed in an unknown area. The robot is equipped with an RGB camera and a LIDAR. 
Use the following lines of code to start the simulation:

```
cd catkin_ws
source devel/setup.bash
roslaunch my_robot mapping.launch
```
This code should open a gazebo world with a robot deployed. Moreover, it should open an RVIZ window showing real-time parameter values.
After generating the map, the resultant maps and features can be explored and analyzed in detail using the RTAB mapping. Use the following lines of code to open a new RTAB window:

```
rtabmap-databaseViewer ~/.ros/rtabmap.db
```
To view the relavant information, go to **view** and enable **Constaint View** and **Graph View**.
