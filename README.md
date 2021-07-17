# Arduino Setup
## Board Installations

Install the following boards

## ESP8266

### Board Installation
  ```
  $ sudo apt-get install ros-kinetic-universal-robot
  ```
### Libraries
* Tets


## ESP32

### Board Installation
  ```
  $ sudo apt-get install ros-kinetic-universal-robot
  ```
### Libraries
* Tets

  
  


### Final Environment Layout (Due to computer hardware issues):




## How to use this repository
- This project was developed and tested in [Ubuntu 16.04 LTS (Xenial Xerus)](https://releases.ubuntu.com/16.04/) with `ROS Kinetic`.
- Make sure you have installed [Python2.7](https://www.python.org/download/releases/2.7/) and the required packages & libraries listed below:

Install Universal Robots ROS Packages:
  ```
  $ sudo apt-get install ros-kinetic-universal-robot
  ```
Install Universal Robots ROS Drivers:
  ```
  $ git clone https://github.com/UniversalRobots/Universal_Robots_ROS_Driver.git universal_robots_ros_driver
  $ git clone -b calibration_devel https://github.com/fmauch/universal_robot.git universal_robot
  ```
