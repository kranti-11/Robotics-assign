# Robotics-assign
This Repo contains the tasks and research assigned by Robotics Club particulary for programming domain.It contains research of two topics and tasks assigned.
<br><h4> ROS 2 </h4>
<br>ROS 2 (Robot Operating System 2) is an open-source robotics middleware framework.
<br>ROS splits the robot into small programs that communicate and run the robot smoothly.
<br>Each part of the robot becomes independent, reusable, and replaceable.
<br>Major Components of ROS2 are 
<h4><br>NODE:</h4> 
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
<br>Topics are used for continuous data flow.
<br>Topics joins the flow of robot like a chain 
<br>Publisher–Subscriber model:
<br>One node publishes
<br>Other nodes subscribe
<br><h4>SERVICES:  (Request–Response)</h4>
<br>Service are used for:
1.Start/stop commands
2.Mode switching
3.Calibrations 
Serivices are used when:
<br>You need one answer from the robot and need immediate response
  <h4>YOLO MODELS:</h4>
<br>YOLO simply means You Only Look Once. YOLO is a real-time object detection algorithm used in computer vision.
<br>It can detect objects AND tell you where they are in an image or video captured by robot. All this happens in a single pass through the image.
<br>For every object in an image, YOLO gives : Class , Bounding box and Confidence Score.
<h4><br>CLASS:</h4>
Class tells us what is the object like person,car.
<h4><br>BOUNDING SCORE:</h4> 
Tells us where is the object. 
<h4><br>CONFIDENCE SCORE :</h4>
It tells how sure is the model about the  Example output of an image :
<br>Person – 92%
<br>Car – 88%
