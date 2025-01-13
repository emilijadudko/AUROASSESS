# AUROASSESS
# this document will include instructions on how to run the solution code

to run the solution, first ensure youre in the directory (within terminal) of the downloaded file
cd ~/auro_ws
then colcon build using:
colcon build --symlink-install && source install/local_setup.bash
finally to run:
ros2 launch solution solution_launch.py

everything should run after that
