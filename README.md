# 🌊 Hybrid ROV for Microplastic Waste Filtration & Collection

📝 Project Overview

This project focuses on designing a Hybrid Remotely Operated Vehicle (HROV) that can automatically detect, collect, and filter plastic waste (including microplastics) from freshwater bodies. The goal is to reduce water pollution while ensuring that only clean water is returned back into the environment.

✅ What We Implemented

Mechanical Collection & Filtration System

Built a prototype filtration mechanism where water is sucked using a DC mini underwater pump, passed through a fine mesh filter, and plastics are separated while clean water is returned.

Added a one-way drainage valve to ensure smooth flow and prevent clogging.

Designed an automatic storage mechanism to move separated plastics into a storage compartment without manual intervention.

Movement & Navigation

Integrated brushless DC motors with propellers for underwater movement.

Powered by a 12V battery for mobility and continuous operation.

Sensing & Detection

Used ultrasonic sensors to detect obstacles and avoid collisions.

Added a camera sensor connected to a machine learning model trained to identify plastics in water.

Location Tracking

Incorporated a GPS module to track and monitor the location of the HROV during operation.

Prototype Demonstration

Tested the system in a controlled setup (water bowl with plastic waste) to demonstrate the plastic-water separation process.

🚀 Next Steps (Planned Improvements)

Advanced Filtration: Implement multi-layer mesh filters to capture smaller plastic particles and microplastics without clogging.

Smart Automation: Upgrade with IoT connectivity for remote monitoring and data collection.

Scalability: Extend the system for larger ponds and lakes with improved motor power and robust storage.

AI Enhancement: Improve the ML plastic detection model for higher accuracy and real-time decision-making.

⚙️ Tech & Components Used

Electronics & Sensors: Arduino Board, Ultrasonic Sensors, Relay Module, Camera Sensor, GPS Module

Power & Motors: 12V Battery, Brushless DC Motors with Propellers

Filtration & Storage: DC Mini Underwater Pump, Fine Mesh, One-Way Valve, Plastic Container

Programming: C++ (Arduino), Python (for ML model training)
