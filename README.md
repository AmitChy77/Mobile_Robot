A ROS2-based teleoperation robot using a Rover5 2-motor chassis and two Raspberry Pis. A PS4 controller connected to the base station Pi drives the robot and rotates a servo-mounted camera, while the robot Pi streams live video back to the operator. The system uses ROS2 Jazzy, joy, teleop_twist_joy, and custom motor/servo nodes for differential drive control, camera panning, and real-time video streaming over Wi-Fi using ROS_DOMAIN_ID.

**Features:**
Wireless PS4 joystick control
Differential drive for Rover5 motors
Servo-based camera panning (right stick)
Live USB camera feed via ROS2
Distributed control with two Raspberry Pis
ROS2 multi-machine communication over Wi-Fi
Modular Python nodes for motors, camera, and servo

**Hardware:**
1. Rover5 2-motor chassis (no encoders)
2. Raspberry Pi 4/5 ×2
3. PS4 DualShock Controller
4. USB Camera
5. Servo motor (SG90) for camera pan
6. Motor driver (TB6612FNG / L298N)
7. Battery pack

**Software Stack**:
1. Ubuntu 24.04
2. ROS2 Jazzy
3. Custom Teleop using PS4 Controller
4. Custom motor_node (GPIO control)
5. Custom servo_driver_node
