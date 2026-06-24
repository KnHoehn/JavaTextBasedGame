**Java Text-Based Game**

This project is a Java-based text adventure game developed as a capstone project, enhanced from my [original Python version](https://github.com/KnHoehn/Python-Text-Based-Game), with database integration, user authentication, and a dynamic scoring system. The application allows users to create accounts, play through different themed environments, and track their performance through a leaderboard.

**Overview**

The goal of the game is to navigate through a map, collect all required items, and reach the boss location. If the player reaches the boss without collecting all items, the game is lost. The application supports multiple themes and tracks player performance based on time and moves.

This project demonstrates object-oriented programming, database integration, and full application development from initial design through implementation.

**Technologies Used**
- Java
- MySQL
- JDBC
- Apache Maven
 
**Key Features**

- User account creation and login system
- Secure password storage using hashing and salting
- Multiple game themes (e.g., medieval, cyberpunk, space)
- Player inventory and item collection system
- Scoring system based on time and number of moves
- Leaderboard displaying top player scores
- Game stats tracking including score, moves, and completion time
 
**My Contributions**

- Designed and implemented the full game logic using object-oriented programming principles, including encapsulation and polymorphism
- Built and structured the application from scratch as a single-developer project
- Created and connected a MySQL database to store user accounts, scores, and gameplay data
- Implemented user authentication with secure password handling using hashing and salting
- Developed a scoring algorithm that evaluates player performance based on time taken and number of moves
- Designed and implemented database tables to support user data and leaderboard functionality
- Integrated Java application with the database using JDBC to perform CRUD operations
- Built a player inventory system and game progression logic
- Implemented multiple game themes to enhance user experience
- Debugged and refined application behavior to ensure consistent functionality across game scenarios
 
**Database Design**

The application uses a relational database to store user and gameplay data.
Tables include:
- Users (stores usernames and secure password credentials)
- Scoreboard (stores player performance metrics such as score, moves, time, and selected theme)
 
**How to Run the Project**

1. Install Java JDK 11 or higher
2. Install and configure MySQL
3. Create the required database and tables (see schema below)
4. Update database connection credentials in the .properties file
5. Compile and run the application
6. 
Example database setup:

- Create a database named game_db
- Create required tables for users and scores based on the schema provided in this repository
- Ensure your local MySQL instance is running before launching the application

**Database Schema:**

<img width="240" height="76" alt="image" src="https://github.com/user-attachments/assets/6d897ca5-8346-4eb3-8ee5-ef56e62e9cc1" />

**Challenges and Learning Outcomes**
One of the most significant challenges in this project was integrating the Java application with a MySQL database and managing data persistence. This required learning how to establish database connections, design schemas, and perform CRUD operations within the application.
Additional challenges included:
- Structuring the application using object-oriented principles
- Designing a scoring system that accurately reflects player performance
- Managing game state across different scenarios
- Implementing secure user authentication
Through this project, I strengthened my skills in backend development, database design, and application architecture.

If you get stuck during your playthrough, here are the maps for the different themes:

**Map of the Space theme:**

<img width="377" height="382" alt="SpaceTextBasedGameMap" src="https://github.com/user-attachments/assets/af45f60c-48b9-49d5-bc8f-6f6b28d052bd" />

**Map of the Medieval theme:**

<img width="334" height="312" alt="MedievalTextBasedGameMap" src="https://github.com/user-attachments/assets/b0ac8d95-bc0e-40ff-80ee-726ed4d3cf4b" />

**Map of the Cyberpunk theme:**

<img width="317" height="317" alt="CyberpunkGameMap" src="https://github.com/user-attachments/assets/f49af801-42ce-49cf-bd61-c326c452f55a" />
