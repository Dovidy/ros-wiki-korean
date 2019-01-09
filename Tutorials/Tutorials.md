= ROS Tutorials =
'''Non-Beginners''': If you're already familiar enough with `ROS` [[fuerte]] or earlier versions and only want to explore the new build system introduced in [[groovy]] and used in [[hydro]] and later, called [[catkin]], you can go through more in-depth [[catkin/Tutorials|catkin tutorial here]]. However, going over all basic [[#Beginner_Level|Beginner Level]] tutorials is still recommended for all users to get exposed to new features.

'''If you are new to Linux''': You may find it helpful to first do a quick tutorial on common command line tools for linux.  A good one is [[http://www.ee.surrey.ac.uk/Teaching/Unix/|here]].

<<TableOfContents(3)>>

== Core ROS Tutorials ==
=== Beginner Level ===
<<TutorialChain(ROS/Tutorials/InstallingandConfiguringROSEnvironment)>>

'''Now that you have completed the beginner level tutorials please answer this short [[http://spreadsheets.google.com/viewform?formkey=dGJVOVhyXzd0b0YxRHAxWDdIZmo4cGc6MA|questionnaire]].'''

=== Intermediate Level ===
More client API tutorials can be found in the relevant package ([[roscpp/Tutorials|roscpp]], [[rospy/Tutorials|rospy]], [[roslisp/Tutorials|roslisp]])

<<TutorialChain(ROS/Tutorials/Creating a Package by Hand)>>

== ROS Standards ==
 * [[DevelopersGuide|ROS Developers Guide]] Guidelines for coding style, package layout and much more
 * [[http://www.ros.org/reps/rep-0103.html|Standard Units of Measure and Coordinate Conventions]]

== Tutorials for Other ROS Libraries ==
 * [[robot_model_tutorials|Robot Model]]
 * [[visualization/Tutorials|Visualization]]
 * [[actionlib_tutorials/Tutorials|actionlib]]
 * [[pluginlib/Tutorials|Pluginlib]]
 * [[nodelet/Tutorials|Nodelets]]
 * [[navigation/Tutorials|Navigation]]
 * [[Industrial/Tutorials|ROS-Industrial Tutorials]]
 * [[dynamixel_controllers/Tutorials|Dynamixel Tutorials]]

== Tutorials for Libraries with ROS Interfaces ==
 * [[stage/Tutorials|Stage]]
 * [[tf/Tutorials|TF]]
 * [[pcl/Tutorials|PCL with ROS]]

== External ROS Resources ==
=== External Tutorials ===
 * [[https://goo.gl/U8op5X|ROS Online Courses Library]]
 * [[https://goo.gl/ZfWwkc|ROS Weekly LIVE-Class]]
 * [[https://www.udemy.com/ros-basics-program-robots/|Udemy Course on ROS: Video tutorials on learning to program robots from scratch]]
 * [[https://goo.gl/Nav9Vh|Online ROS Tutorials:Learn ROS by programming online simulated robots]]
 * [[https://goo.gl/fk2DNU|ROS Q&A Videos Tutorials]]
 * [[http://www.youtube.com/playlist?list=PLDC89965A56E6A8D6|ROS Tutorial Video Demos at ANU]]
 * [[http://nootrix.com/category/robotics/robots-software/|NooTriX Step-by-Step ROS Tutorials]]
 * [[http://support.clearpathrobotics.com|Clearpath Robotics' knowledge base]]
 * [[https://www.youtube.com/watch?v=d5YAJh6Z2B0&list=PL39WpgKDjDfVfiNVG47DBi93wsh2XHKVO|Erle Robotics - Learning ROS]]
 * [[http://ros-industrial.github.io/industrial_training|ROS-Industrial Training Class Curriculum]]
 * [[http://jbohren.com/tutorials/|Jonathan Bohren's ROS Tutorials]]
 * [[https://www.allaboutcircuits.com/technical-articles/an-introduction-to-robot-operating-system-ros/|An Introduction to Robot Operating System (ROS)]]
 * [[https://atadiat.com/ar/articles/programming-robot-operating-system-introduction/|Programming Robots Using ROS: An introduction]] (Arabic Language)
 * [[https://husarion.com/tutorials/ros-tutorials/1-ros-introduction/|Learn ROS using a URDF simulation model from basics through SLAM - by Husarion]]

=== External Seminar/Lecture ===
 * [[https://www.meetup.com/meetup-group-GLGBcAgn/|ROS Meetup]] by [[http://www.theconstructsim.com/|The Construct]]
 * [[http://opensource-robotics.tokyo.jp/?p=355&lang=en|Free introductory seminar for enterprises]] by [[http://opensource-robotics.tokyo.jp|TORK]] in Tokyo

== Using ROS on your custom Robot ==
 * [[https://goo.gl/C4ZLA5|Bringing ROS to real life: Barista]] The first robot serving coffee to the tables in the world
 * [[urdf/Tutorials|Create your own URDF file]] Creating a custom Universal Robot Description Format file
 * [[ros_control]] Use ROS's standard controller framework for interfacing with hardware.
 * [[http://gazebosim.org/tutorials?tut=ros_urdf&cat=connect_ros|Using a URDF in Gazebo]] Add the necessary tags to get your robot in the Gazebo robotic simulator
 * [[http://docs.ros.org/kinetic/api/moveit_tutorials/html/doc/setup_assistant/setup_assistant_tutorial.html|Setting up MoveIt!]] Creating the configuration package to use the [[moveit|MoveIt!]] Motion Planning Framework