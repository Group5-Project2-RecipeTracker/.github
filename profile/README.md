# Group 5 – Recipe Tracker & Meal Planner System
## Project mock Up 
https://www.figma.com/make/HdItIJHavBLz9ZtOwReDFr/Food-Tracking-and-Recommendation-Site?t=qHGGrrXMfMJUUZby-1
## Overview

The Recipe Tracker & Meal Planner System is a full-stack web application designed to help users create recipes, manage ingredients, and organize weekly meal plans.

This project consists of:

- A Spring Boot REST API (Backend)
- A React Web Application (Frontend)
- OAuth2 Authentication with Firebase
- Dockerized backend deployment
- Swagger API documentation

The frontend communicates with the live backend API and handles all user interactions.

---

# System Architecture

Frontend (React)  
⬇  
REST API (Spring Boot)  
⬇  
Database  

Authentication is handled using Spring Security with OAuth2 and Firebase integration.

---

# Backend Overview

## Technology Stack

- Spring Boot
- Spring Security with OAuth2
- Docker
- Swagger (OpenAPI)
- Firebase Authentication
- Planned deployment on Heroku

## Core Features

- User authentication and authorization
- Role-based access control (User and Admin)
- CRUD operations for:
  - Users
  - Foods/Recipes
  - Meal Plans
- RESTful API design
- Swagger documentation for all endpoints

## Main Resources

### User
- userID
- email
- password
- admin (boolean)

### Food
- foodID
- name
- picture
- nutrition (planned)

### Meal Plan
- id
- userID (foreign key)
- foodID (foreign key)

## REST API Methods

GET    - Retrieve resources  
POST   - Create resources  
PUT    - Replace full resources  
PATCH  - Update partial resources  
DELETE - Remove resources  

---

# Frontend Overview

## Technology Stack

- React
- JavaScript (ES6+)
- Firebase Authentication
- Fetch API or Axios

## Core Features

- User registration and login
- Secure logout
- Protected routes
- Dashboard with user statistics
- Weekly meal plan management
- Add/remove foods
- Favorites functionality
- Recipe filtering
- Admin management interface

The frontend runs locally and connects to the deployed backend API.

Optional deployment platforms:
- Vercel
- Netlify

---

# Authentication & Authorization

- OAuth2 integration
- Token-based authentication
- Role-based access control
- Admin-only endpoints and views

---

# Development Workflow

- GitHub Issues used for task tracking
- Milestones for major features
- Pull requests require two approvals before merging
- Feature-branch workflow
- REST best practices enforced

---

# Project Goals

- Build a fully functional REST API using Spring Boot
- Implement secure authentication and authorization
- Demonstrate proper resource relationships
- Follow RESTful design standards
- Develop a responsive React frontend
- Properly document the API using Swagger

---

# Future Improvements

- Expand nutrition tracking
- Improve UI/UX design
- Add advanced filtering and analytics
- Enhance performance optimization
- Deploy full production-ready system

---

# Repositories

Backend and frontend components are maintained within the Group 5 organization.

Backend: Spring Boot REST API  
Frontend: React Web Application  

---

This project demonstrates full-stack development, secure authentication, REST API design, and proper frontend-backend integration.
