# Differntial Drive Robot

This is a simple differential robot to experiment in ROS 2 humble and Gazebo Fortress. The code coppied from [artibot_one](https://github.com/joshnewans/articubot_one) prepared by Josh Newmans.

## How to explore the simulation
Install dependencies:
```
sudo apt-get update
sudo apt-get install ros-humble-twist-stamper
sudo apt-get install ros-humble-twist-mux
sudo apt-get install ros-humble-ros-gz-image
```

Compile the package:

```
mkdir -p my_articubot_one/src
cd my_articubot_one/src
git clone https://github.com/captain-bender/my_articubot_one.git
cd ..
colcon build --symlink-install
source install/setup.bash 
```

Start the simulation:
```
ros2 launch articubot_one launch_sim.launch.py
```
