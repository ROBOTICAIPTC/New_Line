# WRO-2024
 
# Team Details

**Team Name:** New Line

**Country:** Panama, Panamá Oeste, District of Capira

**Team Members:** Josué Jiménez and Isaac Clara

**Coach:** Mara Martínez

# Contenido
* [**Introduccion**](#Introduccion)
* [**Materials**](#Materials)
* [**Mobility Management**](#Mobility-Management)
* [**Energy Management**](#Energy-Management)
* [**Schematic Diagram**](#Schematic-Diagram)
* [**Assembly instructions**](#IAssembly-instructions)
* [**Energy Management and Steering**](#GEnergy-Management-and-Steering)
* [**Code explanation**](#Code-explanation)
* [**Controller/Robot**](#Controller/Robot)
* [**Sensors and error margins**](#Sensors-and-error-margins)
* [**Huskylens (camera)**](#Huskylens)
* [**Team-Photos**](#Team-Photos)
* [**Vehicle-Photos**](#Vehicle-Photos)
* [**Obstacle Round**](#Obstacle-Round)
* [**Open challenge round**](#Open-challenge-round)
* [**Recommendations and tips**](#Recommendations-and-tips)
* [**Program version**](#Program-version)

# Introduction

New Line is a robot built with the EV3 Mindstorms robotics kit. It uses ultrasonic and color sensors to efficiently avoid obstacles. The motors for steering and mobility are located on the front and rear axles, respectively, allowing for precise maneuverability. The robot’s movement is driven by a system of gears, propelling its rear axle to provide traction and speed.

The movement process of New Line involves continuously receiving data from its sensors, which are processed by its central unit to make real-time decisions. When the ultrasonic sensor detects an obstacle, the robot calculates an alternative route to avoid it. Simultaneously, the color sensors monitor the environment to ensure that the robot stays within the track boundaries.

# Materials

- 4 Rim Wide 43,2x26 W 6 Hol.0 4.8
- 4 Tyre Low Wide 056 X 28
- 5 Tube, W/ Double 4.85 Hole
- 2 Gear Wheel Z24
- 2 Gear Wheel 40T
- 1 Gear Wheel Z16
- 1 Technic Angular Wheel
- 6 Bush For Cross Axel 
- 2 Bion. Eye
- 5 Angular Beam 90° W.4 Snaps
- 8 Technic 13M Beam 
- 2 Beam Frame 5x7 04.85
- 4 Technic Angular Beam 3x7
- 6 Technic 3M Beam
- 2 Hto V Beam 90°
- 59 Connector Peg W. Friction
- 9 Connector Peg W, Friction 3M
- 12 Conn.Bush W.Fric/Cross Axle 
- 4 Technic 5M Beam 
- 2 Technic 11M Beam 
- 1 Technic 15M Beam 
- 6 Beam 3 M. W/4 Snaps 
- 2 Cross Block 3 M 
- 2 Technic Ang. Beam 3X5 90°
- 1 Rack 13m
- 1 Cross Axle 25M
- 1 Cross Axle 12M
- 2 Cross Axle 9M
- 5 EV3 Cable 250 Mm
- 2 EV3 Color Sensor
- 1 EV3 Ultrasonic Sensor 
- 1 Ms-EV3 Rechargea. Battery
- 1 P-Brick
- 1 Medium Motor
- 1 Large Motor
- 1 Huskylens

# Mobility Management

The selection of the motor is a crucial component in the autonomous navigation system of our vehicle. The LEGO MINDSTORMS EV3 kit offers two distinct motor options: large motors and medium motors. These motors are fundamental to the vehicle’s performance, each with specific characteristics suited to different project needs.

After carefully evaluating our project's specific requirements, we opted to implement a large motor to drive the vehicle's rear wheels. This decision is based on several key considerations. Firstly, the LEGO EV3 large motor provides considerable power, capable of moving the vehicle effectively even under high friction or resistance conditions on the track. Additionally, the precision of the large motor facilitates controlled maneuverability, which is essential for navigating the vehicle accurately around the circuit. Large motors are known for their ability to handle heavier loads and provide superior torque, which is crucial for maintaining the vehicle's stability and speed during the competition.

On the other hand, we decided to use a medium motor for the vehicle's turning and direction-changing functions. This medium motor, also part of the LEGO EV3 set, is ideal for executing precise left and right movements, contributing to greater maneuverability and control in the robot’s movement. The medium motor’s ability to make fine adjustments in direction is crucial for avoiding obstacles and following the color sensor’s indications, which determine the vehicle’s course based on the colors detected on the track. Medium motors are lighter and more compact, making them easier to integrate into the vehicle design without adding unnecessary weight.

Additionally, both types of motors are equipped with built-in rotation sensors, which allow precise control of speed and position. This feature is particularly useful for programming exact movement sequences, ensuring that the vehicle follows the planned path without deviations.

*The large motor operates at 160–170 rpm, with a rotational torque of 20 Ncm and a locked rotor torque of 40 Ncm.
*The medium motor operates at 240–250 rpm, with a rotational torque of 8 Ncm and a locked rotor torque of 12 Ncm.

# Energy Management

The EV3 brick and the entire vehicle are powered by a rechargeable 10V lithium battery. This power source is essential for the continuous operation of the system, as it provides the necessary electricity for all the robot's components. Within the EV3 brick, energy management is complex and efficient, involving multiple switching regulators that are tightly controlled and intertwined. These regulators ensure that the electronic circuit starts up correctly and maintains stable operation.

To protect the EV3 brick from potential short circuits, three strategically placed polyethylene switches have been implemented. Two of these switches are dedicated to the motor controllers, while the third protects the rest of the circuit. Each of these polygonal switches has a holding current of approximately 1.1 A and activates when the current reaches approximately 2.2 A. This protective design ensures that any potential overload in the system is quickly managed, preventing damage to the components and ensuring safe and reliable robot operation.

These protective mechanisms not only extend the life of the EV3 brick but also enhance system efficiency, allowing motors and other electronic components to operate optimally without the risk of electrical failure. The inclusion of these polyethylene switches reflects a detailed and meticulous approach in designing the EV3's energy management system, ensuring that every part of the robot receives the appropriate amount of energy and is protected against any electrical eventuality.

# Schematic Diagram

![S1](https://github.com/ROBOTICAIPTC/New_Line/blob/main/schemes/Slide1.JPG)

![S2](https://github.com/ROBOTICAIPTC/New_Line/blob/main/schemes/Slide2.JPG)

![S3](https://github.com/ROBOTICAIPTC/New_Line/blob/main/schemes/Slide3.JPG)

![S4](https://github.com/ROBOTICAIPTC/New_Line/blob/main/schemes/Slide4.JPG)

![S5](https://github.com/ROBOTICAIPTC/New_Line/blob/main/schemes/Slide5.JPG)

![S6](https://github.com/ROBOTICAIPTC/New_Line/blob/main/schemes/Slide6.JPG)

![image](https://github.com/user-attachments/assets/0069cbe8-da5d-4de6-bea8-eefdda8799c1)

![image](https://github.com/user-attachments/assets/02744b99-3009-47fe-95ff-297e6faa2b9a)


# Assembly instructions

**PHASE 1:** Assembly of the base structure In this in the first phase, our main objective was to build a solid base that would serve as a foundation for the rest of the robot. Stability is critical for any mobile robot, so we start by using robust blocks and connectors, specifically selected for their ability to withstand weight and tension during movement. We ensured that the base provided equal and well-distributed tire clearance on both front and rear axles, which is crucial for maintaining optimal balance during operation. Additionally, special attention was paid to the symmetry of the structure, ensuring that each component was aligned correctly to avoid any tilt or imbalance that could affect the performance of the robot on the circuit.


**Assembly of the rear axle and the steering mechanism** 
https://youtu.be/C4BgjFh31Pw?si=6pkeb3dYI517SGVD


- First assembly phase
![Tercer-Armado](https://github.com/ROBOTICAIPTC/New_Line/blob/main/v-photos/Tercer-Armado.jpg)


**PHASE 2:** Installation of the large motor With the base already assembled, we proceeded to install the large motor, which is essential to drive the movement of the robot. This motor was selected for its ability to provide high torque, allowing for efficient acceleration and constant speed. The motor was coupled directly to the robot’s rear axle, ensuring that power was efficiently transmitted to the rear tires. To do this, we design and assemble a nut circuit that allows optimal power transfer, minimizing energy loss and guaranteeing fluid movement. In addition, yellow pieces were implemented to stabilize the tires, ensuring that they maintained firm and constant contact with the surface. This stability is crucial to maximizing traction, which in turn improves the robot’s ability to move over different types of terrain without losing control.


- Second phase armed
![Segundo-Armado](https://github.com/ROBOTICAIPTC/New_Line/blob/main/v-photos/Segundo-Armado.jpg)


**PHASE 3:** Assembly of the ultrasonic sensor 

The next step was the assembly of the ultrasonic sensor, a critical component for obstacle detection and autonomous navigation of the robot. We decided to place this sensor on the medium engine, taking advantage of the available space and keeping the center of gravity low to avoid possible overturns. The ultrasonic sensor it Is secured with additional parts, carefully selected to guarantee its stability and avoid any vibration that could compromise the detection accuracy. This sensor is designed to measure the distance between the robot and objects in its path, allowing the robot to adjust its path in real time. The accuracy of the sensor is vital, as any error in the measurement could result In collisions or deviations from the road Programmed.


-  Ultrasonic base
![18](https://github.com/ROBOTICAIPTC/New_Line/blob/main/v-photos/18.jpg)


**PHASE 4:** Installation of the medium engine One 

Once the ultrasonic sensor is installed, we move on to placing the medium motor, which is responsible for the lateral maneuverability of the robot. This motor was strategically positioned to control the directional mechanism, allowing the robot to turn both left and right in a precise and controlled manner. To achieve this, we implemented a system composed of a nut and several pieces designed to reinforce the stability of the directional system. The medium motor is configured to respond quickly to signals from the robot’s brain, allowing for smooth turns and effective obstacle avoidance. The stability and support of the tires were also reinforced in this phase, using additional components that ensure that the robot maintains its trajectory even during sharp turns or abrupt changes of direction.


- Fourth phase of assembly
![Primer-Armado](https://github.com/ROBOTICAIPTC/New_Line/blob/main/v-photos/Primer-Armado.jpg)


**PHASE 5:** Placement of the robot brain

Final phase of assembly involves integration of the robot’s brain, which is essentially the central processor that coordinates all of the robot’s actions and responses. This component is crucial, since it manages the signals coming from the sensors and motors, making decisions in real time based on pre-established programming. To ensure solid and functional integration of the brain with the rest of the system, we built a support structure using rectangular pieces. This structure not only supports the weight of the robot’s brain, but also provides secure mounting points for the color sensors, which are critical for navigation and signal detection on the track. Each part was selected and placed with precision, ensuring that the robot’s brain is protected from vibrations and shocks, while the sensors are optimally positioned to capture information from the environment with maximum efficiency.

-
-  . Fifth phase of assembly
- ![17](https://github.com/ROBOTICAIPTC/New_Line/blob/main/v-photos/17.jpg)


**FASE 6:** In Phase 6, we implemented a fixed structure to integrate a Huskylens vision sensor. This vision sensor provides advanced capabilities in the detection and recognition of multiple targets, offering high-level technological assistance. The incorporation of this system not only enhances the accuracy in mapping and analyzing the environment but also optimizes the robot’s trajectory and maneuvers.

- Sixth phase of assembly

![image](https://github.com/user-attachments/assets/1092bdc8-cf70-40ad-876e-3518812fca3f)

- Track reconstruction
![20](https://github.com/ROBOTICAIPTC/New_Line/blob/main/v-photos/20.jpg)

# Energy Management and Steering

**CONNECTION TO**	

Large Motor: This essential component facilitates the movement of the robot’s rear tires, providing the power and precision necessary to maneuver efficiently on various surfaces and conditions.

**CONNECTION B**

Medium Motor: This motor allows the robot to rotate and change direction, facilitating precise movements to the left and right, and contributing to greater maneuverability and control in its movement.

**CONNECTION 4**	

Ultrasonic Sensor: This sensor allows the robot to detect objects at different distances and uses this information to determine the appropriate moment to determine direction changes, thus guaranteeing safety and precision in its movements.

**CONNECTION 3 AND 2**

Color Sensor: This sensor allows detecting the colors of the cubes in red and green on the track, allowing the robot to decide which way it should turn.


**CONNECTION 1**

Huskylens: The HuskyLens is a smart camera equipped with an integrated processor that enables the detection and recognition of objects, colors, faces, and more.

# Code explanation

**Start:** When the robot is turned on, the large motor begins to rotate at maximum speed (100%).

**Detection:** As the robot moves, it keeps track of the distance to objects in front of it. If it finds an object that is less than 63 centimeters away, a sequence of movements is activated.

**Sequence of movements:**

**Medium motor:** Rotates in the opposite direction to the direction of the main movement (-0.13 rotations). This causes the robot to deviate slightly to one side

**Large motor:** Rotates one full rotation. This makes the robot move forward a little and get closer to the detected object.

**Medium Motor:** Rotates again, but this time in the same direction as the main movement (0.13 rotations). This causes the robot to return to its original trajectory.

**Repetition:** Steps 2 and 3 are repeated over and over until a specific condition is met. This condition is time related and is set during robot calibration.

**Why is this done?**

This sequence of movements allows the robot to systematically explore its environment and avoid collisions with the outer and inner edge of the track. Upon detecting the edge, the robot makes a turn, moves forward and rectifies its direction.

(This process is repeated, but in the opposite direction. That is, the large motor begins to rotate clockwise and the sequence of movements of the medium motor is also reversed.)


# Controller/Robot


Processor: ARM9, 300 MHz.

Memory RAM: MB.

Storage: 16 MB flash memory and microSD card slot up to 32 GB.

Operating System: Kendel Linux.

Operating Voltage: 6-9V DC.

Rechargeable Battery: EV3 lithium ion battery

(10V).

Battery Life: Approximately 6 hours with continuous use of the rechargeable battery.


# Sensors and error margins

Color Sensor: Accuracy: ±1% Modes: Color, Light Reflection, Ambient Light Margin of Error: Depends on the quality of the light and the color of the object, it may vary but generally within ±5%.

Ultrasonic Sensor: Range: 3 cm to 255 cm. Accuracy: ±1cm. Margin of Error: May be greater in conditions of high acoustic interference.

**ENGINES**

Large Motor: Torque: 40 N.cm (Newton centimeters) RPM: 160-170

Medium Motor: Torque: 8 N.cm RPM: 240-250


# Huskylens

**Technical Specifications:**

Camera Resolution: 320x240 pixels.

Processor: Kendryte K210 AI Accelerator.

Detection Capabilities: Color detection, facial recognition, object tracking, QR code detection.

Communication Interfaces: I2C, UART.

Detection Distance: Up to 2 meters for color detection.

Recognition Speed: Capable of processing up to 30 frames per second.
Integration with EV3:

**Physical Connection:**

The HuskyLens connects to the EV3 brick via the UART interface. The following pins are used:

VCC: 5V Power Supply.

GND: Ground.

TX: Data transmission from the HuskyLens.

RX: Data reception to the HuskyLens.

**Initial Setup:**

Color Calibration: Start the HuskyLens and select the color detection mode.

Green and Red Color Detection: Place green and red objects in front of the camera and follow the on-screen instructions to calibrate the detection.

Save Configuration: Once calibrated, save the configuration in the HuskyLens memory.
Communication between HuskyLens and EV3

The EV3 communicates with the HuskyLens through the UART port, receiving real-time data on detected colors. If a red obstacle is detected, the EV3 executes a right turn; if green is detected, the EV3 continues straight or performs the corresponding action.

**Source Code:**

ev3dev2: To program the EV3 in Python.

(Installation details of the program in the following link: https://www.ev3dev.org/docs/getting-started/)
Tests and Results:

**Tests Performed:**

Lighting Conditions: Tests were conducted under different lighting conditions to ensure that the HuskyLens correctly detects red and green colors.

Detection Distance: Tests at different distances (30 cm, 50 cm, 1 meter) to verify detection accuracy.

Response Speed: Evaluation of how quickly the EV3 responds to detections by the HuskyLens.

**Results Obtained:**

Successful Detection: The HuskyLens achieved 95% accuracy in color detection at a distance of up to 1 meter.

Response Time: The average response time was 0.2 seconds from detection to the execution of the action on the EV3.

**User Manual:**

Instructions for Use:

Power On the HuskyLens: Connect the HuskyLens to the EV3's power port.

Select Detection Mode: Use the HuskyLens menu to select the color detection mode.

Calibrate: Follow the on-screen instructions to calibrate the camera according to the environment.

Operation: Once calibrated, the HuskyLens will be ready to send data to the EV3


 **Flowchart**

 ![image](https://github.com/user-attachments/assets/80aeb199-b745-4d47-bc62-298f07b4dc50)

# Team-Photos

-Formal Photos
![equipo](https://github.com/ROBOTICAIPTC/New_Line/blob/main/t-photos/20240702_122028.png)

- Funny Photo
![divertida](https://github.com/ROBOTICAIPTC/New_Line/blob/main/t-photos/13.jpg)

-  Coding
![15](https://github.com/ROBOTICAIPTC/New_Line/blob/main/t-photos/15.jpg)

* `v-photos` contiene 6 fotos del vehículo (de cada lado, desde arriba y desde abajo)

# Vehicle-Photos

- Top View
![Superior](https://github.com/user-attachments/assets/2ba4dbb5-cec7-445a-a341-bc51f382fe76)

- Front View
![Frontal](https://github.com/user-attachments/assets/8119c901-8f25-4ee5-b252-b75c6a36dc92)

- Rear View
![Posterior](https://github.com/user-attachments/assets/a937959c-5cd8-463e-a5d4-f86f1fa7de98)

- Right View
![Derecha](https://github.com/user-attachments/assets/4afbdbbd-4933-4450-b754-0b8131e90e7b)

- Left View
![Izquierda](https://github.com/user-attachments/assets/39ea51e1-dcd0-4a6f-bc3f-5b77ed57dd87)

- Bottom View
![Inferior](https://github.com/user-attachments/assets/ed821f36-36ae-47c2-8fb2-f8757a8e89c1)

- Programming Tests
![21](https://github.com/ROBOTICAIPTC/New_Line/blob/main/v-photos/21.jpg)

- Aerodynamics Simulator Tests
![22](https://github.com/ROBOTICAIPTC/New_Line/blob/main/t-photos/22.jpg)


* `video` contiene el archivo video.md con el enlace a un video donde existe una demostración de manejo

# Obstacle Round
https://youtube.com/shorts/4RbNTx60fGI?si=cP3oHAXRoECWtf_m

# Open challenge round
https://youtu.be/KI8TZq1QNDs

* `schemes` contiene uno o varios diagramas esquemáticos en formato JPEG, PNG o PDF de los componentes electromecánicos que ilustran todos los elementos (componentes electrónicos y motores) utilizados en el vehículo y cómo se conectan entre sí.

# Recommendations and tips

1.	**Robot Orientation:** Before initiating any operation, it is crucial to carefully verify the robot’s position. Ensure that the direction it is aligned with corresponds to the planned trajectory. An error in the initial Orientation can lead to significant deviations during the course, affecting the precision and effectiveness of the execution of programmed tasks. Consider using markers or reference points to facilitate alignment and ensure consistency in each attempt.


2.	**Battery Status:** The charge level of the robot’s brain batteries is a crucial factor in its overall performance. Before any operation, check that the batteries are charged to 100%. A battery with a low charge level can result in the robot not functioning at optimal power, leading to slow or inaccurate movements, and in the worst case, failures in program execution. Maintaining batteries in good condition and fully charging them before each use ensures more stable and predictable robot performance.


3.	**Connections between Brain, Sensors, and motors:** The physical connections between the robot’s brain and sensors and motors are fundamental for proper signal transmission and command execution. Ensure that all connections are securely fastened and free from damage. Any disconnection or poor connection can result in malfunctioning of the robot, ranging from a sensor failing to respond to inefficiencies in motor movements. Conducting a thorough review of connections before starting the robot can prevent unexpected errors during competitions or tests.
                                             
* `src` contiene código de software de control para todos los componentes que fueron programados para participar en la competencia

 # Program version

Lego Mindstorms EV3

v.1.5.3

https://education.lego.com/en-us/downloads/mindstorms-ev3/software/

* `models` es para los archivos de modelos utilizados por impresoras 3D, máquinas de corte por láser y máquinas CNC para producir los elementos del vehículo. Si no hay nada que agregar a esta ubicación, se puede eliminar el directorio.


* `other` es para otros archivos que pueden usarse para entender cómo preparar el vehículo para la competencia. Puede incluir documentación sobre cómo conectarse a un SBC/SBM y cargar archivos allí, conjuntos de datos, especificaciones de hardware, descripciones de protocolos de comunicación, etc. Si no hay nada que agregar a esta ubicación, se puede eliminar el directorio.
