---
permalink: /
title: "Hey there! 👋 I'm Dev"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

🤖 Robotics Engineer in the making  
🎓 Johns Hopkins University - MS Robotics  


🔬 Research Focus
======

I am interested in Robotics, Controls, Reinforcement Learning, and Deep Learning. Most of my work revolves around designing, controlling, and automating robots to make them smarter and more autonomous. 

💼 Experience
======


Dosage rate for mouse for cancer treatment something like that 
------
I am Graduate Research Assistant at Advanced Medical Instrumentation and Robotics (AMIRo) Research Lab. Developing a high-precision mechanical positioning system for small animal FLASH X-ray therapy at AMIRo Lab. Implementing dual-arm robotic configuration with 3D-printed PLA collimator assemblies achieving 20-40 micrometer alignment accuracy (Keyence 3D profiler measurements). Designing multi-modal mouse bed with 80mm bi-directional translation, 90-degree rotation, and 250g load capacity (0.4mm max deflection). Utilizing Creo Parametric for design and FEA simulation. System features hybrid manual/electronic control, variable collimator patterns for targeted tumor ablation, and integrated multi-nozzle anesthesia delivery. Creating modular platform compatible with both micro-CT imaging and FLASH therapy systems, enabling seamless workflow integration for image-guided preclinical radiotherapy research.


Putting a car steering hanlde using UR5: Probabilitic RoadMap - Motion Planner
------
Implemented custom PRM-based motion planner in C++ for UR5 robotic arm to autonomously grasp and install automotive steering wheels. Built collision-free roadmap in 6D configuration space, utilizing KD-tree data structure for efficient nearest neighbor queries to connect vertices within radian distance threshold. Applied graph theory algorithms- BFS for path search through adjacency list representation, achieving O(V+E) time complexity. Leveraged FLANN library for optimized spatial indexing and integrated with MoveIt framework for collision checking using FCL backend. Achieved sub-30 second planning times for complex assembly tasks, validating approach through successful steering wheel installation in cluttered automotive workspace.

Kalman Filter for postion of jackal robot
------

UR5 Robotic Arm Control for Parallel Line Drawing
------
Programmed UR5 robot to perform "place-and-draw" task, teaching start/end positions to draw two 5cm parallel lines with 10cm spacing. Implemented three control algorithms in MATLAB: Inverse Kinematics using DH parameters and Paden-Kahan subproblems (selecting optimal solution from 8 possibilities), Resolved Rate control with discrete-time implementation, and Jacobian Transpose for trajectory tracking. Incorporated manipulability analysis for singularity avoidance and optimized control gains (K) and time steps (Δt) through iterative testing. Achieved rotation-invariant algorithm design allowing parallel line drawing regardless of initial point orientation.

Semantic SLAM Detecting object is 3D map
------
Developed an end-to-end real-time semantic SLAM system by first capturing and manually annotating 1,000+ images of various objects across different colors and orientations to create a robust training dataset. Trained YOLOv7 model achieving 91% mAP@0.5 for accurate object detection across shape and color variations. Performed camera calibration using OpenCV checkerboard method to extract intrinsic parameters and distortion coefficients from Pi Camera v2. Developed Python streaming utilities to capture raw image data from Raspberry Pi 4 and convert to ROS bag format for consistent input processing. Integrated the trained YOLOv7 model with ORB-SLAM3 through multi-threaded ROS Noetic pipeline, where SLAM generates sparse 3D point clouds while YOLO performs real-time object detection at 30 FPS. Implemented direct semantic fusion by projecting 2D bounding box detections onto 3D map points using calibrated depth measurements, creating a dense semantic map with real-time object labeling and spatial localization.

Morphing robot
------
Conceptualized and designed a novel bio-inspired morphing robot system through comprehensive biomimetic research to identify 8 distinct operational configurations for versatile terrain adaptation. Developed detailed mechanical design integrating dual locomotion systems: mecanum wheels for omnidirectional ground movement and quadcopter propellers for aerial capabilities, enabling hybrid air-ground movement schemes. Created 3D CAD models and engineering drawings specifying actuator placement, joint mechanisms, and transformation sequences between configurations. Implemented basic Arduino control code for manual switching between ground-based car configuration and aerial drone configuration through servo motor actuation. Validated design feasibility through kinematic analysis and structural simulations of the morphing mechanisms. 


2 DOF Needle Driver for Streotatic Brain Biopsy
------
<img src="/DevGhiya/images/Biopsy.jpeg" alt="Device Design" style="float: right; width: 250px; margin-left: 20px;">

Developed a novel needle manipulation system featuring an aperture-inspired gripper with compliant flexure design achieving 0.1mm accuracy. Implemented three micro high-torque geared motors controlling needle insertion, rotation, and flexure-actuated gripping mechanism that moves concentrically like a camera aperture. Engineered PLA-based compliant mechanics enabling dynamic inner diameter adjustment while maintaining safe gripping forces, resulting in 24% weight reduction from previous design. Built Raspberry Pi-based control system operating at 100Hz with PID controllers for real-time motor control. Successfully demonstrated proof-of-concept for precision needle manipulation combining aperture-style gripping with compliant robotics principles for medical applications.


Miscilenous
======

🏎️ Formula Student Team Captain - Vehicle Design & Dynamics
------
Led 18-member team as captain designing 200kg formula student race car, driving aerodynamic development achieving 150kg downforce at 100km/h through CFD optimization in OpenFOAM with k-ω SST turbulence modeling. Designed lightweight tubular chassis in Siemens NX achieving torsional rigidity of 1500 Nm/deg while maintaining optimal weight distribution. Optimized suspension kinematics in LOTUS for 2° camber gain, <0.5° bump steer, 45/55 weight distribution, 1.5Hz ride frequency, and 2.2Hz roll frequency. Validated vehicle dynamics through 60 km/h testing achieving 1.4g lateral acceleration, 12m turning radius, and 0.8g braking deceleration.  

🛞 Robotfest comeptition
------
Conceptualized amphibious rover with team of 3 for navigating 60° inclines and 15cm water depths, developing detailed CAD models and feasibility analysis. Designed hybrid wheel-paddle locomotion system with sealed drivetrain components for dual terrain capability. Created modular chassis architecture using topology optimization for 3D printed components, targeting 40% weight reduction through lattice structures and material selection (PLA/PETG). Proposed sensor suite including IMU for incline detection, ultrasonic depth sensors, and encoder feedback for closed-loop control.

