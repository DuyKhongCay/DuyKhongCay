# Hi, I'm Duy (@DuyKhongCay) 👋

Robotics & Embedded Systems Engineer focusing on real-time hardware-software co-design, industrial edge computing, and autonomous mobile manipulation.

---

### 🔧 Tech Stack & Expertise
* **Robotics & Middleware:** ROS 2 (rclcpp/rclpy), ros2_control, Nav2, MoveIt 2, LeRobot, OpenCV.
* **Embedded & Firmware:** STM32 (ARM Cortex-M), FreeRTOS, LwIP (TCP/IP), Bare-metal C, SPI/DMA, UART, I2C.
* **Edge AI & Acceleration:** HailoRT (Hailo-8/8L NPU), YOLOv8, GStreamer pipeline.
* **Industrial & Systems:** Industrial I/O control, Ethernet Edge Gateways, M2M protocols, C# / ASP.NET Core (MES).

---

### 🚀 Highlighted Projects

#### 🤖 [LeKiwi ROS 2 Workspace](https://github.com/DuyKhongCay/lekiwi_ros2)
A production-grade ROS 2 workspace for the **LeKiwi Mobile Manipulator** (6-DoF arm + 3-wheel omnidirectional base):
* **Hardware Abstraction:** Custom `ros2_control` SystemInterface managing 9 Feetech STS3215 servos over a 1 Mbps serial bus and ICM-20948 9-DoF IMU via I2C.
* **Edge Perception:** Accelerated dual-camera GStreamer pipeline with Hailo-8/8L NPU running real-time YOLO piece detection and FEN generation.
* **Navigation & Manipulation:** AprilTag arena localization (solvePnP), Nav2 holonomic navigation, MoveIt trajectory execution, and native Hand-Eye calibration.

#### ⚡ [Industrial I/O & Communication Gateway](https://github.com/DuyKhongCay/Industrial-IO-and-Communication-Gateway)
Cost-optimized edge gateway firmware running on STM32F103 (ARM Cortex-M3) designed for factory floor automation:
* **Real-time Architecture:** Multi-threaded FreeRTOS system with prioritized network interrupt handling and mutex-guarded SPI/DMA driver for ENC28J60 Ethernet.
* **Network & M2M:** Tuned LwIP TCP/IP stack running a TCP command server, embedded HTTP web dashboard, and UART CLI to bridge SCARA robots and sensors.
* **Safety & Reliability:** Deterministic command queue with logic timeout pauses, link-loss fail-safes, and continuous I/O health monitoring.

---

### 📬 Connect with me
* **GitHub:** [@DuyKhongCay](https://github.com/DuyKhongCay)
* * **Email:** [nguyendangduy7112003@gmail.com](mailto:nguyendangduy7112003@gmail.com)
