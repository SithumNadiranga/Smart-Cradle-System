# Smart Cradle System
![WhatsApp Image 2024-10-15 at 02 27 02_afc45234](https://github.com/user-attachments/assets/b5692d79-67ac-4deb-9df7-20dada852530)

The Smart Cradle System is an innovative solution aimed at helping parents ensure the safety and comfort of their babies through the integration of modern sensor and actuator technologies. By transforming traditional cradles into intelligent guardians, this project seeks to provide real-time monitoring and intervention to address various aspects of infant care.

# Introduction
Ensuring the well-being of infants is a primary concern for parents. Our Smart Cradle System introduces a proactive, tech-driven approach to baby care. It uses sensors to monitor the baby’s presence, movements, moisture levels, and sound to detect crying, while actuators automate soothing mechanisms like gentle rocking.
The goal of this project is to provide peace of mind to parents by offering a system that constantly monitors the baby’s status and takes appropriate actions based on real-time data.

# Features
* Sound Sensor: Monitors baby’s crying and alerts parents and start oscillate the cradle.
* Rain Sensor: Detects if the bed is wet, triggering an alert for diaper change.
* IR Sensors: Monitors the baby’s position, ensuring safety during unusual movements or when the baby tries to sit up .
* DHT11 Sensor: Maintains an optimal temperature in the cradle for the baby's comfort.
* Cradle Automation: Automatically rocks the cradle c when the baby cries.
* Create own speed measure sensor of Cradle
* Monitors baby’s real-time conditions
* Fan: comfortable environment

# Objectives
* Moisture Detection: Identify wetness in the cradle and alert parents using a buzzer.
* Noise Detection: Use sound sensors to recognize baby cries and trigger appropriate responses.
* Safety Monitoring: Implement optical and weight sensors to track the baby's position and presence in the cradle.
* Automated Soothing: Activate motors to rock the cradle and play music when necessary, ensuring a calm environment for the baby.
* Environment Control: Use temperature sensors to keep the cradle's sleeping environment optimal for the baby

# Technologies Used
* LabVIEW: For programming and processing real-time sensor data.
* Sensors: sound, optical/infrared, rain, and temperature sensors.
* Actuators: Motors for rocking, fan for comfortable environment and speakers for audio feedback.
* HC-06 Bluetooth Module: Enables wireless communication between the system and a mobile device for monitoring the real time data .

# Hardware Components
* Sound Sensor: Recognizes the baby’s cries or sounds of distress.
* Rain Sensor: Senses if the baby has wet the bed.
* IR Sensor: Tracks unusual movements, such as the baby sitting up.
* DHT11 Sensor: Monitors and controls the cradle’s internal temperature.
* Motor: Activates to rock the cradle when the baby cries.
* Buzzer and Speaker: Alerts and soothes based on sensor input.
* Fan: Automatically activated by LabVIEW if temperature or humidity is outside comfort zones.
* HC-06 Bluetooth Module: monitoring the real time data

# Software Design
The Smart Cradle System utilizes a LabVIEW-based software interface to process data collected from sensors in real-time. It ensures efficient decision-making by:
* Continuously analyzing sensor readings.
* Triggering actuators based on predefined thresholds (e.g., rocking the cradle when the baby cries).
* Notifying parents with audio and visual alerts if any critical conditions arise

# System Architecture
The system architecture involves multiple sensors connected to an Arduino microcontroller, which communicates with a LabVIEW interface. This setup allows for real-time monitoring and response based on sensor inputs.
* Input Sensors: sound, optical, rain, and DHT11 Sensor.
* Control Logic: Implemented in Arduino and LabVIEW, processing sensor data to trigger the appropriate actuator response.
* Output Actuators: Motors (rocking), buzzer (alerts), fan, monitor.

# Future Enhancements
* Mobile App Integration: Enable remote monitoring and control via a mobile app.
* Camera Integration: Add a camera to allow parents to view their baby remotely.
* Advanced Cry Analysis: Implement machine learning to better understand different types of cries and respond accordingly.

## Photos for LabView Block diagram
* Block diagram for sensor and Actuators.
![Screenshot 2024-10-06 151215](https://github.com/user-attachments/assets/76b23d0c-af7d-45db-9a9e-2be085b1723a)

*  Block diagram for own speed measure sensor.
![Screenshot 2024-10-06 150802](https://github.com/user-attachments/assets/181ee099-f539-4113-9f68-aa7328aab10a)

* Front Panel for indication panel
![Screenshot 2024-10-06 151154](https://github.com/user-attachments/assets/410e7578-8240-4683-91c0-2bf933641242)

* Front Panel for Speed meter
![Screenshot 2024-10-06 150817](https://github.com/user-attachments/assets/2e7b4873-207f-42fe-aec1-eb1a71a9d6cb)

##  Monitoring the real time data
![WhatsApp Image 2024-10-15 at 02 27 02_bcd35479](https://github.com/user-attachments/assets/7303855a-4f65-4b98-bf6a-092b9fc2055d)

## Working Video of Smart Cradle System



