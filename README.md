# simulation_test
Package to test ROS_control in Gazebo simulator

1. Spawn the robot model in gazebo using spawn.launch
2. Spawn the state_controller using bot_control.launch

- Parameters for controller are given inside config folder in controller_params.yaml

for keyop:
install dependency: sudo apt-get install ros-melodic-teleop-twist-keyboard
run: rosrun teleop_twist_keyboard teleop_twist_keyboard.py
teleop_twist_keyboard package documentation: http://wiki.ros.org/teleop_twist_keyboard
