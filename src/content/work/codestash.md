---
title: CodeStash
publishDate: 2024-03-01 00:00:00
img: /assets/codestash.webp
img_alt: CodeStash App Screenshot
description: |
  CodeStash is a personal project that enables users to store, categorize, and manage code snippets with syntax highlighting, tagging, and language recognition.
tags:
  - TypeScript
  - NestJS
  - PostgreSQL
  - Redis
  - Docker
  - GitHub Actions
  - React
  - TailwindCSS
  - ShadcnUI
  - CodeMirror
  - highlight.js
---

## Project Overview

**CodeStash** is a personal project aimed at helping developers store, organize, and manage their code snippets efficiently. Users can categorize snippets by programming language, assign tags, and benefit from automatic syntax highlighting and language recognition. This project was built using **TypeScript**, **PostgreSQL**, **Redis**, **NestJS**, and **React**.

The application features an IDE-like interface, offering code syntax highlighting, auto-indentation, and language detection thanks to **highlight.js** and **CodeMirror**. Additionally, **Redis** is used to store **refresh tokens** and **password reset tokens** securely, ensuring robust user authentication and session management.

### Technologies Used

The **CodeStash** application leverages several modern technologies to create a robust, efficient, and user-friendly solution:

- **React & TypeScript**: Built the frontend using **React** for dynamic user interaction and **TypeScript** for type safety and better code management.
- **NestJS**: Used for the backend, providing a structured and scalable API for handling snippets, authentication, and user data.
- **PostgreSQL**: Acts as the main relational database to store code snippets and associated metadata (tags, language, etc.).
- **Redis**: Integrated for caching securely storing **refresh tokens** and **password reset tokens** to manage user sessions efficiently.
- **CodeMirror & highlight.js**: Implemented an IDE-like interface with **CodeMirror** for auto-indentation and **highlight.js** for automatic syntax highlighting and language recognition.
- **ShadcnUI**: Utilized for the UI components to ensure a clean and modern design, built on top of **TailwindCSS**.
- **Docker**: Containerized the application using **Docker**, enabling easy deployment and scalability.
- **GitHub Actions**: Automated the deployment process using **GitHub Actions**, ensuring continuous integration and deployment to a VPS.

### Key Features

- **Store & Categorize Snippets**: Users can store code snippets, categorize them by language, and assign multiple tags for better organization.
- **Syntax Highlighting & Language Recognition**: Using **highlight.js** and **CodeMirror**, the app automatically highlights syntax and recognizes the programming language, enhancing readability and usability.
- **Secure Token Management**: **Redis** is used to securely store **refresh tokens** and **password reset tokens**, improving security and session management.
- **IDE-Like Interface**: Provides an intuitive and responsive code editor with auto-indentation, language detection, and a clean UI, improving the developer experience.
- **Tagging & Search**: Snippets can be tagged and easily searched, allowing developers to quickly find the code they need.
- **Performance Optimization with Redis**: Frequently accessed snippets are cached in **Redis** to improve the application's responsiveness and reduce database load.

### Challenges Overcome

Several technical challenges were tackled during the development of **CodeStash**:

- **Integrating CodeMirror & highlight.js**: Ensuring that the code editor provides a seamless experience with features like **syntax highlighting**, **auto-indentation**, and **language detection** required an in-depth integration of **CodeMirror** and **highlight.js**.
- **Database Design & Optimization**: Designing the **PostgreSQL** schema to efficiently store and retrieve snippets along with their tags and language metadata, while ensuring scalability and performance.
- **Token Management with Redis**: Implementing a secure system for storing **refresh tokens** and **password reset tokens** in **Redis**, which required understanding and managing token lifecycles.
- **Deployment Automation**: Setting up **Docker** for containerization and using **GitHub Actions** for **CI/CD** allowed me to automate the deployment process on a VPS, ensuring smooth updates and scalability.

### Results and Impact

**CodeStash** is an ongoing personal project designed to enhance developer productivity by providing a central place to store and manage code snippets. It offers:

- A streamlined workflow for organizing code snippets by language and tags.
- An improved coding experience through an IDE-like interface with **syntax highlighting** and **auto-indentation**.
- Fast performance with **Redis** caching and secure token management for user sessions.
- Reliable and automated deployment using **Docker** and **GitHub Actions**.

The project showcases my ability to design and implement full-stack solutions, with a focus on frontend experience, backend efficiency, and DevOps practices for continuous integration and deployment.
