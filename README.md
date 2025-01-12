# Smart-Irrigation-System

Overview

The IoT-Based Smart Irrigation System is designed to automate and optimize the watering of plants using sensors, actuators, and remote control through a mobile app. It ensures efficient water usage while providing plants with optimal care, making it a sustainable solution for agricultural and gardening applications.

System Workflow


1. Data Collection

Soil Moisture Sensor:

Continuously measures the moisture level in the soil.

Provides real-time data to determine whether the soil is dry or sufficiently moist.

Temperature Sensor (DHT11/DHT22):

Measures the ambient temperature.

Provides environmental data that affects irrigation requirements.


2. Data Processing

The ESP32 Microcontroller serves as the system's central processing unit (CPU).

It collects data from the soil moisture sensor and temperature sensor.

Based on predefined thresholds (e.g., low soil moisture or high temperature), the ESP32 determines if irrigation is needed.


3. Decision Making

Low Soil Moisture:

If the soil moisture level is below the threshold:

The relay module activates the water pump.

The servo motor opens the water valve, allowing water to flow to the plants.

Sufficient Soil Moisture:

If the soil moisture level is above the threshold:

The relay module deactivates the water pump.

The servo motor closes the water valve.

High Temperature:

If the temperature exceeds a predefined limit (e.g., 30°C):

The system may activate the water pump sooner or extend the watering duration to prevent overheating or dehydration of plants.


4. Remote Monitoring and Control

The system connects to the Blynk app via Wi-Fi, enabling users to monitor and control it remotely.

Key Features on Blynk App:

Real-time display of soil moisture and temperature readings.

Manual control to turn on/off the water pump or adjust the valve position.


5. Automation and Efficiency

Automation: Irrigation is managed based on actual plant needs, reducing water wastage.

Energy Efficiency: The water pump is activated only when required, optimizing energy use.


6. Alerts and Notifications

Users receive alerts via the Blynk app in the following scenarios:

Critically low soil moisture requiring immediate attention.

System anomalies, such as sensor malfunction or pump failure.


Features and Advantages

Features

Automatic irrigation based on soil moisture levels and temperature.

Remote monitoring and control through the Blynk app.

Alerts for critical conditions or malfunctions.

Scalable for larger agricultural or gardening settings.


Advantages

Water Conservation: Prevents overwatering by irrigating only when necessary.

Remote Accessibility: Users can monitor and control the system from anywhere.

Convenience: Minimizes manual intervention, allowing more efficient management of plants.

Scalability: Can expand to cover multiple zones or plant types.

Summary

The IoT-Based Smart Irrigation System continuously monitors soil moisture and temperature levels to automate irrigation effectively. By integrating sensors, actuators, and a user-friendly mobile app, the system ensures optimal watering while conserving water and energy. With features like remote control and alerts, it provides convenience and reliability for plant care in both small-scale and large-scale applications.
