# ROS2_Sample_Robot
[![x86 Build Status](https://github.com/frcteam195/ROS2_Sample_Robot/actions/workflows/main.yml/badge.svg)](https://github.com/frcteam195/ROS2_Sample_Robot/actions/workflows/main.yml)

This is the main robot project. All nodes used in the robot should be defined in ros_projects.txt and all third party libraries should be defined in third_party_projects.txt. In order to run this project, you need to have [ros_dev](https://github.com/frcteam195/ros_dev) at the same directory level as this repository. Then you can run `./ros_dev/mkrobot.sh clone` to pull all the node and third party libraries and then run `./ros_dev/mkrobot.sh build` to build all the nodes. To deploy to the ROS robot, run `./ros_dev/mkrobot.sh deploy`. The naming standard for nodes is `[nameofnode]_[year]_node`.


---

### Robot Nodes

[ros2](git@gitlab.team195.com:cyberknights/ros2/robots/sample_robot/ck_ros2_msgs_node.git)

[ros2](git@gitlab.team195.com:cyberknights/ros2/robots/sample_robot/dashboard_interface_node.git)

[ros2](git@gitlab.team195.com:cyberknights/ros2/robots/sample_robot/drivetrain_node.git)

[ros2](git@gitlab.team195.com:cyberknights/ros2/robots/sample_robot/health_monitor_node.git)

[ros2](git@gitlab.team195.com:cyberknights/ros2/robots/sample_robot/hmi_agent_node.git)

[ros2](git@gitlab.team195.com:cyberknights/ros2/utility-nodes/ck_ros2_base_msgs_node.git)

[ros2](git@gitlab.team195.com:cyberknights/ros2/utility-nodes/ck_utilities_node.git)

[ros2](git@gitlab.team195.com:cyberknights/ros2/utility-nodes/ck_utilities_py_node.git)

[ros2](git@gitlab.team195.com:cyberknights/ros2/utility-nodes/frc_robot_utilities_node.git)

[ros2](git@gitlab.team195.com:cyberknights/ros2/utility-nodes/frc_robot_utilities_py_node.git)

[ros2](git@gitlab.team195.com:cyberknights/ros2/utility-nodes/logger_node.git)

[ros2](git@gitlab.team195.com:cyberknights/ros2/utility-nodes/phoenixpro_control_node.git)

[ros2](git@gitlab.team195.com:cyberknights/ros2/utility-nodes/rio_control_node.git)

[ros2](git@gitlab.team195.com:cyberknights/ros2/utility-nodes/swerve_drivetrain_node.git)



---

### Third Party Projects

[ROS2_ProtoDef](https://github.com/frcteam195/ROS2_ProtoDef.git)

