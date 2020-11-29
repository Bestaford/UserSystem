# UserSystem
A GenisysPro plugin that adds auth system to your server

## Features:
* Displaying the player's number in the chat, if he joined server for the first time
* No need to enter password until next restart
* Welcome message and title
* Password is not less than 5 characters, bad characters are prohibited (cyrillic, emoji, etc.)
* Fix player "shaking" at join (may not works)
* Blocking any actions of player and with player (chat, commands, inventory, etc.)
* A minute to enter / register, after which player will be kicked
* 3 attempts to enter the password at the entrance, after which player will be kicked
* Ability to log out from your account
* Ability to change password
* Hides the password if it was accidentally entered into the chat

## Commands:
* /lоgоut
* /change <old password> <new password>

## Permissions:
* users.logout
* users.change

## API:
* isLogined(Player $player) : bool
* isRegistered(Player $player) : bool
