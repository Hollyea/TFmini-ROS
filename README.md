TFmini working in ROS 

# TFminiROS

quick start commands
create folder 'catkin_ws'
$cd catkin_ws
create folder  'src'，put the tfmini ROS package in
back to folder /catkin_ws 

$ catkin_make
$source devel/setup.bash 
$sudo chmod 666 /dev/ttyUSB1  /*Notes: need to keep the same as the 'tfmini.launch'/
$ roslaunch tfmini_ros tfmini.launch

$rostopic list 
$rostopic echo /tfmini_ros_node/TFmini


 

also can use 'rviz' to view 

$rostopic list 
$rviz


Notes: 
Fixed frame 
Range Topic
choose the 'TFmini'

