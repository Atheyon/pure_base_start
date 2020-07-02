# pure_base_start
## A Satisfactory Save Game

This repo is used to address the lack of proper server functionality in Satisfactory. This repo can be pulled by any of the players and rehosted on any of their machines. If the host needs to leave, they can save the game and push the changes to this repo. The other players may continue playing simply by pulling the save down

### Usage
To use the save, simply clone this repo inside C:\Users\\\<user>\AppData\Local\FactoryGame\Saved\SaveGames\\\<steam_id?>\\
or wherever your Satisfactory saves are stored. Refer to https://satisfactory.gamepedia.com/Save_files for more info.

Then simply open up satisfactory, and session "HELLALLALOT" will be available containing this save file.

### Notes
Satisfactory does not use folders to organize the saves associated with differnt sessions. As a consequence, using a git repo to manage the saves only works with a .gitignore that ignores everything except for the save in question. To add another file to this repo, use "!/\<the file>" to add it after the "/*" line. 

Keep in mind that using multiple repos to keep track of different saves in this way becomes very cumbersome because of Satisfactory's save file organization. Scripts that move the saves around from a source location to the correct location will likely be needed.