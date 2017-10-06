# MHIMP
A Dungeon Siege mod to control more than one heroes in multiplayer.

# Fixed Issues
2017 09 20
Fixed shield export on the summoned character.
Fixed attribute values & skill values from the summoned character.We copy the summoned character's base attribute into save file rather than the value buffed by equipments.

# Readme
This is the ReadMe file for MHIMPsV0_90   (Multiple Heros In Multi-Player)

The MHIMPs IS NOT SUPPORTED IN DS 1.0.  In other words, does not work with DS 1.0.
This mod works in DS w beta patch up to DS 1.11.

Thanks to Icemage, Xaa, Wolf, Major Hostility, iRoNiC, Stargazer, Assembler of Redux; they and others have contributed greatly.

12 17 02 Fixed a bug causing game to crash upon summoning a Hero.  Also cleaned up code a bit.


# How The Mod Currently Works
     MHIMPs is a work in progress.  Currently, the various hero's are summoned by their corresponding summon spell.  After the hero is summoned, he/she starts with what the hero had last time he/she played, or a the basics if this is the first time. 
     Every 60 seconds, the summoned heros stats and inventory are exported via dsdll so that it may be retrieved upon startup next time.

# How To Install The Mod

In the same folder as the DugeonSiege.exe file, remove any previous versions of the StrGthrDyns DSDLL if applicable and place the new StrGthrDynIV.dsdll in the executible folder.
In the resource folder, remove any previous versions of MHIMPs, and place the new MHIMPs.dsres in the DS resources folder.
Place septarian.dsparty in the \Dungeon Siege\save folder, usually found in the my documents folder.  She holds the summon spells/scrolls.
Start up DS and choose Septarian to play and test away.

The heroes are geered to start  at farmhouse level 0.


# Known Issues
The biggest issue is that of difficulty scaling (mp scaling).  In other words the more heroes are on screen the 'easier' taking down monsters will be.  MP scaling only affects actual Multi-Player games on Lan Internet, etc not multiple characters on screen.  Therefore it is advisable to change the formulas.gas MP scaling settings to change the difficulty to your liking.  In the future, I may include a set of Formulas files for those that dont have time/ability to change the file manually.
Portrait icon is not correct with more than one player playing.
Exported information is stored on server...the hosting computer.

Septarian starts of with most of the summonable spells/scrolls.  Others summon scrolls/spells will be dropped randomly etc..
