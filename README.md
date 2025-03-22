# Voice Command Wheelchair: Arduino-Based Smart Mobility Solution

![Voice Command Wheelchair](docs/images/wheelchair_banner.png)

## Project Overview
The **Voice Command Wheelchair** is an **Arduino-powered smart wheelchair** designed to assist individuals with mobility impairments. It uses **voice recognition**, **motor control**, and **obstacle avoidance** to provide hands-free navigation.

## Features
- **Voice-Controlled Navigation**: Move forward, backward, left, and right using voice commands.
- **Obstacle Avoidance**: Uses ultrasonic sensors to detect and avoid obstacles.
- **Bluetooth Remote Control**: Allows manual control via a smartphone app.
- **Speed Control**: Adjusts speed based on environment and user preference.
- **Battery Monitoring**: Alerts when power is low.

## Components Used
| Component | Purpose |
|-----------|---------|
| Arduino UNO R3 | Main microcontroller |
| Voice Recognition Module (V3) | Detects user voice commands |
| Motor Driver L298N | Controls the wheelchair's motors |
| Ultrasonic Sensors | Detects obstacles |
| Bluetooth HC-05 Module | Allows smartphone remote control |
| 12V DC Motors | Drives the wheelchair |
| 12V Battery | Power source |

## System Architecture
![System Architecture](docs/diagrams/system_architecture.png)

## Installation & Setup
1. **Clone the Repository:**
   ```bash
   git clone https://github.com/anikmd/VoiceCommandWheelchair.git
   cd VoiceCommandWheelchair
   ```
2. **Upload Firmware to Arduino:**
   - Open `software/firmware/voice_wheelchair.ino` in **Arduino IDE**.
   - Connect your Arduino UNO.
   - Select the correct board and COM port.
   - Upload the code.
3. **Hardware Setup:**
   - Connect **Voice Module, Motor Driver, and Sensors** as per the **circuit diagram** in `docs/diagrams/circuit_diagram.png`.
4. **Power On & Test:**
   - Ensure the wheelchair receives **12V power**.
   - Test voice recognition and Bluetooth functionality.

## Usage Instructions
- **Voice Commands:**
  - Say "Forward" → Moves forward
  - Say "Backward" → Moves backward
  - Say "Left" / "Right" → Turns in that direction
  - Say "Stop" → Stops the wheelchair
- **Obstacle Avoidance:**
  - The wheelchair will automatically stop if an obstacle is detected.
- **Bluetooth Control:**
  - Use a smartphone app to manually navigate.

## Test Results
| Module | Testing Success Rate |
|--------|---------------------|
| Voice Recognition | 95% |
| Motor Control | 100% |
| Obstacle Detection | 90% |
| Bluetooth Remote | 98% |

## Future Improvements
- **Autonomous Navigation**: AI-based path planning.
- **Fall Detection**: Alerts emergency contacts in case of a fall.
- **IoT Integration**: Remote monitoring via cloud.

## Contact
For any inquiries, please email **mdanikk630@gmail.com** or open an [issue](https://github.com/anikmd/VoiceCommandWheelchair/issues) on GitHub.

---
🚀 _Empowering Mobility with Technology!_

