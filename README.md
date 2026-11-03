# Subin Park

**AI Development · Robotics Engineering**

I work on Korean NLP experiments and ROS 2 vehicle control. My current work focuses on adaptive communication for multi-robot systems.

## Selected Projects

### Korean Hate Speech Detection · Undergraduate Research

I ran few-shot classification experiments on KOLD, including ICCD/CD experiments. In the reported self-refinement ablation, the proposed method achieved **0.4636 macro-F1**, compared with **0.4039** for regular in-context learning. The repository includes experiment scripts, prompts, and reported metrics.

[Experiment code and results](https://github.com/psubin05/hate_self_refine)

### Adaptive Multi-Robot Communication · In Progress

I am working on how robots can adapt their communication to changing conditions while coordinating as a team.

### F1TENTH Adaptive Racing Control · Autonomous Driving Competition

I adapted a TinyLidarNet inference node in an existing ROS 2 racing stack on NVIDIA Jetson. I used forward LiDAR clearance to adjust the speed limit and commanded speed to constrain steering.

[Control implementation](https://github.com/psubin05/F1TENTH-Adaptive-Racing-Control)

### F1TENTH Collision Detection and Reverse Recovery · Team Project

I implemented collision detection using LiDAR, IMU, and odometry, and integrated the ROS 2 state transitions and controller switching. The team’s recovery sequence uses rule-based reverse steering and waits for particle-filter localization to stabilize before resuming Pure Pursuit.

[Recovery implementation and demo documentation](https://github.com/psubin05/f1tenth-collision-recovery)

## Tools and Methods

- **AI and NLP:** Python, few-shot evaluation, in-context learning, vLLM
- **Robotics and control:** ROS 2, Python, C++, LiDAR, Ackermann control, NVIDIA Jetson

## Contact

[psubin0512@gmail.com](mailto:psubin0512@gmail.com)

