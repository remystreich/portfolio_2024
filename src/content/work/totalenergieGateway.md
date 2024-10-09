---
title: Total Energie Matter Gateway
publishDate: 2024-09-01 00:00:00
img: /assets/240.svg
img_alt: Gateway Matter App Screenshot
description: |
 Developed at OMWave for Total Énergie as part of an R&D project, enabling control and monitoring of Matter devices for energy consumption tracking.
tags:
  - NodeJs
  - MongoDB
  - JavaScript
  - WebComponents
  - Microservices
  - CI/CD
  - Docker
  - Matter
  - CHIP Library
  - Kotlin
---

## Project Overview

**Gateway Matter** is a prototype application developed at **OMWave** for **Total Énergie** as part of a **research and development (R&D)** project. The goal was to design a gateway that allows users to control **Matter**-compliant devices and track energy consumption within a domestic network. The gateway utilized a proprietary **ERL**, a **tablet gateway**, and a **CRO** for energy management.

This solution provides a centralized platform for managing connected devices, allowing users to visualize and control energy usage in real time.

### Technologies Used

The **Gateway Matter** project leverages cutting-edge technologies to ensure performance, scalability, and effective device communication:

- **Node.js**: Built the backend infrastructure to handle device communication and energy data processing.
- **MongoDB**: Implemented as the database to store energy consumption data from connected devices.
- **Kotlin**: Developed an Android controller using **Kotlin** and the **CHIP Library** to interface with the Matter devices, ensuring smooth communication between the gateway and the network.
- **JavaScript & WebComponents**: Developed the frontend interface using WebComponents, providing an intuitive control dashboard for managing the devices.
- **CI/CD Pipelines & Docker**: Integrated continuous integration and deployment pipelines, using **Docker** for consistent and reliable application deployment across environments.

### Key Features

- **Device Control**: The gateway allows seamless control of multiple Matter devices, enabling users to interact with and manage their connected appliances via a central interface.
- **Energy Consumption Monitoring**: Real-time tracking of energy consumption using data from the **ERL** and visualized through a user-friendly interface.
- **Cross-Platform Support**: The application includes an Android controller developed with **Kotlin**, serving as the interface between the Matter devices and the gateway.
- **Cloud-Based Management**: The backend, built with **Node.js** and **MongoDB**, allows for efficient storage and retrieval of energy usage data, making it accessible in real time.
  
### Challenges Overcome

Several technical challenges were addressed during the development of the **Gateway Matter** project:

### Challenges Overcome

During the development of the **Gateway Matter** project, several technical and organizational challenges were addressed:

- **Learning Matter and Underlying Protocols**: I had to quickly familiarize myself with the **Matter** protocol and its underlying technologies, including **Thread**, **Wi-Fi**, and **IPv6**. This required understanding how these protocols work together to enable communication between smart home devices in a secure and scalable way.
  
- **Integrating the CHIP Project (Connected Home over IP)**: One of the biggest challenges was integrating the **CHIP** (Connected Home over IP) project from the **Connected Home over IP** initiative, with very limited documentation available. I had to experiment, reverse-engineer parts of the project, and adapt it to our specific use case within the gateway architecture.

- **Team Collaboration Across Disciplines**: Working within a multidisciplinary team at **OMWave**, where different teams were responsible for designing, creating, and assembling the gateway, the **ERL**, and the **CRO**, required strong communication and collaboration. The team at OMWave was also responsible for creating both the hardware and software, which meant coordinating across departments to ensure seamless integration.

- **Linky Meter Integration**: I had to learn how the **Linky** smart meter works, focusing specifically on the various indexes it reports. This involved understanding how to capture and process data from the meter, and ensuring that the system could interpret the indexes for accurate energy consumption monitoring and device control.

### Results and Impact

Although still in the **R&D phase**, the **Gateway Matter** project has demonstrated significant potential for improving energy management and device control within smart home networks. Key results include:

- **Efficient Energy Management**: Provided a platform that allows users to track and optimize their energy consumption, contributing to more sustainable energy use.
- **Improved Device Control**: Enabled seamless control and monitoring of multiple connected Matter devices in real time.
- **Prototype for Future Development**: This project has laid the foundation for future commercial applications, providing **Total Énergie** with insights into smart energy management solutions.

The **Gateway Matter** project showcases my ability to design full-stack solutions that integrate real-time data processing, device communication, and cloud-based management systems, with a focus on energy efficiency and smart home technology.

