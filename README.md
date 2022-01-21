# ue4-online-lobby
Open source Unreal Engine 4 files and documentation about an online menu and lobby system.
Developed by me and Miray Morova.
You can use this system for your multiplayer game. 

Main Menu: has 4 buttons. 

![Main Menu](https://user-images.githubusercontent.com/45761081/150539250-06d003ec-7bfa-43aa-bfe4-fb985b9e1d8b.png)

Host Game button creates a LAN or online lobby where other players can join. You need to set up a dedicated server for it to work online. You can also set server name and player limit (2-8).

![TopDown2 - Unreal Editor 21-Jan-22 4_51_56 PM (2)](https://user-images.githubusercontent.com/45761081/150539416-a7949808-1538-4985-adba-53495edf7f1c.png)

Find match simply searches for servers. If a server is found, you can click "join" and enter the same lobby as the host.

![FindMatch](https://user-images.githubusercontent.com/45761081/150539597-11c7354d-020d-45e3-af0b-675adfdcba05.png)

Options menu (WIP) lets the player choose their name and avatar. 

![PlayerOptions](https://user-images.githubusercontent.com/45761081/150539701-2b21d961-3e7d-49cb-b595-f70b2bee1a6b.png)

Quit game simply closes the game for the specific player.


Lobby has many functions. 

![Lobby](https://user-images.githubusercontent.com/45761081/150540046-972fe57f-72a9-4b54-a02a-23f05454ea4f.png)

If there are over 2 players in the lobby and all chose their character, the "Start Session" button becomes clickable and the host can click it to start a new game and move all players to that level. 
Game settings has a few functions.

![GameSettings](https://user-images.githubusercontent.com/45761081/150540236-5b42a11c-71e3-40e1-97a1-058818330457.png)

Select map simply chooses the level to start. Select time (5-10-15-20) sets the game time. You can implement it in your project. Kick player opens a player list in which clicking on a list member kicks the chosen player back to main menu, removing them from the lobby. 

Select Character button opens the character selection menu (WIP) where you can choose inbetween your characters in your game. 

Leave lobby removes the player from the lobby and sends them back to main menu. If the host leaves lobby, server is closed and all players return to the main menu.

Chat in lobby works just fine. When a message is sent, it appears in the chatbox and all players can see it.

Currently, some functions or events in this project might not work or create errors. If you detect any, please don't hesitate to contact me.
