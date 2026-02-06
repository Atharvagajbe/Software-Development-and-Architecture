# Student Management System

## Overview
The **Student Management System** is a robust, microservices-oriented application designed to streamline academic administrative tasks. It manages everything from student enrollments and course curricula to professor assignments and authentication.

## Architecture
The system is built using a microservices architecture, ensuring scalability and maintainability. Each service is responsible for a specific domain:

- **authService**: Manages user authentication, authorization, and security.
- **courseService**: Handles course creation, curriculum management, and scheduling.
- **enrollmentService**: Facilitates student registration and course enrollment processes.
- **professorsService**: Manages faculty profiles, expertise, and teaching assignments.
- **studentService**: Handles student personal records, academic history, and profiles.

### Shared Components
To ensure consistency across the microservices, the following shared components are utilized:
- `logging.js`: A centralized logging utility for structured logs.
- `correlationId.js`: Facilitates request tracking and observability across service boundaries.
- `consts.js`: Shared constants and configuration values.

## Key Features
- **Microservices-Based Design**: Modular and independently deployable services.
- **Rate Limiting**: Integrated rate limiting to ensure system stability and security.
- **Observability**: Request tracking using Correlation IDs and centralized logging.
- **Tech Stack**: Built entirely with **JavaScript** and **Node.js**.

## Getting Started
### Prerequisites
- [Node.js](https://nodejs.org/) (Recommended version: v14 or higher)
- [npm](https://www.npmjs.com/)

### Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/nandanmuruli/StudentManagementSystem.git
   ```
2. Navigate to the project root and install dependencies:
   ```bash
   npm install
   ```
   *(Note: Each service may require individual `npm install` depending on your deployment strategy.)*

## Contributors
- **Nandan Muruli** (10004359)
- **Dakshitha Ancha** (100004361)
- **Atharva Gajbe** (100004209)
- **Nitin Saini** (100004861)
- **Kiran Somineni Raghupathi** (100004324)

---
*Developed as part of the Student Management System project.*
