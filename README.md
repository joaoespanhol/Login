Guardapanda Login
Guardapanda Login is a Minecraft Forge mod designed to protect offline-mode servers. It functions as an authentication system, requiring players to enter a password upon joining the server, similar to plugins like AuthMe on Bukkit.

Introduction
Guardapanda Login was created to add a layer of security to Minecraft servers operating in offline mode. It ensures that only registered and authenticated players can access the server, protecting against unauthorized users in environments without Mojang account verification.

Features
Registration and Login System: Players must register with a password and log in every time they join the server.

Admin Commands: Commands to manage player accounts, such as changing passwords, forcing login, or removing registrations.

Customizable Configuration: Messages and settings can be adjusted to suit the server's needs.

Configuration
The configuration files for Guardapanda Login are located in the config/guardapanda folder. Below are the main files:

systemLogin.json: File to customize system messages.

registered-players.json: Database that stores registered players and their passwords.

Commands
Player Commands
/register <password>: Registers a player in the system.

/login <password>: Authenticates a player on the server.

/changepassword <newPassword>: Changes the player's password.

Admin Commands (OP)
/changepasswordstaff <Nickname> <NewPassword>: Changes another player's password.

/forcelogin <Nickname>: Forces a player to log in.

/unregister <Nickname>: Removes a player's registration.

FAQ
1. How can I customize system messages?
Edit the systemLogin.json file in the config/guardapanda folder to adjust the messages displayed to players.

2. Where is player data stored?
Registered player data is stored in the registered-players.json file.

3. Can I use this mod on online servers?
Yes, but it is primarily designed for offline servers. On online servers, Mojang's authentication already provides a layer of security.

Contributing
Contributions are welcome! Feel free to open issues or pull requests on the GitHub repository.

License
This project is licensed under the MIT License. See the LICENSE file for more details.

GitHub Repository: https://github.com/joaoespanhol/Login
Version minecraft forge: 1.20.1
Author: guardapanda
