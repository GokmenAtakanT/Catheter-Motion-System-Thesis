# Catheter-Motion-System-Thesis

Project command

1 roscore

2 roslaunch dynamixel_workbench_controllers dynamixel_controllers_current2.launch

3 rosrun rosserial_python serial_node.py /dev/ttyACM0

4 rosrun dynamixel_workbench_controllers step.py

5 rosrun dynamixel_workbench_controllers smc3_5_new.py 

6 python catheter_motion_control2.py
