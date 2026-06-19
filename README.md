This is a text-based adventure game written in Java. The goal of the game is to navigate the map and pick up all items before reaching the room where the boss resides. This is an enhanced version of the Python text-based game that is also featured on my Github. This enhanced version was created as my capstone project for Southern New Hampshire University. 

Structural enhancements include:

1. Porting the game from Python to Java.
2. Implementing Object Oriented Programming.
3. Unit testing.
4. Connecting to a database.
5. Modularizing.
6. Fixing bugs.

New features include:

1. The ability to pick the theme of your game which alters the game's story, map, items, and boss.
2. A scoring system based on the time it takes to reach the boss and total moves taken.
3. A secure account creation and login system.
4. The ability to view your top ten personal best scores and a leaderboard of the top ten scores of all time.

To run the game you will need to download and install Java JDK version 11 or higher and install Apache Maven. 

At this time, there is not a hosted database so a database needs to be created locally on your machine. You will need to download and install MySql and create a database with the following schema:

<img width="638" height="759" alt="image" src="https://github.com/user-attachments/assets/1c943f51-e6e4-45c1-afa8-473511d2f7e1" />

The application connects to the database by reading the credentials from a db.properites file. To get yours to connect you will need to create a "db.properties" file and place it in the src/main/resources folder. The db.properties file should look like the following but with the values replaced with your own:

<img width="240" height="76" alt="image" src="https://github.com/user-attachments/assets/6d897ca5-8346-4eb3-8ee5-ef56e62e9cc1" />

If you get stuck during your playthrough, here are the maps for the different themes:

Map of the Space theme: 

<img width="377" height="382" alt="SpaceTextBasedGameMap" src="https://github.com/user-attachments/assets/af45f60c-48b9-49d5-bc8f-6f6b28d052bd" />

Map of the Medieval theme: 

<img width="334" height="312" alt="MedievalTextBasedGameMap" src="https://github.com/user-attachments/assets/b0ac8d95-bc0e-40ff-80ee-726ed4d3cf4b" />

Map of the Cyberpunk theme:

<img width="317" height="317" alt="CyberpunkGameMap" src="https://github.com/user-attachments/assets/f49af801-42ce-49cf-bd61-c326c452f55a" />
