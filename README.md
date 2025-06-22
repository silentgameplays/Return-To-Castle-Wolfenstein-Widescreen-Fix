# RTCW-Widescreen-Fix
FHD Fix For Return To Castle Wolfenstein
How to fix to FHD

1. Download Return To Castle Wolfenstein WideScreen Fix 

2. Extract anywhere

3. Copy/Paste into your Return To Castle Wolfenstein Steam or GoG directory

4. Set the resolution to 1920x1080 in game settings 

5. Enjoy!

# Alternative Resolution Fix(No need to download anything)

1. Launch the game at least once then exit.

2. Find the file wolfconfig.cfg  in the game isntall directory C:\Program Files (x86)\Steam\steamapps\common\Return to Castle Wolfenstein\Main

3. Modify the following values in wolfconfig.cfg to: 

* seta r_customaspect "1"
* seta r_customheight "1080" (where 1080 or anything else is your desired vertical resolution)
* seta r_customwidth "1920"  (where 1920 or anything else is your desired horizontal resolution)
* seta r_mode "-1"

4. # Fix Low Brightness Issue for recordings:
* Crank Brightness to the desired levels in Settings
* Go into C:\Program Files (x86)\Steam\steamapps\common\Return to Castle Wolfenstein\Main
* Open wolfconfig.cfg

# change
* seta r_ignorehwgamma "0"
# to 
* seta r_ignorehwgamma "1" 

5. Enjoy!
# Works by copy/pasting with GOG and Steam versions on Linux as well

Thanks
#silentgameplays
