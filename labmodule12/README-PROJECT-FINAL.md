# Lab Module 12 - Semester Project - Final Write-up

NOTE: Be sure to implement all the Lab Module 12 requirements listed at [Lab Module 12](https://github.com/orgs/programming-the-iot/projects/1#column-10488565).


## Realtime patient room monitoring system using IoT

## Description

Describe your idea in 1 paragraph (at least 2 or 3 sentences).

- Develop a system to monitor and control temperature, pressure, and humidity in hospitals, ensuring optimal conditions for patient comfort and recovery in wards, as well as preserving the quality and efficacy of medicines and medical equipment in storage areas. This solution enhances patient care while safeguarding critical healthcare resources.


## What - The Problem 

What problem did you tackle and why does it matter? Write 1 to 2 paragraphs in response.

The problem I tackled was ensuring precise monitoring and control of environmental conditions—specifically temperature, pressure, and humidity—in hospital settings. Maintaining optimal conditions is crucial for two primary reasons: patient care and the preservation of medical resources. In patient wards, an unsuitable environment can lead to discomfort, delayed recovery, or even worsened health outcomes. Simultaneously, medical equipment and medicines often require stringent storage conditions to maintain their efficacy and prevent damage, which could compromise patient safety and lead to significant financial losses for healthcare facilities.

This issue matters because hospitals are environments where lives are at stake, and even minor deviations in environmental conditions can have significant negative effects. By addressing this challenge, we ensure a higher standard of patient care, protect valuable medical resources, and support healthcare providers in delivering consistent, reliable treatment. Solving this problem contributes to more efficient hospital operations and better health outcomes, making it a critical area for innovation and improvement.


## Why - Who Cares? 

Why do you care about this particular problem? Write 1 to 2 paragraphs in response.

- Monitoring the hospital environment is critical to ensuring patient comfort and maintaining the integrity of medical supplies. A well-regulated environment in patient wards promotes recovery and well-being, while temperature-controlled storage is essential to prevent damage to sensitive medical equipment and medicines. Proper environmental monitoring not only enhances patient care but also safeguards the efficacy of essential healthcare resources.

## How - Expected Technical Approach

Write 1 to 2 paragraphs describing the outcomes you achieved.

I developed a secure end-to-end IoT system for monitoring and controlling temperature, humidity, and pressure, with implementations for both the constrained device (using Python) and the gateway device (using Java). The system leverages the MQTT protocol to enable real-time communication between devices.

Local thresholds can be configured for each parameter, triggering automatic HVAC actuation when these thresholds are breached. Sensor data is visualized on a cloud platform, which also facilitates sending actuation commands remotely. The architecture is scalable, allowing deployment of multiple sensors while a centralized gateway efficiently manages communication with the cloud.

This robust system ensures seamless integration, real-time monitoring, and control, making it ideal for applications requiring automated environmental management.

### System Diagram

Embed a block diagram depicting your overall design, including the CDA, GDA, and Cloud Services interactions.
Be sure to include arrows depicting data flow from one application / service to the next.

Write 1 to 2 paragraphs describing your design.

![Block Diagram](/images/block-diagram.png)

Developed a secure end-to-end IoT system for monitoring and controlling temperature, humidity, and pressure, with implementations for both the constrained device (using Python) and the gateway device (using Java). The system leverages the MQTT protocol to enable real-time communication between devices.

Local thresholds can be configured for each parameter, triggering automatic HVAC actuation when these thresholds are breached. Sensor data is visualized on a cloud platform, which also facilitates sending actuation commands remotely. The architecture is scalable, allowing deployment of multiple sensors while a centralized gateway efficiently manages communication with the cloud.

This robust system ensures seamless integration, real-time monitoring, and control, making it ideal for applications requiring automated environmental management.

### What THREE (3) sensors and ONE (1) actuator did you use (add more if you wish)?

- CDA Sensor 1: Temperature

- CDA Sensor 2: Pressure

- CDA Sensor 3: Humidity

- CDA Actuator 1: HVAC



### What ONE (1) CDA protocol and TWO (2) GDA protocols did you implement (add more if you wish)?

- CDA to GDA Protocol: MQTT + TLS

- GDA to CDA Protocol: MQTT + TLS

- GDA to Cloud Protocol: MQTT + TLS

- Cloud to GDA Protocol: MQTT + TLS


 
### What TWO (2) cloud services / capabilities did you use (add more if you wish)?

- Cloud Service 1 (data ingress - all inputs): Temperature, Pressure, Humidity, System Performance data

- Cloud Service 2 (data egress - all actuation events): Trigger an LED for actuation



## Screen Shots Representing Cloud Services



### Screen Shots Representing Visualized Data

NOTE: Include (at least) TWO (2) screen shots - one showing at least 1 hour
of time-series data from the CDA, and one showing an event being triggered
that results in an actuation event sent to your GDA and then to your CDA.



EOF.
