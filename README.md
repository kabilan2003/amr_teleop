# amr_teleop

mkdir catkin_ws


cd catkin_ws


mkdir src


cd src



catkin_init_workspace

cd ..


catkin_make


git clone https://github.com/kabilan2003/amr_teleop.git




roslaunch AMR_description gazebo.launch

It will run the gazebo simulation


roslaunch AMR_description display.launch

It will run Rviz software



rosrun teleop_twist_keyboard  teleop_twist_keyboard.py 

for running teleoperation 
