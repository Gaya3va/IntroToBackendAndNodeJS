# IntroToBackendAndNodeJS

Web Application Fundamentals – Answers


Q1. Role of Frontend (FE)
The Frontend (FE) is the part of a web application that users directly see and interact with in their browser. It focuses on presentation, interaction, and communication with the backend.

1. User Interface
Frontend is responsible for designing and displaying the user interface such as buttons, forms, images, navigation bars, and layouts. It ensures the website looks attractive, readable, and consistent across different devices and screen sizes.

2. User Interaction
Frontend handles all user actions like clicking buttons, filling forms, scrolling pages, and validating input before sending data. It provides instant feedback to users (error messages, loading indicators) to improve user experience.

3. Communication with Backend
Frontend sends requests to the backend using APIs (HTTP/HTTPS) and receives responses such as data or status messages. It processes this data and displays it meaningfully to the user.





Q2. Role of Backend (BE)
The Backend (BE) works behind the scenes of a web application. It manages data, processes requests, and ensures secure and correct functioning of the system.

1. Server-side Processing
Backend handles all application logic such as calculations, validations, and decision-making. When a request comes from the frontend, the backend processes it and prepares an appropriate response.

2. Database Handling
Backend communicates with databases to store, retrieve, update, and delete data. It ensures data consistency, integrity, and proper structure.

3. Security and Authentication
Backend is responsible for user authentication, authorization, and data security. It verifies user credentials, manages sessions or tokens, and protects the system from unauthorized access.





Q3. Business Logic
Business Logic refers to the core rules and decision-making processes of an application that define how data is processed according to business requirements. It lies between the user interface and the database.

Explanation
Business logic ensures that the application behaves correctly based on real-world rules. It decides what should happen when a user performs an action, not how it looks or where data is stored.

Real-World Examples
E-commerce Website
Applying discounts only if the cart value exceeds a certain amount
Preventing checkout if stock is unavailable
Banking Application
Allowing money transfer only if sufficient balance exists
Applying daily transaction limits
Online Exam System
Allowing exam submission only within the allotted time
Automatically calculating scores based on answers




Q4. Client–Server Model
The Client–Server Model is a network architecture where tasks are divided between service providers (servers) and service requesters (clients).

Client
The client is usually a web browser or mobile application. It sends requests to the server and displays the received response to the user.

Server
The server is a system that processes client requests, executes business logic, interacts with databases, and sends results back to the client.

Communication Process
Communication happens through HTTP/HTTPS protocols.
Client sends a request
Server processes it
Server sends a response back





Q5. Three-Tier Architecture
3-Tier Architecture divides a web application into three independent layers to improve scalability, maintainability, and security.

1. Presentation Layer
This is the frontend layer. It handles user interface and user interaction.

2. Application (Business) Layer
This layer contains business logic. It processes data, applies rules, and communicates between frontend and database.

3. Data Layer
This layer manages data storage using databases. It handles data retrieval, updates, and storage.
Why This Architecture Is Used
Easier maintenance
Better scalability
Improved security
Clear separation of responsibilities





Q6. JavaScript as a Backend Language
JavaScript is widely used as a backend language due to its speed, flexibility, and strong ecosystem.

1. Performance
JavaScript uses non-blocking, event-driven architecture, which allows handling multiple requests efficiently and improves performance for real-time applications.

2. Ecosystem
JavaScript has a huge ecosystem with thousands of libraries and tools available through package managers. This speeds up development and reduces effort.

3. Popular Backend Frameworks
Express.js
NestJS
Fastify
Using JavaScript on both frontend and backend allows code reusability and easier development.