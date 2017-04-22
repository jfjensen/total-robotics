# Table of Contents

* TOC
{:toc}


# Introduction to Kalman Filters by Michel van Biezen

[playlist with 55 videos](https://www.youtube.com/playlist?list=PLX2gX-ftPVXU3oUFNATxGXY90AULiqnWT)

# Introduction to GPS by Michel van Biezen

[playlist with 18 videos](https://www.youtube.com/playlist?list=PLX2gX-ftPVXXGdn_8m2HCIJS7CfKMCwol)

# Control System Lectures by Brian Douglas

PID Control:
[playlist with 2 videos](https://www.youtube.com/playlist?list=PLUMWjy5jgHK20UW0yM22HYEUTMJfla7Mb)

# Forward and Inverse Kinematics by Coding Math

Demo with implementation in Javascript.

Lecture 1: [video](https://youtu.be/WHn2ouKKSfs)

Lecture 2: [video](https://youtu.be/4oCo1j8xGew)

Lecture 3: [video](https://youtu.be/sEKNoWyKUA0)

Lecture 4: [video](https://youtu.be/7t54saw9I8k)

# Artificial Intelligence for Robotics by Sebastian Thrun (Udacity)

A course created by Sebastian Thrun on the on-line educational platform Udacity. It covers the basic techniques for self-driving robots/cars. The course material is presented in a series of videos accessible via the Udacity platform. This course is very motivational. The exercises sometimes vary highly in difficulty though. The solution code for the exercises is always given. There's also an on-line forum where students can ask questions. This is a good place to start.

[Link to the class Wiki](https://www.udacity.com/wiki/cs373)

#### Lesson 1: The problem of localization

  Robot sensing and movement. Probabilistic techniques to deal with inaccuracies. Probability theory basics like Bayes theorem and law of total expectation. Finding position in 2D world.  

  [Lesson notes - PDF](https://storage.googleapis.com/supplemental_media/udacityu/48739381/Lesson1Notes.pdf)

#### Lesson 2: Kalman Filters

  Powerful localization method. Matrix operations to predict position and velocity of robot with linear motion. Conenctions between Kalman filter and Gaussian function and covariance.  

  [Lesson notes - PDF](https://storage.googleapis.com/supplemental_media/udacityu/48723604/Lesson2Notes.pdf)

#### Lesson 3: Particle Filters

  Alternative technique to Kalman Filter. Different possible robot positions are generated at random and evaluated according how close these are to the observed measurements. Particles are then reselected with probability. This creates a cluster around robot, reflecting its probable position.  

  [Lesson notes - PDF](https://storage.googleapis.com/supplemental_media/udacityu/48704330/Lesson3Notes.pdf)

#### Lesson 4: Motion Planning

  Planning robot motion. Path planning strategies A* search and Dynamic Programming.  

  [Lesson notes - PDF](https://storage.googleapis.com/supplemental_media/udacityu/48646841/Lesson4Notes.pdf)

#### Lesson 5: PID Control

  Path smoothing. PID controller to make robot follow a path. Smooth corrections when robot deviates from path.  

  [Lesson notes - PDF](https://storage.googleapis.com/supplemental_media/udacityu/48743150/Lesson5Notes.pdf)

#### Lesson 6: GraphSLAM

  Review of previous lessons. Method for simultaneous localization and mapping (SLAM). This method helps solving the problem of a robot in a world whose features are unknown.  

  [Lesson notes - PDF](https://storage.googleapis.com/supplemental_media/udacityu/48696626/Lesson6Notes.pdf)



# SLAM tutorial by Prof. Claus Brenner

A tutorial on Youtube on Simultaneous Location And Mapping by Prof. Claus Brenner. Starter code in Python can be downloaded using a link below the videos. No solution code is given. Only the expected results of running the solution code are given. This is a very nice tutorial to follow after "Artificial Intelligence for Robotics" by Sebastian Thrun.

#### Unit A: Getting started with a real robot

   [Video 1: Getting Started](https://www.youtube.com/watch?v=sxu6_YnZca8)  
   [Video 2: Motor Control](https://www.youtube.com/watch?v=Wt-ivnBZsv0)  
   [Video 3: Motion Model](https://www.youtube.com/watch?v=HPeBhArNpzY)  
   [Video 4: Implementing the motion model](https://www.youtube.com/watch?v=7zpz7f73MOU)  
   [Video 5: Some modifications](https://www.youtube.com/watch?v=wNmCSF0Pk4w)  
   [Video 6: Sensor Data](https://www.youtube.com/watch?v=_rGseGPtS7g)  
   [Video 7: Sensor Data pt.2](https://www.youtube.com/watch?v=JBr3dpvvmVo)  
   [Video 8: Sensor Data pt.3](https://www.youtube.com/watch?v=rrg9BtfxdhM)  
   [Video 9: Sensor Data pt.4](https://www.youtube.com/watch?v=uz-ckOO8w9s)  

#### Unit B: Using sensor data to improve the robot's state

   [Video 1: Intro](https://www.youtube.com/watch?v=AbmhPu6lgUs)  
   [Video 2: Estimating the feature transform](https://www.youtube.com/watch?v=2Zf7J6cKpOQ)  
   [Video 3: Applying the transform](https://www.youtube.com/watch?v=zSUoE-I9kkc)  
   [Video 4: ](https://www.youtube.com/watch?v=kTg7mGL48Jw)  
   [Video 5: Estimating the wall transform](https://www.youtube.com/watch?v=rM-CajaLZi4)  
   [Video 6: ICP - Iterative Closest Point transform](https://www.youtube.com/watch?v=zBe4IfpPRlc)  

#### Unit C: Filtering

  [Video 1: Intro](https://www.youtube.com/watch?v=6JEN_5rp6bI)  
  [Video 2: Moving probability distribution](https://www.youtube.com/watch?v=mdzgKpRRd58)  
  [Video 3: Convolution of distribution](https://www.youtube.com/watch?v=YhxdZt9rzRA)  
  [Video 4: Modelling uncertainty](https://www.youtube.com/watch?v=YXraP_l2g_Y)  
  [Video 5: Multiplication of probability distribution](https://www.youtube.com/watch?v=olOGM0bv1BA)  
  [Video 6: Histogram Filter](https://www.youtube.com/watch?v=yCYybXmuVEU)  
  [Video 7 ](https://www.youtube.com/watch?v=JNCkmzec-zk)  
  [Video 8 ](https://www.youtube.com/watch?v=kNLehf7vs5w)  
  [Video 9: Kalman Filter vs. Histogram Filter](https://www.youtube.com/watch?v=SEh7vst6XPc)  
  [Video 10: OVerview of Filtering](https://www.youtube.com/watch?v=zRuXKGNIb4o)  

#### Unit D: Kalman Filter

  [Video 1: Intro](https://www.youtube.com/watch?v=xN6OEwudmwo)  
  [Video 2: Normal Distribution](https://www.youtube.com/watch?v=tP3UAE8dyuw)  
  [Video 3 ](https://www.youtube.com/watch?v=2KhE8PDqj7M)  
  [Video 4 ](https://www.youtube.com/watch?v=cMAoOxMnCsk)  
  [Video 5 ](https://www.youtube.com/watch?v=9IZMrNNg6Ac)  
  [Video 6: Kalman Filtering in 1D and nD](https://www.youtube.com/watch?v=cXx5NmtPFag)  
  [Video 7 ](https://www.youtube.com/watch?v=VlvaZtABDoo)  
  [Video 8 ](https://www.youtube.com/watch?v=lMLKk7knWxk)  
  [Video 9 ](https://www.youtube.com/watch?v=g6qqfyN-7Ec)  
  [Video 10 ](https://www.youtube.com/watch?v=J0WqOvCSqA0)  
  [Video 11 ](https://www.youtube.com/watch?v=gdSEp58hOeo)  
  [Video 12 ](https://www.youtube.com/watch?v=QBcdaPfCXW8)  
  [Video 13: Extended Kalman Filter](https://www.youtube.com/watch?v=U2fE1AkmGmg)  
  [Video 14: EKF - prediction step](https://www.youtube.com/watch?v=QLslcjSF4GQ)  
  [Video 15: EKF - prediction step](https://www.youtube.com/watch?v=pc2EfZfQbCM)  
  [Video 16: EKF - correction step](https://www.youtube.com/watch?v=4gtNda-OD4Y)  
  [Video 17: Kalman Filter - putting everything together](https://www.youtube.com/watch?v=Idb05ZsD2t0)  
  [Video 18: Outro](https://www.youtube.com/watch?v=0bZNOfs4Tmg)  

#### Unit E: Particle Filter

  [Video 1: Intro](https://www.youtube.com/watch?v=ME7kUbLYMno)  
  [Video 2: Localization](https://www.youtube.com/watch?v=N6-1aGWE9IM)  
  [Video 3 ](https://www.youtube.com/watch?v=dgvi7eLleOo)  
  [Video 4: Particles - prediction step](https://www.youtube.com/watch?v=9jhnye7I2pU)  
  [Video 5: Particles - correction step](https://www.youtube.com/watch?v=kZhOJgooMxI)  
  [Video 6: Density Estimation](https://www.youtube.com/watch?v=x-bHZMo1a28)  
  [Video 7: Conclusions](https://www.youtube.com/watch?v=Il2xzNchp1M)  

#### Unit F: Simultaneous Localization and Mapping

  [Video 1: Intro](https://www.youtube.com/watch?v=NWxVKxZQBFs)  
  [Video 2: Online SLAM vs. Full SLAM](https://www.youtube.com/watch?v=lzjP9t_UPV8)  
  [Video 3 ](https://www.youtube.com/watch?v=wniJgJG0vNE)  
  [Video 4: EKF SLAM - prediction](https://www.youtube.com/watch?v=o9b9Lz80xvw)  
  [Video 5: Adding landmarks](https://www.youtube.com/watch?v=TQwzG_dy-Ao)  
  [Video 6: EKF SLAM - correction](https://www.youtube.com/watch?v=dlyzXjc8pRA)  
  [Video 7 ](https://www.youtube.com/watch?v=dV_5_OQbrFA)  
  [Video 8: On landmarks and Conclusions](https://www.youtube.com/watch?v=UyFBDgOwZ40)  

#### Unit G: Particle Filter SLAM - FastSLAM

  [Video 1: Intro](https://www.youtube.com/watch?v=9WyrWJcvneE)  
  [Video 2: Correspondence likelihood](https://www.youtube.com/watch?v=HfBqPi-ydrc)  
  [Video 3: New landmark](https://www.youtube.com/watch?v=Hk5s-8-0RlM)  
  [Video 4: Update landmark](https://www.youtube.com/watch?v=PZe_aAgIxHA)  
  [Video 5: Correction](https://www.youtube.com/watch?v=50NqWjiMnnE)  
  [Video 6: Spurious landmarks](https://www.youtube.com/watch?v=1lXD7nHDBxg)  
  [Video 7: Conclusion](https://www.youtube.com/watch?v=gwxBrE-aYmc)  

#### Unit PP: Basics of Path Planning

  [Video 1: Intro and Dijkstra's algorithm](https://www.youtube.com/watch?v=_Bmnxjj9lJw)  
  [Video 2: Dijkstra pt.2](https://www.youtube.com/watch?v=8qXG_k1bXEs)  
  [Video 3: Dijkstra pt.3](https://www.youtube.com/watch?v=n_xxEIwVO44)  
  [Video 4: Dijkstra using Heap data structure](https://www.youtube.com/watch?v=FEdid3OXTcw)  
  [Video 5: Dijkstra optimal path](https://www.youtube.com/watch?v=sVSV2lOq6UM)  
  [Video 6: Greedy search algorithm](https://www.youtube.com/watch?v=Lq6XC9rWRDs)  
  [Video 7: A* algorithm](https://www.youtube.com/watch?v=oMR-wIu38_s)  
  [Video 8: A* with potentional functions](https://www.youtube.com/watch?v=nQtmUH3UCi4)  
  [Video 9: A* with kinematic state space](https://www.youtube.com/watch?v=XNZkiDOVsNk)  
  [Video 10: A* with kinematic state space - optimized](https://www.youtube.com/watch?v=rnf4t00uSmk)  
  [Video 11: End](https://www.youtube.com/watch?v=JFtZnMu6PDQ)  

# Visual Navigation for Flying Robots by Dr. Jürgen Sturm

Complete playlist:

[playlist](https://www.youtube.com/playlist?list=PLTBdjV_4f-EKeki5ps2WHqJqyQvxls4ha)

Individual lectures:

#### Lecture 1: Introduction and History of Mobile Robotics

  [video](https://youtu.be/f5khDPUMYmQ)  

#### Lecture 2: Linear Algebra, 2D/3D geometry and Sensors

  [video](https://youtu.be/0wOp4k_lJvI)  

#### Lecture 3: Probabilistic Models and State Estimation 

  [video](https://youtu.be/ZT3HILfxvps)

#### Lecture 4: Robot Control

  [video](https://youtu.be/NCBZ6XW4TFs)



# Robotics - ColumbiaX - CSMM.103x - edX

#### Overview
Programming in ROS (Robot Operating System) with Python. Focus on Robot arms.

[link](https://courses.edx.org/courses/course-v1:ColumbiaX+CSMM.103x+1T2017/info)

#### Course Outline
* Week 1: Introduction to Robotics, Robotics and AI, Introduction to ROS, Project 1 released

* Week 2: 2D Transforms, Homogenous Coordinates, 3D Transforms, Thinking about Transforms, Transform Inverse, Rotation Representations, Transforms in ROS, the TF Library, Project 2 released

* Week 3: Robot Arms Introduction, Kinematic Chains, Forward Kinematics: URDF, Forward Kinematics: Analytical Methods, DH Parameters, Forward Kinematics:DH Examples, Project 3 released

* Week 4: Analytical IK, Robot Examples, Robot Workspaces and IK Solutions, Homework 1 released

* Week 5: Differential Kinematics: Jacobian Definition and Analytical Computation, Singularities, Full Kinematics: Robot Examples, Homework 2 released

* Week 6: Study week

* Week 7: Numerical Jacobian Computation, Cartesian and Null Space Control, Porject 4 released

* Week 8: Motion Planning: Configuration Space vs. Task Space, Stochastic Motion Planning, Project 5 released

* Week 9: Mobile Robots Introduction, Mobile Robots Kinematics: Differential Drive, Other Kinematics, Path Planning for Mobile Robots

* Week 10: Course Recap, Things We Have Not Covered, Robotics and AI Revisited 
