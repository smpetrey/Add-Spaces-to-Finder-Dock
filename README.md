# Adding Spacer Tiles to Finder Dock

### Step One
Press `⌘ + Spacebar` to open Spotlight
Type `terminal` and press return to open your Terminal.app

### Step Two
Once you Terminal is open, copy and paste the comand below:

`defaults write com.apple.dock persistent-apps -array-add '{"tile-type"="spacer-tile";}' && killall Dock`

Press return, and boom! Your Spacer Tile should be visible to the left of your Separator Tile (by default this should be on the right-hand side of the dock). Repeat as necessary for more Spacer Tiles! 


#### Notes

Sometimes (and I've noticed this on Yosemite or higher) you have to run

`killall Dock`

an additional time to reload Finder if you want an additional Spacer down there.

_Removing Spacer Tiles_

Same as removing an App from the Dock! Drag to the Trash Can. 
