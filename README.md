# Playnite-DLsite-Metadata-Rename-to-DL-ID

### This script is designed to use with [erri120's Playnite DLsite metadata Extensions](https://github.com/erri120/Playnite.Extensions). All it does is to help you translate your DLsite games name into DLsite game ID for erri120's DLsite metadata to work properly. The script should detect 90% of your dlsite games and turn it into ID.

### This script is design to support all DLsite games with RJ000000 and VJ000000 code.

#### Thank you erri120 for making the DLsite metadata Extensions.



## installation:
Download the RenameTODLID folder and put into your playnite extensions folder. Normally it is the path below if you haven't changed it.

***(I strongly suggest you also install [erri120 DLsite metadata Extensions](https://github.com/erri120/Playnite.Extensions) to use with this script.)***

Portable version: Extensions folder directly inside of Playnite's installation location.

Installed version: %AppData%\Playnite\Extensions folder.


## How to use:
After importing the game, you may see some of your game's name is incorrect such as named "GAME.exe". Select one or more (shift select) games you would like the change then open the main menu and click "Rename Game to DL ID" to run the script. It takes around 5 sec for each game to process on average. If you select more then 20 or 30 games at the same time expect playnite to be freeze for a while. After the script finish you will see all games are now in game id and you can use ctrl+D to redownload all the metadata with erri120 DLsite metadata Extensions.


## logic:
This script tries to extract games name and code from path and also the auto detect field from playnite, it searches at DLsite and google to see if it finds the game code. If it does, it will change the name field in playnite for it to work with the metadata extensions.



![Preview](/Preview.gif)
