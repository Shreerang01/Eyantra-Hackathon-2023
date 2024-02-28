
# Rescue Drone (An Ultimate LIFE SAVER)

Creation of Drone which will increase the efficiency of the rescue teams, providing them with a 
better view of the affected area and guiding them in the evacuation plans. Rescue plans generally 
last for days and weeks creating a critical shortcoming to the affected once. One of the major 
challenges is to find the survivors and victims are provide them help at the earliest. Quick disaster 
management system by the way of UAV’s is the approach towards fast resolution as delay may lead 
to rise in death toll. So, this is our major inspiration for our team to make sure than no human death 
arises by the basic reason of no help in time and disaster management teams can reach to them at 
the earliest. An Autonomous Drone which will give better access to the Rescue Team by providing 
aerial view of the calamity-struct area, identify the survivors (humans, animals etc.) trapped in the 
vicinity and provide the rescue team with proper pathway planning for the evacuation process. The 
main advantage of drones is that no matter how bad the calamity, they are free to scan the area in 
the sky. The Rescue Drone will comprise hardware components such as High-Resolution Camera, 
Global Positioning System (GPS), Thermal Cameras, Ultrasonic Sensors, Raspberry Pi (On board 
Computer). Image Processing for Human Detection will be done with the help of open-source
library OpenCV, and use Machine Learning for Human Detection, Software such as Robot 
Operating System (ROS), Gazebo and Rviz used for Drone simulation and Pathway Planning.

## Demonstration 
For a detailed Demonstration of the Recuse Drone in action click on [:link:](https://www.youtube.com/watch?v=YkFYba-qDHI)

## Rescue Drone Prototype 
![Drone_Detail](https://github.com/Shreerang01/Eyantra-Hackathon-2023/assets/113919844/4c978588-eca1-4d10-8bd4-52d2327568d6)

## Eyantra Hardware Hackathon 2023
e-Yantra is a robotics outreach program funded by the Ministry of Education and hosted at IIT Bombay. The goal is to harness the talent of young engineers to solve problems using technology across a variety of domains such as: agriculture, manufacturing, defence, home, smart-city maintenance and service industries.


## Project Overview:

Our project comprises three main categories:

- **Hardware and Instrumentation:**
  This involves assembling the drone, incorporating components like frame, battery, flight controller, GPS, onboard computer, camera, and sensors for optimal functionality.

- **Software for Image Processing:**
  We develop algorithms for obstacle and human detection, utilizing advanced image processing techniques to analyze real-time data captured by the drone's camera.

- **Obstacle Avoidance & Path Planning:**
  This segment focuses on real-time scanning of the environment to detect obstacles and determining the best route for the drone to navigate safely and efficiently.

Our drone system is meticulously configured with a 32-bit headless Raspbian OS on a Raspberry Pi, enabling secure shell access over Wi-Fi. It seamlessly integrates Receiver-Transmitter modules for BLDC motor calibration and manual flight control, communicating with the Pixhawk flight controller via MAVLINK protocol through a USB to B-type serial port. Power is efficiently managed using a 12V to 5V DC-DC buck converter from the Power Distribution Board (PDB). Image processing capabilities are enriched by an onboard Raspberry Pi camera, employing Python scripts and Machine Learning algorithms (utilizing OpenCV, NumPy, and HOG features) for real-time human detection and counting using OpenCV's "putText" function, ensuring precise control, autonomous navigation, and intelligent environmental perception.

## Hardware: 

| Sr No. | Components                                                          |
|--------|---------------------------------------------------------------------|
| 1      | Pixhawk 2.4.8 Drone Flight Controller PX4 32 Bit Autopilot         |
| 2      | Q450 Quadcopter Frame – PCB Version Frame Kit with Integrated PCB   |
| 3      | A2212 1000 KV BLDC Brushless DC Motor for Drone (Soldered Connector)|
| 4      | Orange HD Propellers 1045(10X4.5) ABS DJI Black 2CW+2CCW-2pair-Premium Quality|
| 5      | SimonK 30A BLDC ESC Electronic Speed Controller with Connectors    |
| 6      | Converter for raspberry pi                                          |
| 7      | 3D Printed Legs for base                                            |
| 8      | Pixhawk LED Switch                                                  |
| 9      | Pixhawk buzzer                                                      |
| 10     | NEO-M8N GPS with Compass for Pixhawk with extra connector for APM with stand|
| 11     | Raspberry Pi 4 Model B                                              |
| 12     | Raspberry Pi Camera Module 3                                         |
| 13     | APM/Pixhawk Power Module V6.0 Output BEC 3A XT60 Plug 28V 90A       |
| 14     | 3300mAh 3S 11.1V Lithium polymer (LiPo) rechargeable battery with XT60 female connector 30C|
| 15     | FlySky FS-IA10B Radio Receiver                                      |
| 16     | FS-TH9X 2.4GHz 9CH Upgrade Transmitter                              |
| 17     | Orange 6200mAh 4cell 14.8v 35C Battery (Extra)                      |
| 18     | B3 PRO Compact Charger                                               |
| 19     | Ultrasonic Sensor Module HC-SR-04 by Robokart                       |
| 20     | Connecting wires (female to female)                                 |
| 21     | Anti-Vibration Shock Absorber for APM/KK/MWC/PixHawk                |
| 22     | Zip wrap                                                             |
| 23     | 40cm Lipo Battery Strap Belt Reusable Cable Tie Wrap                |

## Software: 
| Software           | Description                           |
|--------------------|---------------------------------------|
| Raspbian OS        | Operating system for Raspberry Pi     |
| Command-line       | Interface for executing commands      |
| Mission-planner    | Ground control station for UAVs       |
| Q-ground Controller| Ground control software for UAVs      |

## Technical Skills Required:
| Technical Skills                                     | Description                                                   |
|------------------------------------------------------|---------------------------------------------------------------|
| Basics of quadcopter kinematics and quadcopter autonomy | Understanding fundamental principles of quadcopter dynamics and autonomy|
| Manual control of drone using receiver and transmitter | Proficiency in manually controlling drones via receiver-transmitter setup|
| ROS, Gazebo, PX4                                    | Competence in Robot Operating System (ROS) ecosystem, simulation with Gazebo, and PX4 flight stack |
| Communication over MAVLINK between Raspberry Pi and Pixhawk | Experience in establishing communication protocols utilizing MAVLINK between Raspberry Pi and Pixhawk flight controller |
| Image processing using OpenCV and Raspberry Pi      | Proficiency in utilizing OpenCV library and Raspberry Pi for image processing tasks |
| Human detection                                      | Capability to develop algorithms for human detection in images/videos |
| Soldering                                            | Proficiency in soldering electronic components for assembly and repair |

## Applicability of Rescue Drone
Our Rescue Drone system, augmented with Machine Learning algorithms, operates autonomously, employing advanced path planning and precise obstacle avoidance to locate and assist affected individuals in disaster-stricken areas. Designed for swift deployment and ease of use, this robust system boasts extensive range and battery backup, ensuring comprehensive coverage of affected regions, even in the most remote corners. Utilizing high-resolution visible light or thermal cameras, our drones facilitate efficient rescue operations, enabling coordinated efforts by rescue teams, even in low visibility conditions. By overcoming land obstacles and navigating through challenging terrain, including trees, this innovative rescue system emerges as a vital asset in future rescue missions, significantly enhancing overall efficiency and saving lives.

## License

[MIT](https://choosealicense.com/licenses/mit/)

