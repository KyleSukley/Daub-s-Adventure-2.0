  ____    _   _   _ ____           _       _                 _                  
 |  _ \  / \ | | | | __ ) ___     / \   __| |_   _____ _ __ | |_ _   _ _ __ ___ 
 | | | |/ _ \| | | |  _ \/ __|   / _ \ / _` \ \ / / _ \ '_ \| __| | | | '__/ _ \
 | |_| / ___ \ |_| | |_) \__ \  / ___ \ (_| |\ V /  __/ | | | |_| |_| | | |  __/
 |____/_/   \_\___/|____/|___/ /_/   \_\__,_| \_/ \___|_| |_|\__|\__,_|_|  \___|
                                                                                
FBLA Computer Game and Simulation Programming 2014-2015
Abington Senior High School — Nima Eskandary, Michael Gilmour, Kyle Sukley
D.A.U.B.’s Adventure version 3.0 5/2/2015

-------------------
GENERAL USAGE NOTES
-------------------

- Tested on Google Chrome, Firefox, and Safari
- ! Will not work with Internet Explorer !
- Launch by opening the index.html from the directory with your desired browser, or by opening your browser and using [ctrl+O] (command+O for mac), and selecting the index.html file to open
- The start button will say "Loading...." until the game is done loading and you will not be able to start the game in this state, the text will change to prompt the user 
- In the level difficultly selection, do not click and choose a difficultly unless it is highlighted green
- If you are experiencing problems, attempt to refresh the game after it has fully loaded once

-----------------
GAME INSTRUCTIONS
-----------------

- The game alternates between two different modes:
- Desktop mode, where the player finds him/herself on the desktop of a computer and walks around looking for infected directories
- Sidescroller mode, where the player is investigating a directory and traverses several maps filled with enemies

- At any time pressing 'P' will bring up the pause menu which will show instructions, and has a mute button
- Pressing ESC will quit the game
- Desktop:
	-WASD to move
	-Space to view and purchase available upgrades
- Sidescroller:
	-A and D to move left and right
	-W to jump; double jumping is available initially and triple jumping can be unlocked
	-SPACE to shoot anti malware discs
	-Ammo boxes and Health boxes can be collected for boosts, and coins help accumulate score
- There is a dialogue system used for the game's story, and will prompt the user with options such as advancing the text, and investigating a directory
- SCORE is accumlated by collecting coins and destroying malware; used to buy upgrades
	-coins are worth 100 points
	-the smallest malware minions are worth 200 points
	-second smallest are worth 400 points
	-largest are worth 600 points

-------------------
FOLDER DESCRIPTIONS
-------------------

- The Images folder has all the images used in the game, in png formats 
	-Spritesheet.png is comprised of most of the 2d animations 
	-all artwork is original 
- The Sounds folder has all the sound effects and music used in the game

-----------------
FILE DESCRIPTIONS
-----------------

- Original code:
	-index.html: html skeleton for our page 
	-stylesheet.css: dimensions and attributes for html elements used in our game
	-main.js: javascript file that has objects and event handlers such as pausing , upgrades, and start game button
	-fble.js: (Future Business Leaders Engine) Personal game engine developed to make DAUBs Adventure. Contains collision, player movement, enemy, map, and physics algorithms along with much more
	-fble API.txt : Though all of our code is documented, a desciption of every method used in fble.js is included due to its size
- Tools: 
	-jquery-1.11.1.js: javascript library used in our game
	-gameQuery.js: javascript library used in our game, used to handle things like onscreen sprite movement 

-------------
PROGRAMS USED
-------------

- Google Chrome : developer testing
- https://c9.io : collaborative programming development environment
- NotePad++ : native development, rarely used after c9.io was adopted 
- Adobe Photoshop CC 2014 : graphical design
- Paint : graphical design

--------
LICENSES
--------

- 	jQuery JavaScript Library v1.11.1
	http://jquery.com/
	Includes Sizzle.js
	http://sizzlejs.com/
	Copyright 2005, 2014 jQuery Foundation, Inc. and other contributors
	Released under the MIT license
	http://jquery.org/license
	
-	gameQuery rev. 0.7.1
	Copyright (c) 2012 Selim Arsever (http://gamequeryjs.com)
	licensed under the MIT-License

-	SONGS:
	Carefree.mp3, PixelPolka.mp3, boss.mp3, Track.mp3 -Kevin MacLeod (incompetech.com)-
	Licensed under Creative Commons: By Attribution 3.0
	http://creativecommons.org/licenses/by/3.0/
	
- 	Quick Sound Effects:
	https://www.freesound.org/
	(Due to the length of these sounds, no further documentation is necessary as according to creativecommons.org — CC0 1.0 Universal (CC0 1.0) license)
