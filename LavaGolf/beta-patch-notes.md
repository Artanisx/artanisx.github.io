---
layout: default
title: "Lava Golf - Beta Patch Notes"
permalink: /LavaGolf/beta-patch-notes
---
# Lava Golf - Beta Patch Notes

In here the beta patch notes for Lava Golf!
As a reminder, you can access our Itch.io page for the game [here](https://artanisx.itch.io/lava-golf).


## Patch notes

### Version 1.15 - In development:

This is a minor patch for the Beta! Currently in development.

*Fixes and Changes*
* (I) Changed the behaviour of the screenshots logic to avoid the known issue that would prevent the screenshots to be taken if you installed the game in the default directory (inside "Program Files") while not running the game as administrator. The screenshots will now be created inside Documents folder (My Games\Lava Golf\Screenshots), a more standard approach.
* (I) It is now possible to take screenshots while in the main menu, in the victory screen, in the power up screen and in the game over screen (alongside all levels as usual).
* (I) Taking a screenshot will now show a fading in & out text message as feedback a screenshot has been taken.
* (I) Taking a screenshot will play a sound effect.

### Version 1.1 - 27/04/2021:

This is the first patch for the Beta and includes the fixes some of our dear beta tester asked for!

*Graphics*
* Added a small visual effect to celebrate the player when the End Portal is reached.
* After reaching the end portal, the ball will disappear as intended. The camera will move slightly upwards to let the player take a view to the fireworks.
* After completing a level, the next level won't load instantly, allowing the player to watch the new celebrative visual effect.
* Added a small visual effect when the player gathers an X Sphere.
* Added a small visual effect when the player crosses a Lava Ring.
* Added an animated Crystal Golf Tee in all levels, so the ball rests on it before being launched for the very first time.
* Rebaked all levels to account for the new animated Crystal Golf Tee.
* Added smoke particle effects in the lava across all levels.
* Added lava bubbles effects in the lava across all levels.

*Audio and Music*
* Added a small audio effect to celebrate the player when the End Portal is reached.
* Added a sound effect for the fireworks that spawn after entering the End Portal.

*UI*
* The help text for the **GROUND DASH** is now fixed. Due to a bug it showed a copy of the description of the AIR BRAKE. The actual description for the GROUN DASH is: "The ball rolls forward, allowing the player to try to collect more X Spheres or to avoid falling from a platform. There are a finite amount of charges, but they get replenished each time you land. Usable only on the ground".
* The game levels are now called "COURSES" (it's a golf game after all) to avoid any confusion with player levels.
* When you mouse over on a button in the Main Menu the lightning effect is now more pronounced.
* The text "Press any key to start!" in the Loading Screen for the very first level has been changed to make it more readable.
* Added explanation on the number of shoots for each level in the Game Help screen.
* Updated the game help desciptions mentioning "forward" with "the direction you're aiming" to avoid confusion.
* Added more elements to the Help Screen guide, including the UI element for Lava Rings, X Spheres and the Shoots.
* Added a Video Guide in the Help Screen to show you the ropes of Lava Golf. The video can be played in full screen / switched back clicking on the video itself. Make sure to check it out!
* UI element for Air Brake and Ground Dash are now swapped. Air Brake is now in the bottom right, while Ground Dash is now in the bottom left corner of the innate skills UI.
* Fixed an issue in the Power Up Sceen that would let the tooltip show during the loading if a player used Space/Enter to click the CONTINUE button while still hovering with the mouse on a skill.
* Credits have been updated.
* Added a visual cue (a "bar" that is filled) to inform the player the next shoot is about to be performed.
* Now the Pause Menu controls are properly split in two separated lines.
* Changed the game ui elements so that it doesn't mentions "Rings", "X Spheres" and "Shoots" no longer as they are properly explained by the use of the related icon (plus the How to Play screen explains them at lenght). Now the UI is more compact as a result and more readable. 
* Did a pass on all in game help strings to improve clarity.
* Reflected the new usability rules for the Rewind skill in the game ui.
* Updated the Game Help guide on the Rewind skill to reflect the new usability rules.
* Fixed a bug that prevented the new Launch Bar to be shown after a Rewind was used.
* Updated the Game Help guide in accordance with the balance pass on the Air Brake.
* Added loading tips.
* Added the Twitter and Itch.io buttons in the main menu to bring you directly to Lava Golf's Twitter page and the Lava Golf's Itch.io page.
* Fixed a bug that would hide the cursor when the player cleanly enters the end portal without touching the borders.

*Controls*
* You can now go back to the Main Menu at any point during the gameplay, with the ESC key (or the "START" button on your gamepad).
* Changed the Camera control angle to avoid a bug when looking down.
* You can now quit the overview camera with the SPACEBAR as well.
* You can now take a screenshot of the game by pressing F12. Developer Console is not required for this action.

*Gameplay and Levels*
* Fixed the number of actual Lava Rings in Level 7 (for real this time).
* Fixed a collider issue with the starting platform in Level 3.
* Edited the collider for the Green Portal so it doesn't trigger before the ball properly enters the portal to avoid a very rare visual bug.
* Minor rings position tweaks in some levels.

*Balance*
* The Rewind skill can now only be used while in the air.
* Now the Air Brake is FAR more powerful. It also gives some grace period before applying gravity back. Using an Air Dash will instantly restore the proper drag and gravity values.

*Known issues*
* If you install the game in the default directory (inside "Program Files"), you won't be able to take screenshots unless you run the game as Administrator.

### Version 1.0 - 23/03/2021:

First beta release!

The Lava Golf beta finally starts. Below some of the changes we implemented from the last Alpha version.

*Graphics*
* Completed the final lightning baking pass on all levels.
* Updated the font color in the Air Dash description in Game Help Scene
* Added the game icon!
* Added a game cursor!
* The H.E.I. logo has been updated in the splash screen.
* Updated the background scene in the Credits.
* Antialiasing fixes.
* Fixed Camera on Power Up Scene. 
* Updated the graphics settings for the High Quality preset.
* Now the cursor is hidden while in first person camera mode.

*Audio and Music*
* Added a music theme for the Game Over screen.
* Added a music theme for the Victory screen.
* Added two different ambience sound effect for the Lava.
* Added a sound effect for the Level Up.
* Added a sound effect for X Spheres collection.

*Gameplay and Levels*
* Swapped a platform in Level 5 to fix a rare issue.
* Swapped a platform in Level 7 to fix a rare issue.
* Fixed the number of actual Lava Rings in Level 7.

*Features*
* Added the screenshots functionality to the [Developer Console](https://artanisx.github.io/LavaGolf/developer-console). Beta testers can use this to take screenshots to accompany their feedback. Open the console with the Tab key and type \ss to take a screenshot. The screenshot will appear in the Screenshots folder inside the Lava Golf_Data subfolder in the game installation path. 

*UI*
* When using a gamepad, they buttons are now properly shown in the game UI interface, replacing the Keyboards keybindings.
* Gamepad buttons are shown in a more clean way, replacing "Gamepad_X" with "(X)" and similar text changes.
* Beta version has been reached, as shown in the UI from the Main Menu screen.

## Links

 Go back to the Lava Golf main page here [Lava Golf](https://artanisx.github.io/LavaGolf).
 
 Go back to the Itch.io page for the game [here](https://artanisx.itch.io/lava-golf).
