# Jackal_VO
Jackal Gazebo Simulator for Visual Inertial Odometry

Based on Jackal robot by Clearpath Robotics: https://github.com/jackal/

To spawn Jackal:
```
#!command

roslaunch jackal_vo jackal_vo.launch
```

To move Jackal:
```
#!command

rosrun key_teleop key_teleop.py key_vel:=cmd_vel
```
