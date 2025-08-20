# Airbnb Clone Project
A real-world application designed to simulate the development of a robust booking platform like Airbnb. It involves a deep dive into full-stack development, focusing on backend systems, database design, API development, and application security.

# Team Roles
## Backend Developer
- Engineers and stabilizes the product
- Solves techincal problems emmerging during the development lifecycle
Responsible for implementing API endpoints, database schemas, and business logic
## DevOps engineer
- Facilitates cooperation between development and operation teams
- Builds CI/CD pipelines
Handles deployment, monitoring, and scaling of the backend services
## Database Administrator
Manages database design, indexing, and optimizations.
## QA Engineer
Ensures the backend functionalities are thoroughly tested and meet quality standards.

# Technology Stack
 - Django : a web framework for building RESTful APIs
 - GraphQL : efficient query mechanism for interacting with the backend
 - PostgreSQl : a relational DB for data storage
 - Redis : Used for caching and session management
 - Celery : For handling async tasks such as sending notifications
 - Docker : conteinerization tool for consistent development and deployment
  - CI/CD pipelines : automated pipelines for testing and deploying code changes

# Database Design
## User
 - Can have multiple properties
 - Can have multiple bookings
 ## Property
 - Can have multiple reviews from many users
 - Bookings belong to a property
 ## Bookings
 - Belong to a property and a user
 ## Reviews
 - Belong to a user and a property

 # Feature Breakdown
 ## User Authentication
 - Register new users
 - Authenticate and manage user profiles
## Property Management
- Create, update, retrieve and delete property listings
## Booking System
- Make, update and manage bookings
- Manage check-in and check-out details
## Payment processing
- Hanlde payment transactions related to bookings
## Review System
- Post and manage reviews for properties
## Database Optimizations
- Implementing indexes for fast retrieval of frequently accessed data
- Caching

# API Security
- Authentication : protecting user data
- Role based access : ensures the right users have the correct permissions
- Rate limiting : to prevent abuse, protect resources, and ensure fair usage among multiple users

# CI/CD Pipeline
CI/CD are practices in software development that ensure the quality, stability, and speed of the software delivery process. They
- improve code quality
- increase development speed
- reduce errors that might happen
## Tools
- Github Actions
- Docker
- Jenkins


