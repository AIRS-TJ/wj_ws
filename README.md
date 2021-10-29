# 1. 准备

moveit安装教程参考：
http://docs.ros.org/en/melodic/api/moveit_tutorials/html/doc/getting_started/getting_started.html


# 2. 编译

	$ cd ~

	$ git clone https://github.com/AIRS-TJ/wj_ws.git

	$ cd wj_ws/

	$ catkin_make

	$ source devel/setup.bash 

# 3. 运行

运行机器人模型

	$ roslaunch snake_robot demo.launch

运行snake_robot机器人的moveit

	$ roslaunch snake_robot_moveit_config demo.launch rviz_tutorial:=true

运行snake_robot2机器人的moveit

	$ roslaunch snake_robot2_moveit_config demo.launch rviz_tutorial:=true

# MoveIt 设置

参考：http://docs.ros.org/en/melodic/api/moveit_tutorials/html/doc/setup_assistant/setup_assistant_tutorial.html

	$ roslaunch moveit_setup_assistant setup_assistant.launch

# gazebo

	$ roslaunch snake_robot2 gazebo.launch 


