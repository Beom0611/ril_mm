# Robotics Intelligence Lab, Mobile Manipulation Robot (RIL_MMR)
 
## Overview
The UR5 with Robotiq Gripper85 and Husky mobile manipulation robot tutorial will show you how to operate a mobile manipulation robot using Gazebo, RViz, MoveIt


**Author**   
- **Sangbeom Park, [github]:https://github.com/Beom0611**  

## Before start the tutorial, please check your ROS version, this pakage for ROS Melodic version


## Let's start it!

- For RIL_MMR
[UR5+Robotiq Gripper85+Husky Model](https://github.com/Beom0611/ril_mmr.git)  
```
$ cd ~/catkin_ws/src && git clone
$ cd ~/catkin_ws/src && catkin_make
$ sudo rosdep init
$ rosdep update
$ rosdep install --from-paths src --ignore-src -r -y
```

## Sample code for beginner 
- Spawning RIL_MMR on Gazebo and Rviz 
- 
$ rosrun ril_mmr_gazebo ril_mmr_empty_world.launch 

- Moving RIL_MMR to the goal point  
$ rosrun ril_mmr_python husky_point.py 

- Contorlloing the RIL_MMR' arm and gripper    
$ rosrun ril_mmr_python joint_test1.py 
```

## Description


## Demo
