# Online Tutor Matching System

## TutorConnect

TutorConnect is a comprehensive online education platform designed to connect students with qualified tutors while supporting an interactive and flexible learning environment.

Instead of directly selecting a tutor, students submit a tutoring request form specifying detailed information such as:

- Grade level  
- Subject  
- Learning schedule  
- Expected payment  

Tutors can view available class requests, review the provided requirements, and accept suitable requests based on their expertise and availability.

Once accepted, tutors can manage assigned classes and participate in the learning process through the platform.

The system integrates essential educational functionalities, including:

- User management  
- Course and class management  
- E-learning support  
- Secure payment processing  

TutorConnect aims to streamline the tutoring workflow, improve transparency between students and tutors, and enhance the overall learning experience for both parties.

---

## Tech Stack

### Backend
- **Language:** Python  
- **Framework:** FastAPI  
- **Architecture:** Microservices  
- **Database:** Supabase  

#### Backend Services
- **Gateway:** `localhost:8000`  
  - Main entry point for the API  
  - Routes requests to corresponding microservices  

- **Authentication Service:** `localhost:8001`  
  - Handles authentication, login, and registration  

- **User Service:** `localhost:8002`  
  - Manages user information  

- **Academic Service:** `localhost:8003`  
  - Manages academic data such as courses and tutors  

- **Learning Service:** `localhost:8004`  
  - Supports learning and class-related functionalities  

- **Payment Service:** `localhost:8005`  
  - Processes payment transactions  

---

### Frontend
- **Language:** JavaScript  
- **Framework:** React (Vite)  

#### Libraries
- **axios:** HTTP requests to backend services  
- **react-router-dom:** Client-side routing  

#### Interface
- Modern user interface built with reusable React components  

---

## Containerization
- **Technology:** Docker  
- **Orchestration:** Docker Compose  

---

## Quickstart
This project is configured to run seamlessly using **Docker** and **Docker Compose**.  
This is the recommended way to get all services up and running.
