# ros_robot_localization_tutorial
The ROS robot_localization package: a no-hardware-required hands-on tutorial

放置4个乌龟，乌龟的颜色是随机的，根据路径的颜色区分不同乌龟
1. 对输入指令添加噪声的是红色轨迹乌龟（相当于imu添加噪声） odometry.cpp
2. 对位置添加噪声的是蓝色轨迹乌龟（相当于gps添加噪声）positioning_system.cpp
3. 滤波后的结果是绿色轨迹乌龟 transformation_visualization_node.cpp
4. 真实位置是淡紫色乌龟 来自于默认初始乌龟
