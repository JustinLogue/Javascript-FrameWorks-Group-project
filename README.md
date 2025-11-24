COMP2068 – Group Assignment  
Discord App Project

Group Members:
- Justin Logue
- Mathew Saji Varkey
- Nijin Sino
- Abin Biju

Project Description:
This project is a Discord app built using Node.js and the Discord.js library.
The app connects to a Discord server and responds to user commands. It was
developed to demonstrate the fundamentals of creating interactive Discord apps.

How to Run the App (Step-by-Step):
1. Clone the GitHub repository to your computer.
2. Open the project folder and go into the folder named “groupAssignment”.
3. Open a terminal inside this folder.
4. Install all required dependencies by running:
   npm install
5. Create a file called config.json in the same folder and add the Discord token in this format:
   {
     "token": "YOUR_DISCORD_APP_TOKEN"
   }
6. Save the file.
7. Start the app by running:
   node index.js
8. Make sure the app has already been added to a Discord server before testing.

Commands Available for Testing:
!hello — Responds with a greeting  
!help  — Displays available commands  
!ping  — Responds with latency information

Files in the Project:
index.js — Main app logic  
package.json — Dependencies and metadata  
config.json — Stores Discord token locally (not uploaded for security)

Contributions / Roles:
Justin Logue — Core Discord app development and command features  
Mathew Saji Varkey — GitHub setup, README documentation, and deployment support  
Nijin Sino — Testing and feedback during development  
Abin Biju — Testing and group coordination

Notes:
The config.json file is intentionally excluded from the repository to protect
the Discord token. If a token is exposed publicly, it must be reset in the
Discord Developer Portal.

Course Information:
This project is submitted for the COMP2068 JavaScript Frameworks course at Georgian College.
