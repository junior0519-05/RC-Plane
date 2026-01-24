# ESP-NOW RC FLIGHT

A high performance, fully designed custom 3 channel RC plane using a CLARK-Y airfoil design. 

_*created by Junior Ortega and Bryan Diaz; Focus in embedded systems, wireless communication, and general/end to end engineering._

# Overview
M.M.26 is a high-performance, fixed-wing RC aircraft designed and manufactured using additive manufacturing and custom embedded systems. The project focuses on end-to-end system development, including airframe design, electronics integration, and a custom 2.4 GHz radio communication stack built from the ground up using ESP-NOW.

Unlike typical RC builds that rely on off-the-shelf transmitters and receivers, this project prioritizes deep engineering control, low-latency communication, and rapid iteration through modular design.

# Technologies and Components 
## Hardware Related
- Microcontroller: ESP32
- Propulsion: 2200 KV Brushless DC motor
- Mechanics: 9g Servo motors
- Control: Joysticks

## Software Related
- Programming: Arduino C++ (Receiver: receive values from transmitter and map them to correspond to each motor task. Transmitter: read joystick input values and have them get sent to receiver.)
- CAD: Fusion 360 (Design each component of the airplane and section them into multiple 3D printable pieces with respect to size.)
- Wireless Protocol: ESP-NOW

# System Architecture
## Airfraime
- Custom fixed-wing design optimized for high lift-to-weight ratio
- Thin-wall, surface-based modeling to reduce mass while maintaining rigidity
- Modular fuselage and wing sections for fast repairs and iteration

## Electronics & Control
- ESP32-based onboard controller
- Custom hand-held transmitter using ESP-NOW for direct peer-to-peer communication
- Joystick inputs mapped to PWM outputs for:
  -   Brushless motor ESC
  -   Control surface servos
- Adjustable battery mounting system for Center of Gravity (CoG) tuning

# Pictures

## Physical Model
![Plane - main view](https://github.com/user-attachments/assets/18198f52-6249-48ca-9e67-01ad37c2b8c7)

_Front view of plane_
![Plane_Rearview](https://github.com/user-attachments/assets/e84a4736-49ca-4d34-bbe5-239a6cf4dc8b)
_Rear view of plane_

![Plane_Tail](https://github.com/user-attachments/assets/227094b0-7500-4377-bf14-16ee6552f013)
_Tail mechanics_


## Fusion
<img width="1231" height="781" alt="image" src="https://github.com/user-attachments/assets/e6d045a7-2d43-4123-a1d2-dbe1535500bf" />
 
_Fusion design with all pieces parted out to print_


