COMP2068 – Group Assignment  
Discord App Project

Group Members:
- Justin Logue
- Mathew Saji Varkey
- Nijin Sino
- Abin Biju
- Burak Alay

Project Description:
This project is a Discord application built using Node.js and the Discord.js library.  
The goal of the assignment was to design a functional Discord bot that responds to user messages in a server.  
The bot recognizes specific commands and provides helpful responses.  
This project demonstrates the fundamentals of building event-driven applications, working with APIs, and using JavaScript packages.

Key Features of the Discord App:
- Responds to user commands in a Discord server
- Includes multiple commands located inside a "commands" folder
- Uses modular command files for scalability
- Uses Node.js and Discord.js to connect the bot to the Discord API
- Includes a secure configuration file (example provided) to keep the bot token private

How to Run the App (Step-by-Step):
1. Clone this GitHub repository to your computer.
2. Open the project folder in Visual Studio Code or any IDE.
3. Open a terminal inside the project folder.
4. Install all dependencies by running:
   npm install
5. Create a new file called `config.json` in the project folder and add the bot token in this format:
   {
     "token": "YOUR_DISCORD_BOT_TOKEN"
   }
6. Save the file.
7. Start the bot by running:
   node index.js
8. Make sure the bot has already been added to a Discord server that you can test in.

Commands Available for Testing:
!hello   → Bot replies with a greeting  
!help    → Lists the available commands  
!ping    → Shows response speed / latency  

Project Files:
index.js       – Main application logic and bot login  
package.json   – Dependencies and metadata  
package-lock.json – Required only for dependency tracking  
commands/      – Folder containing separate command files  
config.json    – Stores the bot token locally (not uploaded for security)  
config.json.example – Template file showing where the token must be inserted  

Security Notes:
The bot token is **not** included in the GitHub repository.  
A sample file (`config.json.example`) is included so anyone running the bot can supply their own token.  
Uploading the real token would make the bot public and unsafe.

Contributions of Each Group Member:
- Justin Logue — Set up the base project, organized repository, and managed deployment.
- Mathew Saji Varkey — Wrote README documentation and assisted with structure and commands.
- Nijin Sino — Contributed to command functionality and testing.
- Abin Biju — Helped with debugging and running the app in the server.
- Burak Alay — Assisted in development and command interaction testing.

Future Improvements (Optional ideas):
- Add more interactive commands
- Add slash commands application-wide
- Host the bot permanently using Render or another cloud service
- Create a web dashboard to control bot settings

End of README
