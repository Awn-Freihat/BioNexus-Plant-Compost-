# BioNexus Smart Compost Bin: 2026 Evolution

The 2026 version of **BioNexus** is an autonomous, IoT-enabled compost management system designed to transform organic waste into nutrient-rich soil. This year's iteration focuses on professional structure, advanced connectivity, and data-driven decision-making.

---

## 🚀 Key Improvements (Iteration 2)

* 
**Brain Upgrade**: Transitioned from the Arduino Uno to the **ESP32**, providing native Wi-Fi and Bluetooth for real-time remote monitoring.


* 
**Physical Architecture**: Moved from an exposed "all-in-one" design to a **dual-chamber system**.


* 
**Wet Zone**: A dedicated plastic bin for compost to ensure leak prevention.


* 
**Dry Zone**: A 3D-printed side enclosure to keep electronics safe from moisture.




* 
**Actuator Isolation**: The mixing motor is now mounted **outside** the lid with only the shaft entering the bin, reducing hardware failure risk.


* 
**IoT Dashboard**: Replaced local-only displays with a **cloud-based interface** (via Blynk or ThingSpeak) to track data anywhere.



---

## 🛠️ System Features

* 
**Autonomous Decision Logic**: The system automatically transitions between **Resting, Pumping (Hydration), and Mixing (Aeration)** states based on live sensor data.


* 
**Environmental Sensing**: Tracks temperature, humidity, and moisture trends using DHT11 and dedicated water-level sensors.


* 
**Spatial Awareness**: Uses an **HC-SR04 Ultrasonic Sensor** to estimate bin fill-levels, operating effectively even in total darkness.


* 
**Dual Control**: Supports both automated sensor-driven cycles and manual overrides via a phone app or IR remote.



---

## 📋 Materials & Components

| Category | Components |
| --- | --- |
| **Control** | ESP32 Dev Board, 1.3" OLED Display, IR Receiver 

 |
| **Sensors** | DHT11 (Temp/Humidity), Water Level Sensor, HC-SR04 

 |
| **Actuators** | Geared DC Motor (Mixing), Mini Water Pump, Servo Motor 

 |
| **Power** | 18650 Li-ion Battery, TP4056 Charger, 3.3V Regulator 

 |
| **Mechanical** | Plastic Bin, 3D-Printed Enclosures, PG7 Cable Glands, Metal Shaft 

 |

---

## 🧪 Scientific Objective

BioNexus addresses the global food waste crisis by automating the composting process, which often fails due to human error. By maintaining optimal moisture and aeration levels autonomously, the system accelerates decomposition and prevents methane-heavy anaerobic conditions.

---

## 📄 License & Open Source

This project is licensed under the **MIT License**. We encourage the community to fork our [GitHub Repository]() and contribute to sustainable waste intelligence.
