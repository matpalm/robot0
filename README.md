[ROS](http://www.ros.org/) meta package for the robot0 project.

contains `.launch` files for starting up the required set of nodes

* a [MotorHat node](https://github.com/matpalm/ros-motorhat-node) for controlling the 4 motors.
* a [hc-sr04 node](https://github.com/matpalm/ros-hc-sr04-node) for publishing readings from the three sonars.
* a [mpu6050 node](https://github.com/matpalm/ros-mpu6050-node) for publishing theonboard gyroscope / accelerometer.

```
roslaunch robot0 robot0.launch
```
