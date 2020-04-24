# Kozz-s-QL-HUD

________________________________________________________________________________________________________________________________
/
/                                                         VERY IMPORTANT
/
/                                             THIS HUD IS ONLY FOR 1920X1080 RESOLUTION
/                                            IF YOU USE A DIFFERENT ASPECT RATIO EVERYTHING WILL BE DISPLACED  
/                                             USE THE LINK POSTED BELOW TO HELP YOU MOVE HUD ELEMENTS                                         
/
/_______________________________________________________________________________________________________________________________







Once you’ve obtained your .zip UNPACK it. There should be 2 files. 1 .CFG and 1 .MENU

Go to your QuakeLive folder. (Default C:\Program Files (x86)\Steam\steamapps\common\Quake Live)

Open the SteamID folder (Seemingly randomly generated numbers)

open baseq3 folder

create a new folder named "ui" (no " ")

move the .cfg and .menu files into the newly created ui folder

Now all you need to do is load the custom HUD. If you use an autoexec.cfg, you can add the following line to it:

cg_hudFiles “ui/hudname.cfg”

The HUD should be loaded next time you start your game. Or if you are in-game, you can enter cg_hudFiles “ui/hudname.cfg”

To create your own custom HUD use https://icculus.org/~phaethon/q3tamenu/q3tamenu-single.html to understand the language
