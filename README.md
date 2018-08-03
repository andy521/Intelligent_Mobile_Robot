# Intelligent Mobile Robot
Intelligent Navigation System of Mobile Robot.
<br/>[![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.1317906.svg)](https://doi.org/10.5281/zenodo.1317906)

### Reference to:
Valentyn N Sichkar. Intelligent Navigation System of Mobile Robot // GitHub platform. DOI: 10.5281/zenodo.1317906

### Related works:
* The investigation of Reinforcement Learning for the tasks of shortest path planning is put in separate repository and is available here: https://github.com/sichkar-valentyn/Reinforcement_Learning_in_Python

* The research results for Neural Network Knowledge Based system for the tasks of collision avoidance is put in separate repository and is available here: https://github.com/sichkar-valentyn/Matlab_implementation_of_Neural_Networks

* The study of Semantic Representation of knowledge and querying of it through owl files with SPARQL is put in separate repository and is available here: https://github.com/sichkar-valentyn/System_programming_for_SPARQL_querying_with_interface_development_by_html_files

* The study of Neural Networks for Computer Vision in autonomous vehicles and robotics is put in separate repository and is available here: https://github.com/sichkar-valentyn/Neural_Networks_for_Computer_Vision

## Description
<b>Hardware</b> - Arduino Mega, Motor Shield L298P, DC Motors, Ultrasonic Sensors, Gyroscope, Laser Sensors, Cameras, Lidar Sensor, Bluetooth Module, Batteries, Six Wheel High Pass Base with Active Suspension.
<br/><b>Software</b> - C# via Visual Studio, Python, Arduino IDE, Android SDK, Matlab.
<br/><b>Developmet</b> - Algorithms for Overcoming Obstacles, Algorithms for Localization, Algorithms for Mapping, SLAM Algorithms.

## Content
* <a href="#Introduction">Introduction</a> 
* <a href="#Connecting DC Motors">Connecting DC Motors</a>
* <a href="#More information about equipment">More information about equipment</a>
* <a href="#Adding FIVE Ultrasonic sensors US-015">Adding FIVE Ultrasonic sensors US-015</a>
* <a href="#Checking the abilities to stop before the possible collisions with obstacles">Checking the abilities to stop before the possible collisions with obstacles</a>
* <a href="#Adding TEN Ultrasonic sensors HC-SR04">Adding TEN Ultrasonic sensors HC-SR04</a>
* <a href="#Connecting two Arduino Mega together">Connecting two Arduino Mega together</a>
* <a href="#Checking the abilities to overcome obstacles">Checking the abilities to overcome obstacles</a>

### <a name="Introduction">Introduction</a>
Explaining the main goals of the Project
<br /><a href="https://www.youtube.com/watch?v=srEd8KEh2uo" target="_blank">https://www.youtube.com/watch?v=srEd8KEh2uo</a>
<br /><a href="https://www.youtube.com/watch?v=srEd8KEh2uo" target="_blank"><img src="https://img.youtube.com/vi/srEd8KEh2uo/0.jpg" alt="Main goals of the Project" width="500" /></a>

### <a name="Connecting DC Motors">Connecting DC Motors</a>
Connecting and checking the High Pass Six Wheel Base - HPSWB - for simple commands to move
<br /><a href="https://www.youtube.com/watch?v=Ux8xrQHnlzI" target="_blank">https://www.youtube.com/watch?v=Ux8xrQHnlzI</a>
<br /><a href="https://www.youtube.com/watch?v=Ux8xrQHnlzI" target="_blank"><img src="https://img.youtube.com/vi/Ux8xrQHnlzI/0.jpg" alt="Connecting_DC_Motors" width="500" /></a>

### <a name="More information about equipment">More information about equipment</a>
General view of the Motor Shield L298P is shown below on the figure
<br/><img src="/images/L298P.jpg" alt="L298P" width="500"/>

<br/>The view from the top of Motor Shield L298P and showing the main connectors that are needed for the Project.
<br /><img src="/images/L298P_top_view.png" alt="L298P_top_view" width="500"/>

<br/>General view of the DC Motor
<br /><img src="/images/DC_Motors.png" alt="DC_Motor" width="200"/>

<br/>Connection DC Motors to the Shield
<br /><img src="/images/DC_Motors_7.png" alt="Connection_DC_Motors" width="500"/>

<br/>General view of the Bluetooth Module HC-06
<br /><img src="/images/Bluetooth_Module_HC-06.jpg" alt="Bluetooth_Module_HC-06" width="200"/>

<br/>Connection Bluetooth Module HC-06 to the Shield or Arduino
<br /><img src="/images/HC-06_Connectors.jpg" alt="Connection_Bluetooth_Module" width="500"/>

<br/>More about equipment
<br/>https://www.youtube.com/watch?v=6KQcZUehVFo
<br /><a href="https://www.youtube.com/watch?v=6KQcZUehVFo"><img src="https://img.youtube.com/vi/6KQcZUehVFo/0.jpg" alt="Equipment" width="500"/></a>

<br/>General view of the Ultrasonic Sensor US-015
<br /><img src="/images/General_View_of_US-015.jpg" alt="Ultrasonic_Sensor_US-015" width="200"/>

<br/>Connection Ultrasonic Sensor US-015 (or HC-SR04) to the Arduino
<br /><img src="/images/Connection_of_Ultrasonic_Sensor.png" alt="Connection_Ultrasonic_Sensor" width="500" />

<br/>Equations for Ultrasonic Sensors, explaining how they work
<br /><img src="/images/Equasions_for_Ultrasonic_Sensor.png" alt="Equasions_for_Ultrasonic_Sensor" width="500" />

### <a name="Adding FIVE Ultrasonic sensors US-015">Adding FIVE Ultrasonic sensors US-015</a>
Checking the environment around with Ultrasonic Sensors US-015
<br/>HPSWB with Ultrasonic Sensors - view from the front
<br/><img src="/images/SWB_with_Ultrasonic_Sensors_Front.jpg" alt="Front" width="500" />

<br/>HPSWB with Ultrasonic Sensors - view from the back
<br/><img src="/images/SWB_with_Ultrasonic_Sensors_Back.jpg" alt="Back" width="500" />

<br/>HPSWB with Ultrasonic Sensors - view from one side
<br/><img src="/images/SWB_with_Ultrasonic_Sensors_Side.jpg" alt="Side" width="500" />

### Figure below shows the results of working system in Real Time by SPARQL Querying of the Knowledge Base
<br/><img src="/images/SPARQL_Querying_of_KB.png" alt="SPARQL_Querying" width="500" />

### This figure shows the results of Neural Network Knowledge Base
<br/><img src="/images/Results_of_the_Neural_Network.png" alt="NNKB" width="500" />

### <a name="Checking the abilities to stop before the possible collisions with obstacles">Checking the abilities to stop before the possible collisions with obstacles</a>
With the help of Ultrasonic Sensors and seeing the obstacles to avoid the collisions
<br /><a href="https://www.youtube.com/watch?v=QVCCuo-QOwA" target="_blank">https://www.youtube.com/watch?v=QVCCuo-QOwA</a>
<br /><a href="https://www.youtube.com/watch?v=QVCCuo-QOwA" target="_blank"><img src="https://img.youtube.com/vi/QVCCuo-QOwA/0.jpg" alt="Avoid_Collision" width="500" /></a></p>

### <a name="Adding TEN Ultrasonic sensors HC-SR04">Adding TEN Ultrasonic sensors HC-SR04</a>
Checking the environment around with Ten Ultrasonic Sensors HC-SR04
<br />HPSWB - view from the front
<br /><img src="/images/HPSWB_with_Ten_Ultrasonic_Sensors.jpg" alt="Front" width="500" /></p>

<img src="images/User_interface.gif" alt="User interface with ten ultrasonic sensors" width="500">

### <a name="Connecting two Arduino Mega together">Connecting two Arduino Mega together</a>
The way how to connect Master and Slave Arduino Mega together through Serial Port
<br /><img src="/images/2ArduinoMega2560.png" alt="Two_Arduino_Mega" width="500" />

### <a name="Checking the abilities to overcome obstacles">Checking the abilities to overcome obstacles</a>
Implementing and testing Algorithms for HPSWB
<br /><a href="https://www.youtube.com/watch?v=rjMo-d7WrMY" target="_blank">https://www.youtube.com/watch?v=rjMo-d7WrMY</a>
<br /><a href="https://www.youtube.com/watch?v=rjMo-d7WrMY" target="_blank"><img src="https://img.youtube.com/vi/rjMo-d7WrMY/0.jpg" alt="Overcoming_Obstacle" width="500" /></a></p>

<img src="images/Obstacle_overcoming.gif" alt="Obstacle overcoming" width="500">

<br/>

### MIT License
### Copyright (c) 2018 Valentyn N Sichkar
### github.com/sichkar-valentyn
### Reference to:
Valentyn N Sichkar. Intelligent Navigation System of Mobile Robot // GitHub platform. DOI: 10.5281/zenodo.1317906
