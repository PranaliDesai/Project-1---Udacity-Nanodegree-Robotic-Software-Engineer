# Project-1---Udacity-Nanodegree-Robotic-Software-Engineer

To build - 

'''
cd /location_of_the_project/Project1
mkdir build
cd build/
cmake ../
make # You might get errors if your system is not up to date!
export GAZEBO_PLUGIN_PATH=${GAZEBO_PLUGIN_PATH}:/home/workspace/Project1/build
'''
To run -

'''
cd /location_of_the_project/Project1/world/
gazebo project1_world.world
'''

