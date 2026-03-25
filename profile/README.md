# Group 5 – Recipe Tracker & Meal Planner System

## Project Mockup
https://www.figma.com/make/HdItIJHavBLz9ZtOwReDFr/Food-Tracking-and-Recommendation-Site?t=qHGGrrXMfMJUUZby-1

## Repositories
- Frontend: https://github.com/Group5-Project2-RecipeTracker/FrontEndSection  
- Backend: https://github.com/Group5-Project2-RecipeTracker/BackEndSection  

---

## Overview

The Recipe Tracker & Meal Planner System is a full-stack web application designed to help users:

- Track daily meals and nutrition  
- Create and manage recipes  
- Organize meal plans  
- Receive food recommendations  

This project demonstrates modern full-stack development using a React frontend and a Spring Boot backend, with secure authentication via Firebase OAuth2.

---

## System Architecture

```
Frontend (React)
        ↓
REST API (Spring Boot)
        ↓
Database
```

Authentication is handled using Firebase Authentication integrated with Spring Security (OAuth2).

---

## Backend Overview

### Technology Stack
- Spring Boot  
- Spring Security (OAuth2)  
- Firebase Authentication  
- Docker  
- Swagger (OpenAPI)  
- Planned Deployment: Heroku  

### Core Features
- User authentication and authorization  
- Role-based access control (User and Admin)  
- RESTful API design  
- Full CRUD operations for:
  - Users  
  - Foods / Recipes  
  - Meal Plans  
- API documentation via Swagger  

### Main Resources

#### User
- userID  
- email  
- password  
- admin (boolean)  

#### Food
- foodID  
- name  
- picture  
- nutrition (planned)  

#### Meal Plan
- id  
- userID (foreign key)  
- foodID (foreign key)  

### REST API Methods
- GET – Retrieve resources  
- POST – Create resources  
- PUT – Replace full resources  
- PATCH – Update partial resources  
- DELETE – Remove resources  

---

## Frontend Overview

### Technology Stack
- React  
- JavaScript (ES6+)  
- Firebase Authentication  
- Fetch API or Axios  

### Core Features
- User registration and login  
- Secure logout  
- Protected routes  
- Dashboard with nutrition tracking  
- Food logging system  
- Recipe browsing  
- Search and filtering  
- Meal planning tools  
- Admin management interface  

### Deployment Options
- Vercel  
- Netlify  

---

## Authentication and Authorization

- Firebase OAuth2 integration  
- Token-based authentication  
- Role-based access control  
- Admin-only endpoints and views  

---

## Development Workflow

- GitHub Issues for task tracking  
- Milestones for major features  
- Feature-branch workflow  
- Pull requests require two approvals before merging  
- REST best practices enforced  

---

## Project Goals

- Build a fully functional REST API using Spring Boot  
- Implement secure authentication and authorization  
- Maintain proper resource relationships  
- Follow RESTful design standards  
- Develop a responsive React frontend  
- Provide clear API documentation using Swagger  

---

## Future Improvements

- Expand nutrition tracking  
- Improve UI/UX design  
- Add advanced filtering and analytics  
- Enhance performance optimization  
- Deploy a full production-ready system  

---

## Organization Structure

This project is maintained within the Group 5 organization:

- Backend: Spring Boot REST API  
- Frontend: React Web Application  

---

## Summary

This project demonstrates full-stack development, secure authentication, REST API design, and effective frontend-backend integration.
