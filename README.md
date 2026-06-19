This is a text-based adventure game written in Java. The goal of the game is to navigate the map and pick up all items before reaching the room where the boss resides. At the start of the game you can pick your game theme which alters the game's story, map items, and boss. This application features a scoring system based on the time it takes to reach the boss and total moves taken. This application also features a secure account creation and login system where you can save your end-game score, view your top ten playthroughs, and view the leaderboard.

To run the game you will need to download and install Java JDK version 11 or higher and install Apache Maven. At this time, the game does not connect to the internet so a database needs to be created locally on your machine.

This application connects to a local database made with MySql so you will also need to download and install MySql and create a database with the following schema:

<img width="638" height="759" alt="image" src="https://github.com/user-attachments/assets/1c943f51-e6e4-45c1-afa8-473511d2f7e1" />

The application connects to the database by reading the credentials from a db.properites file. To get yours to connect you will need to create a "db.properties" file and place it in the src/main/resources folder. The db.properties file should look like the following but with the values replaced with your own:

<img width="240" height="76" alt="image" src="https://github.com/user-attachments/assets/6d897ca5-8346-4eb3-8ee5-ef56e62e9cc1" />

If you get stuck i your playthrough, here are the maps for the different themes:

Map of the Space theme: 

<img width="377" height="382" alt="SpaceTextBasedGameMap" src="https://github.com/user-attachments/assets/af45f60c-48b9-49d5-bc8f-6f6b28d052bd" />

Map of the Medieval theme: 

<img width="334" height="312" alt="MedievalTextBasedGameMap" src="https://github.com/user-attachments/assets/b0ac8d95-bc0e-40ff-80ee-726ed4d3cf4b" />

Map of the Cyberpunk theme:

<img width="317" height="317" alt="CyberpunkGameMap" src="https://github.com/user-attachments/assets/f49af801-42ce-49cf-bd61-c326c452f55a" />
