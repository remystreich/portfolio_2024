---
title: PMScan
publishDate: 2024-05-01 00:00:00
img: /assets/pmscan.webp
img_alt: Pmscan App Screenshot
description: |
 Developed at OMWave for Tera Sensor to enable real-time air quality monitoring through fine particle sensors.
tags:
  - ElectronJs
  - IndexedDB
  - NodeJs
  - React
  - TailwindCSS
  - WebBluetooth API
---

## Project Overview

**PMScan** is a desktop application developed at **OMWave** for **Tera Sensor**, designed to interface with fine particle sensors via **Bluetooth Low Energy (BLE)**. The application was integrated into Tera Sensor's product offering, and is currently used by major clients such as **SNCF** and **Alstom** to monitor air quality in real time.

The app features real-time data collection, visualization of sensor data using **Apache ECharts**, and allows users to export the data in **CSV** format for further analysis. This solution was crucial in providing a reliable, user-friendly interface for monitoring environmental conditions.

### Technologies Used

The PMScan application leverages several modern technologies to ensure performance, scalability, and ease of use:

- **ElectronJS**: Built the desktop application to create a cross-platform solution.
- **WebBluetooth API**: Implemented to establish communication between the sensors and the application.
- **IndexedDB**: Used for local storage and efficient data retrieval.
- **Node.js**: Powered the backend services for real-time communication and data processing.
- **React**: Handled the frontend interface, ensuring an intuitive and responsive user experience.
- **TailwindCSS**: Employed for fast and consistent styling of the user interface.
- **Apache ECharts**: Visualized the particle measurement data in dynamic charts for real-time monitoring.

### Key Features

- **Real-time Data Collection**: The application continuously collects data from fine particle sensors via **Bluetooth Low Energy (BLE)**, ensuring up-to-date air quality information.
- **Dynamic Data Visualization**: Sensor measurements are visualized using **Apache ECharts**, providing dynamic, easy-to-understand graphical representations of air quality data.
- **Data Export**: Users can export collected data in **CSV format**, enabling detailed external analysis.
- **Cross-Platform Compatibility**: Built with **ElectronJS**, the app runs seamlessly on multiple operating systems, making it versatile for different environments.

### Challenges Overcome

During the development of **PMScan**, several technical challenges were addressed:

- **Bluetooth Communication**: Managing **BLE communication** with environmental sensors required in-depth knowledge of the **WebBluetooth API** and handling device-specific protocols for data transmission. I had to learn to interpret and manage **binary data streams** sent by the sensors, ensuring accurate real-time data processing.
- **Data Synchronization**: Ensuring smooth data collection and visualization without performance bottlenecks, especially when managing large datasets, required implementing efficient **data storage** solutions using **IndexedDB**.
- **Electron Architecture**: Working with ElectronJS involved mastering the interaction between the main process and the render process, as well as implementing efficient communication through **IPC (Inter-Process Communication)**. This architecture allowed the seamless transfer of data between the backend and the frontend of the application.
- **Real-time Data Visualization**: Utilizing **Apache ECharts** to create dynamic, interactive charts that update in real-time based on large sensor data, providing users with a clear and immediate understanding of air quality conditions.
### Results and Impact

The **PMScan** application has been successfully integrated into **Tera Sensor's** product suite and is now used by **SNCF**, **Alstom**, and other clients for monitoring air quality in various settings. This solution has:

- Enhanced the monitoring of fine particles in sensitive environments, providing real-time data to decision-makers.
- Simplified data analysis with easy CSV exports for further processing by technical teams.
- Improved the reliability of air quality measurements through a robust and user-friendly interface.

The application showcases my ability to design and implement full-stack solutions that integrate real-time data processing, sensor communication, and intuitive data visualization.

