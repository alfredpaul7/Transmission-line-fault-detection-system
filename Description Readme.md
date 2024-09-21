
# Transmission Line Fault Detection System

### Overview
This project, **Transmission Line Fault Detection System**, was developed to detect and identify faults in transmission lines, including:

- **Line to Line Fault**
- **Line to Ground Fault**
- **Line to Neutral Fault**

When a fault is detected, the system sends an SMS to the nearest Electricity Board and residences in the vicinity, specifying the exact location of the fault. The system is also integrated with the **Internet of Things (IoT)**, enabling the Electricity Board to monitor real-time data such as current and voltage values for enhanced monitoring and faster resolution.

### Award and Recognition
The project won **Third Prize** in the **India Automation Challenge** held as part of the **Automation Expo** in Mumbai.

### Features
- **Fault Detection**: Identifies and differentiates between different types of faults in transmission lines.
- **SMS Alerts**: Sends alerts to the nearest Electricity Board and residents with fault location details via SMS.
- **IoT Integration**: Provides real-time data monitoring, including current and voltage values, through IoT interfaces.
  
### Technologies and Components Used
- **Programming Language**: C++ 
- **Development Environment**: Arduino IDE
- **Communication**: SIM800A module for SMS alerts and GPS module to find the exact location of the fault
- **Microcontroller**: Arduino and ESP32
- **Sensors**: Current and Voltage sensors for real-time data monitoring
- **Relays**: For controlling circuit connections
- **IoT Integration**: ESP32 for real-time data communication

### Components List
- **Arduino Uno/ESP32**: Microcontrollers used for processing and IoT connectivity.
- **SIM800A Module**: For sending SMS alerts.
- **Current and Voltage Sensors**: For measuring transmission line parameters.
- **Relays**: For controlling circuit disconnections in case of faults.
- **Wires and Connectors**: For interfacing sensors and other components.
- **Power Supply**: Required to operate the system.

### System Architecture
The system continuously monitors the transmission line for any anomalies in current and voltage values. Upon detecting a fault, it identifies the type of fault (Line-to-Line, Line-to-Ground, or Line-to-Neutral), sends an SMS alert to predefined contacts, and updates the IoT dashboard with real-time data from the transmission lines.

### How to Use
1. **Set Up**: Connect all components including the sensors, SIM800A module, and relays to the Arduino/ESP32 as per the circuit diagram.
2. **Upload Code**: Use the Arduino IDE to upload the fault detection code to the Arduino/ESP32.
3. **Monitor Data**: The IoT dashboard can be used to view real-time data, including voltage and current.
4. **Receive Alerts**: If a fault is detected, an SMS alert will be sent to the nearest Electricity Board and residences with fault location details.



### Conclusion
This project aims to improve the efficiency and response time in detecting and resolving transmission line faults, helping prevent larger-scale outages and ensuring safety for residences and infrastructure.
