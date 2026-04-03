Project Report: Low-Cost FPV Camera 
Drone 
1. Project Title 
Low-Cost FPV Camera Drone for Real-Time Aerial Monitoring 
2. Objective 
The objective of this project is to design and develop a quadcopter drone capable of: 
• 
�
�
 Stable multi-directional flight (roll, pitch, yaw, throttle) 
• 
�
�
 Real-time video streaming using an FPV system 
• 
�
�
 Transmitting live video feed directly to a mobile device 
• 
�
�
 Wireless control using a remote transmitter 
This project aims to replicate real-world surveillance and aerial monitoring drones using 
cost-effective and modular components. 
3. Problem Statement 
In applications such as: 
• Surveillance systems 
• Disaster monitoring 
• Exploration and inspection 
Traditional drones with FPV capabilities are: 
• Expensive 
�
�
 
• Complex to build and maintain 
⚙
 
• Not easily accessible to students 
�
�
 
�
�
This project solves the problem by: 
Providing a low-cost, hands-on FPV drone platform for learning and real-world 
applications. 
4. Proposed Solution 
We propose a quadcopter drone system that: 
• Uses a flight controller for stabilization 
• Receives wireless commands from a transmitter 
• Controls motor speed using ESCs 
• Captures and transmits real-time video using an FPV system 
• Displays live feed directly on a mobile device 
5. System Architecture 
The system consists of two major subsystems: 
�
�
Flight Control System 
• Remote Controller → Receiver 
• Flight Controller → ESC → Motors 
• Stabilization using onboard sensors 
�
�
FPV Video System 
• Camera captures video 
• Video Transmitter (VTX) sends signal 
• FPV Receiver receives signal 
• Mobile displays live video 
6. Workflow 
Flight Operation Flow: 
1. User inputs command via transmitter 
2. Receiver captures signal 
3. Flight controller processes input 
4. ESC adjusts motor speed 
5. Motors rotate propellers → drone movement 
Video Transmission Flow: 
1. Camera captures real-time video 
2. VTX transmits signal wirelessly 
3. FPV receiver receives signal 
4. Video displayed on mobile device 
7. Components Required 
�
�
Core Components 
• F450 Quadcopter Frame 
• A2212 1000KV Brushless Motors (4x) 
• 30A ESC (Electronic Speed Controller) 
• F4 Flight Controller 
• 1045 Propellers 
�
�
Power System 
• 3S LiPo Battery (2200mAh) 
• Power Distribution Board 
• LiPo Balance Charger 
�
�
Communication System 
• FlySky FS-i6 Transmitter 
• FlySky FS-iA6 Receiver 
�
�
FPV System 
• Runcam Phoenix 2 Camera 
• 5.8GHz Video Transmitter (VTX) 
• Eachine ROTG02 FPV Receiver 
�
�
Others 
• Wires, connectors, XT60 plug 
• Screws, zip ties 
8. Technologies Used 
• Embedded Control Systems 
• Flight Stabilization Algorithms 
• Wireless Communication (2.4GHz & 5.8GHz) 
• Real-Time Signal Processing 
• FPV (First Person View) Transmission 
9. Circuit Diagram (Conceptual) 
Connections overview: 
• Motors → ESC → Flight Controller 
• Receiver → Flight Controller 
• Battery → Power Distribution Board → ESC & Electronics 
• Camera → VTX → Wireless Transmission 
• FPV Receiver → Mobile Device 
10. Software & Configuration Overview 
Flight Controller Setup 
• Firmware configuration (Betaflight / similar) 
• Sensor calibration (Gyroscope, Accelerometer) 
• ESC calibration 
Control System 
• Receiver binding with transmitter 
• Channel mapping (Throttle, Pitch, Roll, Yaw) 
FPV System Setup 
• Frequency configuration (5.8GHz band) 
• Channel matching between VTX and receiver 
11. Key Features 
• 
�
�
 Stable quadcopter flight 
• 
�
�
 Real-time FPV video transmission 
• 
�
�
 Mobile-based video monitoring 
• 
�
�
 Cost-efficient design (~$210) 
• 
�
�
 Modular and upgradeable system 
12. Use Cases 
• Surveillance drones 
• Disaster monitoring 
• Aerial inspection 
• Exploration systems 
• Security applications 
13. Innovation & Uniqueness 
• Low-cost alternative to expensive FPV drones 
• Combines flight control + real-time video system 
• Mobile-based FPV (no costly goggles required) 
• Modular design for learning and scalability 
• Suitable for educational robotics platforms 
14. Future Enhancements 
• GPS-based navigation 
• Autonomous flight system 
• Obstacle avoidance 
• AI-based object tracking 
• HD digital FPV upgrade 
15. Build & Testing Plan (For Submission) 
• Frame assembly and motor mounting 
• Flight controller and ESC integration 
• FPV system setup and testing 
• Calibration without propellers 
• Controlled flight testing and tuning 
16. Conclusion 
This project demonstrates a complete aerial robotic system integrating: 
• Flight control systems 
• Wireless communication 
• Real-time video transmission 
It provides a scalable, cost-effective solution for aerial monitoring and serves as a strong 
foundation for learning advanced drone technologies.
