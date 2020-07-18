# LootTrackerExtension
Chrome extension for the LootTracker App at https://loot-trackerz.herokuapp.com/

## Installation
Download the repo at https://github.com/SaskuatchofAZ/LootTrackerExtension, 
in the Chrome extension window (chrome://extensions) tick Developer Mode in 
the upper right-hand corner of the window. Then click "Load unpacked" on the
upper left-hand side and navigate to the root directory for LootTrackerExtension
and load it into the extensions.

## Usage
You must login at https://loot-trackerz.herokuapp.com/ and keep the page open 
before using this extension in every new instance of Chrome.
The browser extension will only be active on pages with the url pattern of:
https://store.steampowered.com/app/* or http://store.steampowered.com/app/*.
Upon loading one of the app pages a button will appear on the page in the box
on the right-hand side declaring the playstyles of the game e.g. Singleplayer,
Multiplayer. 

On click of the button you will be redirected to the app page which will alert you if
the game was added successfully and then redirect you to your wishlist page.

Happy hunting and enjoy LootTracker!