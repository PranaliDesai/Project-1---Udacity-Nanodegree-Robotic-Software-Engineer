# Project-1---Udacity-Nanodegree-Robotic-Software-Engineer

To build - 

```
cd /location_of_the_project/Project1
mkdir build
cd build/
cmake ../
make # You might get errors if your system is not up to date!
export export GAZEBO_PLUGIN_PATH=${GAZEBO_PLUGIN_PATH}:/location_of_the_project/Project1/build

```
To run -

```
cd /location_of_the_project/Project1/world/
gazebo world_project1.world
```

