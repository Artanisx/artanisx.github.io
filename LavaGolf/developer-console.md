---
layout: default
title: "Lava Golf"
permalink: /LavaGolf/developer-console/
---
# Lava Golf - Developer Console
During Alpha and Beta, testers can access the Developer Console directly from the game itself. Thanks to that, you can quickly change levels (to see more difficult ones faster), or even take screenshots. While the Developer Console is pretty powerful, we advise you not to use it too hastily. Try to beat a level on your own, so you can tell us better how it felt and if it was really too difficult. This game is designed to be hard, a roguelite take of Golf, so it's expected to take quite a few tries to beat a level!


## How to operate the Developer Console
In order to open the Developer Console you need to push the **TAB KEY** on your keyboard. It will open the console, and now you'll be able to type your commands. Each command must be prefixed with \.
You can check all available commands directly in the console typing **\help**

The list of the commands follows:
* **\help**: This command will show all available commands with an explanation for each.
* **\gravity X.Y**: This command changes the gravity of the level to the passed float value. Example: "\gravity 10.3"
* **\ss X**: Takes a screenshot immediately and save it to the LavaGolf folder (inside the Lava Golf_Data subfolder in the game installation path.). If a number is passed, the screenshot will be taken at a resolution multiplier. This multiplier should be given in numerical form between 1 to 8. Example "\ss 2". If no number is passed, 1 will be assumed matching the current resolution.
* **\warptolevel x**: Warps directly to the selected level. The level should be given in numerical form between 1 to 9. Example "\warptolevel 2"
* **\winlevel**: Wins the current level. Only works if used during a level scene.

## Links

 Go back to the Lava Golf main page here [Lava Golf](https://artanisx.github.io/LavaGolf). 
 
 Go back to the Itch.io page for the game [here](https://artanisx.itch.io/lava-golf).
 
 Go back to the [Beta Patch Notes](https://artanisx.github.io/LavaGolf/beta-patch-notes).
