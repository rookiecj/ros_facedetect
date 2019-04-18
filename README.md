# ros_facedetect

This is a simple face detect project based on OpenCV on ROS.


## build

```
$ cd catkin_ws
$ mkdir -p src
$ git clone https://github.com/rookiecj/ros_facedetect.git  src/ros_facedetect
```

## launch

$ source devel/setup.bash
$ roscore

facedetect node
```
$ rosrun rospy_facedetect ros_facedetect.py
```

facedetect listener node
```
$ rosrun rospy_facedetect ros_facedetect_listener.py
```

sound player node
```
$ rosrun ros_omxplayer ros_omxplayer
```

