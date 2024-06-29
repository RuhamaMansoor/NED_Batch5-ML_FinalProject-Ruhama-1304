Project Overview
Project 1: Simple Todo-App
Description:
This Todo-App is a straightforward and efficient task management application designed to help users organize their daily tasks. It leverages three core technologies to deliver a seamless user experience:

UI - Streamlit:

Chosen for: Ease of use and interactive capabilities.
Role: Provides an intuitive and interactive interface for users to manage their tasks. Users can add, edit, delete, and view their to-dos in a visually appealing and responsive manner.
Database - SQLite:

Chosen for: Simplicity and reliability.
Role: Acts as the storage backbone of the application, maintaining a persistent record of all user tasks. SQLite's lightweight nature makes it an ideal choice for this scale of application.
Backend - FastAPI:

Chosen for: Speed and efficiency.
Role: Handles the application's backend logic and API endpoints, facilitating communication between the UI and the database. FastAPI ensures rapid responses and smooth data handling.
Project 2: Comprehensive Todo-App
Description:
The final project expands on the basic Todo-App to incorporate a full suite of advanced features and technologies, making it a robust, scalable, and secure task management system:

UI - Streamlit:

Chosen for: Maintaining ease of use and adding interactive enhancements.
Role: Continues to serve as the user interface, now enhanced with features that accommodate the additional backend capabilities and user authentication.
Backend - FastAPI with PostgreSQL:

Chosen for: Robustness and scalability.
Role: Manages the application's business logic and data handling, using PostgreSQL for its robust and scalable database solution. This setup supports a higher volume of data and more complex queries efficiently.
Authentication and Authorization:

Role: Provides secure access to the application, ensuring that user data is protected and that only authorized users can access or modify their tasks. Implemented using secure protocols and best practices.
Kafka:

Chosen for: Enabling an event-driven architecture and real-time data processing.
Role: Facilitates real-time updates and data streaming within the application, allowing for asynchronous communication and improved performance in handling tasks and notifications.
Kong:

Chosen for: API gateway and management.
Role: Manages and secures API traffic, providing load balancing, rate limiting, and analytics. Ensures the APIs are reliable, secure, and scalable.
Containerization - Dockerfile and Docker Compose:

Chosen for: Ensuring easy deployment and management.
Role: Containerizes the application components, making it easier to deploy, scale, and manage across different environments. Docker Compose facilitates the orchestration of multi-container applications.
