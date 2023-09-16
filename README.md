# Innovators by Panini

## Description
Innovators is a web application which help to collaborate with other people and share ideas. It is a platform where you can share your ideas and get feedback from other people. 
You can also join other people's projects and help them to make it better.

For the junior developers is great opportunity to join the open-source or commercial projects to get more experience and improve their skills for the feature work.

For the senior developers is great opportunity to find new people and create a team for the new project.

## Architecture
Architecture of the project is based on the microservices.
1. Frontend Microservice (Web UI):

This microservice handles the user interface of the application.
It serves web pages to users and interacts with other microservices via RESTful APIs and Kafka.
It communicates with the backend services to fetch and display data.
2. Authentication and Authorization Microservice:

Responsible for user authentication and authorization.
Provides APIs for user registration, login, and manages user roles and permissions.
Uses a database to store user data and JWT tokens for authentication.
3. Idea Management Microservice:

Handles the core functionality of the application, such as idea creation, editing, and sharing.
Manages user-generated content and interactions.
Stores ideas and their metadata in a database.
4. Feedback Microservice:

Allows users to provide feedback on ideas.
Manages feedback ratings and comments.
Sends notifications to users when their ideas receive feedback.
5. User Profile Microservice:

Manages user profiles, including personal information, skills, and project history.
Allows users to search for other users based on skills and interests.
Provides APIs for users to connect with each other.
6. Project Collaboration Microservice:

Handles the collaboration aspect of the platform.
Allows users to create projects and invite collaborators.
Manages project-specific discussions, tasks, and file uploads.
7. Messaging Microservice (Kafka):

Acts as a message broker using Kafka for communication between microservices.
Different microservices can publish and subscribe to specific Kafka topics to exchange information.
Facilitates real-time updates and event-driven communication.


### Frontend
Tech stack: Vue.js, Quasar, TypeScript
### Backend
Tech stack: Java, Spring Boot, Spring Cloud, PostgreSQL, Redis, Docker, Kubernetes, Kafka,  Jenkins, SonarQube, Selenium, JUnit, Mockito, WireMock, Pact, Swagger, OpenAPI, Maven, Git, GitHub, GitLab, 