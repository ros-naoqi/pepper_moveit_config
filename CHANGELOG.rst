^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^
Changelog for package pepper_moveit_config
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

0.0.7 (2016-12-21)
------------------
* fix allowed_execution_duration_scaling
* fixing the robot visualization
* changing the type of virtual_odom
* fixing both arms
* adding wheels as passive joints
* Contributors: Natalia Lyubova

0.0.6 (2016-09-18)
------------------
* updating Octomap config to make compatible with pepper_sensors_py
* Update README.rst
* Merge pull request `#6 <https://github.com/ros-naoqi/pepper_moveit_config/issues/6>`_ from 130s/impr/default_safe_planner
  Use RRT as default.
* Use RRT as default.
* Contributors: Isaac I.Y. Saito, Natalia Lyubova

0.0.5 (2016-07-05)
------------------
* removing the broken moveit_ros_visualization dependence
* adding disabled self-collisions and cleaning
* Merge pull request `#5 <https://github.com/ros-naoqi/pepper_moveit_config/issues/5>`_ from nlyubova/master
  updating the tutorial
* updating the tutorial
* Merge pull request `#4 <https://github.com/ros-naoqi/pepper_moveit_config/issues/4>`_ from nlyubova/master
  cleaning and launch file rename
* renaming demo_real.launch to moveit_planner.launch to keep the same naming convention as for Nao
* cleaning
* Contributors: Mikael Arguedas, Natalia Lyubova, nlyubova

0.0.4 (2016-02-03)
------------------
* remove pepper_meshes from dependency because license not displayed on buildfarm
* Contributors: Mikael Arguedas

0.0.3 (2016-02-03)
------------------
* update dependency list
* fixing controllers names
* Merge pull request `#3 <https://github.com/ros-naoqi/pepper_moveit_config/issues/3>`_ from 130s/add/botharms
  Add botharms MoveGroup and a simple unit test
* Merge pull request `#2 <https://github.com/ros-naoqi/pepper_moveit_config/issues/2>`_ from 130s/selectable_moveitconfig
  Accept .rviz file as an argument
* Add the simplest unit test
* Allow no RViz gui mode
* Add both_arms Move Group
* Accept .rviz file as an argument
* Merge pull request `#1 <https://github.com/ros-naoqi/pepper_moveit_config/issues/1>`_ from keulYSMB/master
  added the version argument and use xacro command instead of one globa…
* added the version argument and use xacro command instead of one global URDF file to allow different configurations
* fixing the repository path
* fixing kinematics params
* Contributors: Isaac I.Y. Saito, Mikael Arguedas, Natalia Lyubova, nlyubova

0.0.2 (2015-10-22)
------------------
* Creating moveit config
* Contributors: nlyubova
