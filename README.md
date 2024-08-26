Quiz Application
A full-stack quiz application built with Spring Boot (Java) for the backend, React.js for the frontend, and PostgreSQL as the database. The application features user authentication (including Google login), dynamic quiz generation using ChatGPT AI, and a leaderboard system to track user performance.

Features
User Authentication:

Login with username/password and Google OAuth 2.0.
Secure JWT-based session management.
Quiz Section:

Select from 3 time intervals: 15 min (10 questions), 30 min (20 questions), 45 min (26 questions).
Choose topics such as Java, C++, DBMS, CN, OS, Spring Boot, and Aptitude. Includes an advanced option for mixed topics.
Set quiz difficulty: Easy, Medium, Hard. Advanced mode offers a mix of difficulties.
Questions fetched dynamically using ChatGPT AI API, allowing for an unlimited set of questions.
Timed quizzes with real-time progress tracking.
Leaderboard Section:

Track user performance across multiple quiz attempts.
Visualize progress and accuracy with interactive graphs.
Global leaderboard displaying rankings of all users with real-time updates.
Technologies Used
Backend:
Java 17
Spring Boot
Spring Security (JWT, OAuth 2.0)
Spring Data JPA (Hibernate)
PostgreSQL
ChatGPT AI API Integration
Frontend:
React.js
React Router
Axios for API Calls
Material-UI (MUI) for UI Components
Chart.js for Data Visualization
Tools & Libraries:
Maven/Gradle for Dependency Management
Docker for Containerization
Postman for API Testing
Git/GitHub for Version Control
Getting Started
Prerequisites
Java 17+
Node.js (v16+)
PostgreSQL
Docker (optional for deployment)

Usage
Register/Login: Users can sign up with a username/password or log in using Google.
Select Quiz Options: Choose time, topic, and difficulty, then start the quiz.
Complete the Quiz: Answer questions within the time limit and submit.
View Leaderboard: Track your progress and compare with other users on the leaderboard.
Screenshots
(Add relevant screenshots here)

Future Enhancements
Adaptive quizzes based on previous performance.
Badges and achievements for milestones.
Support for additional languages and topics.
