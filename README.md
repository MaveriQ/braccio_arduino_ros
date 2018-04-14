# braccio_arduino_ros

Heavily inspired by https://github.com/ohlr/braccio_arduino_ros_rviz. With some major restructuring of the code, it's essentially the same project.

## Steps to Run the Code. (Under Construction/Incomplete)

1. Upload braccio_ros.ino found in src/braccio_ros to Arduino
2. Terminal 1: roscore
3. Terminal 2: rosrun braccio parse_and_publish
4. Terminal 3: roslaunch braccio braccio.urdf
5. Terminal 4: rosrun rosserial_python
6. Terminal 5: rostopic echo joint_state

Use gui slider on RVIZ to move the joints. 
