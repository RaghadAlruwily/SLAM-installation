# SLAM-installation
how to install SLAM approach :
first of all, you must have ROS system on your ubuntu before install SLAM approach 


( here, you can see how i did download ROS system on ubuntu 16.04)
https://github.com/RaghadAlruwily/Ros-Installation

(or from this link)
https://emanual.robotis.com/docs/en/platform/turtlebot3/quick-start/

after installated ROS now you have to install SLAM approach .. firstly , open terminal in ubuntu :
put the following instruction :
- sudo apt-get install ros-kinetic-joy ros-kinetic-teleop-twist-joy \
  ros-kinetic-teleop-twist-keyboard ros-kinetic-laser-proc \
  ros-kinetic-rgbd-launch ros-kinetic-depthimage-to-laserscan \
  ros-kinetic-rosserial-arduino ros-kinetic-rosserial-python \
  ros-kinetic-rosserial-server ros-kinetic-rosserial-client \
  ros-kinetic-rosserial-msgs ros-kinetic-amcl ros-kinetic-map-server \
  ros-kinetic-move-base ros-kinetic-urdf ros-kinetic-xacro \
  ros-kinetic-compressed-image-transport ros-kinetic-rqt* \
  ros-kinetic-gmapping ros-kinetic-navigation ros-kinetic-interactive-markers
  
  - and then to install turtlebot3 packages :
  
  - sudo apt-get install ros-kinetic-dynamixel-sdk
  - sudo apt-get install ros-kinetic-turtlebot3-msgs
  - sudo apt-get install ros-kinetic-turtlebot3
  
Run Navigation Nodes :

  - roscore
  - export TURTLEBOT3_MODEL=burger
  
  to launch turtlebot3 :
  - roslaunch turtlebot3_navigation turtlebot3_navigation.launch map_file:=$HOME/map.yaml



 ![turtlebot3](https://user-images.githubusercontent.com/100563503/183825964-be171be3-0e91-4017-b2a2-9f6cfb60f86c.png)
