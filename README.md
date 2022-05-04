## ELAS - Cyphy

ROS packages containing a wrapper for libelas, a stereo matching library. 

用了openmp加速，好像就快那么一丢丢

Most of this code is the original work of Patrick Ross <<patrick.ross@connect.qut.edu.au>>, Andreas Geiger <<geiger@kit.edu>>, Ben Upcroft <<ben.upcroft@qut.edu.au>>, and David Ball <<david.ball@qut.edu.au>>; see http://www.ros.org/wiki/cyphy_elas_ros for more information.

The original repository that this was forked from no longer exists, so I'll do my best to maintain this one.  Thanks to [@nicolapiccinelli](https://github.com/nicolapiccinelli), [@comkieffer](https://github.com/comkieffer), and [@heimsi](https://github.com/heimsi) for their help in bringing this package up to date.

### Installation Instructions

To install the package, clone this repository into your workspace:

```
cd catkin_ws/src
git clone git@github.com:jeffdelmerico/cyphy-elas-ros.git
```

Then build the `libelas` and `elas_ros` packages:

```
catkin_make
```

An example launch file is provided in 
```
elas_ros/launch/elas.launch
```

说实话效果就那样，还是得上个深度学习