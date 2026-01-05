# Online Tutor Matching System

TutorConnect is a comprehensive online education platform designed to connect students with qualified tutors while supporting an interactive and flexible learning environment. Instead of directly selecting a tutor, students submit a tutoring request form specifying detailed information such as grade level, subject, learning schedule, and expected payment.

Tutors can view available class requests, review the provided requirements, and accept suitable requests based on their expertise and availability. Once accepted, tutors can manage assigned classes and participate in the learning process through the platform.

The system integrates essential educational functionalities, including user management, course and class management, e-learning support, and secure payment processing. TutorConnect aims to streamline the tutoring workflow, improve transparency between students and tutors, and enhance the overall learning experience for both parties.

## Tech Stack
Backend
Language: Python
Framework: FastAPI
Architecture: Microservices
Database: Supabase
Components:
Gateway: localhost:8000 - The main entry point for the API, directing requests to the corresponding microservices.
Authentication Service: localhost:8001 - Handles authentication, login, and registration.
User Service: localhost:8002 - Manages user information.
Academic Service: localhost:8003 - Manages academic matters like courses and tutors.
Learning Service: localhost:8004 - Supports functions related to the learning process.
Payment Service: localhost:8005 - Processes payment transactions.
Frontend
Language: JavaScript
Framework: React (using Vite)
Libraries:
axios: For sending HTTP requests to the backend.
react-router-dom: For managing page navigation.
Interface: A modern user interface built with React components.
Containerization
Technology: Docker
Orchestration: Docker Compose

Quickstart
This project is configured to run seamlessly using Docker and Docker Compose. This is the recommended way to get all services up and running.
