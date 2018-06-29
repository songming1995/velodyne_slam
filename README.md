<!--![Screenshot](/capture.bmp)-->
<!--Sample map built from [nsh_indoor_outdoor.bag](http://www.frc.ri.cmu.edu/~jizhang03/Datasets/nsh_indoor_outdoor.bag) (opened with [ccViewer](http://www.danielgm.net/cc/))-->

<!--:white_check_mark: Tested with ROS Indigo and Velodyne VLP16. [(Screencast)](https://youtu.be/o1cLXY-Es54)-->

# Using 3D Lidar to do Simultaneous Localization and Mapping (SLAM)

This repository is modified from previous work of [ROS Loam Velodyne](http://wiki.ros.org/loam_velodyne)

All sources were taken from [ROS documentation](http://docs.ros.org/indigo/api/loam_velodyne/html/files.html)

<!--Ask questions [here](https://github.com/laboshinl/loam_velodyne/issues/3). -->

## Build with catkin:

* Clone the repository:

```
$ cd ~/catkin_ws/src/
$ git clone https://github.com/xlab905/velodyne_slam.git
$ cd ~/catkin_ws
$ catkin_make -DCMAKE_BUILD_TYPE=Release
$ source ~/catkin_ws/devel/setup.bash
```

* In the terminal, run:
```
roslaunch loam_velodyne sdc_project.launch
```

Remember to check the velodyne configuration to modify the parameters in sdc_project.launch. The bag file will automatically played but paused at first, press <kbd>Space</kbd> to play it.

