# Robotics-assign
This Repo contains the tasks and research for Robotics Club
<br>ROS 2 (Robot Operating System 2) is an open-source robotics middleware framework.
<br>ROS splits the robot into small programs that communicate and run the robot smoothly.
<br>Each part of the robot becomes independent, reusable, and replaceable.
<br>Major Components of ROS2 are 
<h4><br>NODE:
<br>A node is a single executable program that performs one specific task.
<br>for Example:
<br>1.Camera node captures images
<br>2.Motor node  controls wheels
<br>A robot may run dozens of nodes at the same time.
<br>Nodes are important for :
<br>1.Easy debugging
<br>2.Parallel execution
<br>3.Team members can work independently 
<h4><br>TOPICS (Continuous Communication): </h4> 
Topics are used for continuous data flow.
Topics joins the flow of robot like a chain 
Publisher–Subscriber model:
One node publishes
Other nodes subscribe
SERVICES:  (Request–Response)
Service are used for:
1.Start/stop commands
2.Mode switching
3.Calibrations 
Serivices are used when:
You need one answer from the robot and need immediate response
