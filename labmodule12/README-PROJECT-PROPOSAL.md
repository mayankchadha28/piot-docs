# Lab Module 12 - Semester Project Proposal

## Realtime patient room monitoring system using IoT

## Description

Describe your idea in 1 paragraph (at least 2 or 3 sentences).

Develop a system to monitor and control temperature, pressure, and humidity in hospitals, ensuring optimal conditions for patient comfort and recovery in wards, as well as preserving the quality and efficacy of medicines and medical equipment in storage areas. This solution enhances patient care while safeguarding critical healthcare resources.

## What - The Problem 

What problem are you trying to solve and why does it matter? Write 1 to 2 paragraphs in response.

The problem I tackled was ensuring precise monitoring and control of environmental conditions—specifically temperature, pressure, and humidity—in hospital settings. Maintaining optimal conditions is crucial for two primary reasons: patient care and the preservation of medical resources. In patient wards, an unsuitable environment can lead to discomfort, delayed recovery, or even worsened health outcomes. Simultaneously, medical equipment and medicines often require stringent storage conditions to maintain their efficacy and prevent damage, which could compromise patient safety and lead to significant financial losses for healthcare facilities.


## Why - Who Cares? 

Why do you care about this particular problem? Write 1 to 2 paragraphs in response.

This issue matters because hospitals are environments where lives are at stake, and even minor deviations in environmental conditions can have significant negative effects. By addressing this challenge, we ensure a higher standard of patient care, protect valuable medical resources, and support healthcare providers in delivering consistent, reliable treatment. Solving this problem contributes to more efficient hospital operations and better health outcomes, making it a critical area for innovation and improvement.


## How - Expected Technical Approach

How do you plan to tackle this problem technically?

Include a high-level design diagram depicting your planned technical approach - it does not need to be final, but it must include the CDA, GDA, and cloud services you plan to use, as well as the protocol(s) you will use for communicating between the devices and the cloud.

Write 1 to 2 paragraphs describing your diagram.

![Block Diagram](/images/block-diagram.png)

Developed a secure end-to-end IoT system for monitoring and controlling temperature, humidity, and pressure, with implementations for both the constrained device (using Python) and the gateway device (using Java). The system leverages the MQTT protocol to enable real-time communication between devices.

Local thresholds can be configured for each parameter, triggering automatic HVAC actuation when these thresholds are breached. Sensor data is visualized on a cloud platform, which also facilitates sending actuation commands remotely. The architecture is scalable, allowing deployment of multiple sensors while a centralized gateway efficiently manages communication with the cloud.

This robust system ensures seamless integration, real-time monitoring, and control, making it ideal for applications requiring automated environmental management.


## Results - Expected Outcomes 

If your project is successful, what outcome do you expect (e.g. what will happen if everything works)? Write 1 to 2 paragraphs describing your expected outcomes.

The project allowed me to emulate an entire IoT infrastructure for healthcare. I emulated sensors and actuators, triggered events from the cloud to control actuators. This leads to an effective way of managing the environment temperatures to provide accessibility and control in healthcare environments. 

EOF.
