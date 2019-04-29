This project merged into oroca/iTurtle.

# ros_facedetect

This is a simple face detect ROS project based on OpenCV.

## build

```
$ cd catkin_ws
$ mkdir -p src
$ git clone https://github.com/rookiecj/ros_facedetect.git  src/ros_facedetect
$ catkin_make && catkin_make install
```

## launch

```
$ source install/setup.bash
$ roscore
```

facedetect node
```
$ rosrun rospy_facedetect ros_facedetect.py
```

facedetect listener node
```
$ rosrun rospy_facedetect ros_facedetect_listener.py
```

for playing sound via ros_omxplayer
```
$ rosrun ros_omxplayer ros_omxplayer
```

