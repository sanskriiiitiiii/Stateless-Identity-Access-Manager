# Identity & Access Manager: Java Spring Boot and Angular Implementation

## Table of Contents
- [Introduction](#introduction)
- [Features](#features)
- [Requirements](#requirements)
- [Setup Instructions](#setup-instructions)
- [Usage](#usage)

## Introduction
This repository features a full-stack application developed with Java Spring Boot and Angular, focusing on secure user authentication. It provides a practical implementation of registration and login workflows using Spring Security and JSON Web Tokens (JWT).

The system architecture utilizes Spring Boot to provide a high-security backend API, while the Angular frontend offers a streamlined interface for user interaction with the authentication services.



## Features
- **User Registration:** Provisioning of new accounts utilizing email and password credentials.
- **Secure Authentication:** Robust login services powered by Spring Security.
- **JWT Authorization:** Stateless access control for protected API endpoints.
- **Session Management:** Token-driven lifecycle management for secure client-server communication.

## Requirements
To deploy and run this project, ensure your environment meets the following criteria:
- **Java Development Kit (JDK):** Version 8 or more recent.
- **Node.js & npm:** Required for managing frontend dependencies.
- **Angular CLI:** For building and serving the client-side application.

## Setup Instructions

1. **Clone the Repository:**
   Download the source code to your local workstation:
   ```bash
   git clone [https://github.com/sanskriiiitiiii/Stateless-Identity-Access-Manager.git](https://github.com/sanskriiiitiiii/Stateless-Identity-Access-Manager.git)
   cd Stateless-Identity-Access-Manager
Backend Configuration:

Import the backend project into your preferred Java IDE (IntelliJ IDEA, Eclipse, or STS).

Navigate to src/main/resources/application.properties and update the database connection strings to match your local MySQL setup.

Boot the Spring Boot application to initialize the REST API server.

Frontend Configuration:

Open a terminal in the frontend project directory.

Install the necessary node modules:

Bash
npm install
If necessary, modify the API base path in src/environments/environment.ts to point to your backend's local port.

Launching the Platform:

Start the Angular development server:

Bash
ng serve
Navigate to http://localhost:4200 in your web browser.

Usage
Account Creation:

Access the "Sign Up" portal within the application.

Input your registration details and submit. Upon successful persistence, you will be directed to the login page.

User Authentication:

Enter your registered credentials on the login screen.

On successful validation, the server issues a JWT which is stored by the client to maintain the session.

Secure Dashboard:

Once authenticated, you will be granted access to the protected dashboard.

The dashboard retrieves user-specific data via authorized REST calls using the Bearer token.

Contributing
Contributions are encouraged. If you identify bugs or wish to propose feature enhancements, please open an issue or submit a detailed pull request. We ask that all contributors adhere to the existing architectural patterns and document any significant logic changes.
