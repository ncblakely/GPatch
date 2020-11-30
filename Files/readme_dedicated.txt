========================================================
GIANTS:  CITIZEN KABUTO (TM)
Dedicated Server Setup Tool and Launcher Version 1.000
Readme_Dedicated.txt file
========================================================
MARCH 8, 2001

CONTENTS
1.  Release Notes
   	1.1 Server Tool and Launcher Version 1.000
	1.2 Tool Description
	1.3 Functionality
2.  Legal Information

========================================================
1. RELEASE NOTES
	1.1 - SERVER TOOL AND LAUNCHER RELEASE VERSION 1.000
The dedicated server setup program, "dedicated.exe" is installed into your Giants install directory with the 1.4 or greater Giants update.

This program is a free unsupported supplement for advanced Giants users.  Interplay customer support will not be able to help you with issues regarding the dedicated server or launcher.  You might be able to find help with this tool from one of these official or unofficial Giants websites currently on the internet.
http://www.interplay.com/giants
http://www.planetmoon.com
http://www.giantshell.com
http://www.planetmooncentral.com

	1.2 - DESCRIPTION
The dedicated server tool and launcher allows you to create a sequence of Giants Citizen Kabuto games to run.  This sequence will be run in the order they are added to the ouput window looping back to the top when the last game added has ended.

	1.3 - FUNCTIONALITY
Below is a description of what each dialog item does.
Session Name		
: Selects the server name (IE, what gamespy and other players joining the game will see as the server name)
	
Game Type			
: Allows you to select what game type the current sequence being setup will play as.  *Note, it is STRONGLY recommended that you set a time limit for base build games.  Otherwise everybody could leave the server and thus, the points winning conditions would never be met and the server would have to be reset manually.
	
Team Type			
: Allows you to select what races are involved in the game
	
World				
: Allows you to select what world to play on
	
Detente				
: How long before base buildings being damaged and flag captures can happen
	
Points Per Kill		
: How many points each kill of an opposing team member is worth
	
Points Per Cature	
: How many points capturing the flag is worth
	
Player Score Limit	
: How many points an individual needs to end the level and load the next server setup
	
Team Score Limit	
: How many points a team needs to end the level and load the next server setup
	
Time Limit			
: How long current server setup will wrong before loading next setup
	
Base Destroyed		
: Game will end if team base is completely destroyed (defend base and base build games only)
	
Allow Team Damage	
: Allow players on the same team hurt each other
	
No Vimps			
: Disable vimps for this setting (best for mecc vs mecc levels)
	
Smartie Difficulty	
: How many smarties are in the world
	
Vimp Difficulty		
: How much energy you get per chunk of meat (base building only)
	
Max Players			
: Maximum number of players the server can hold.  Will be the same for all server setups.  This number includes the server itself, so a 20 person game can really only have 19 people in it.

Min Players			
: Minimum number of players the server will start the game with.  This is ignored for everything but base build games.  If it is a base build game, and min players are not on the server, the setting is skipped and the next one is used.  If no settings are playable, the server will wait until min players is reached on one of the settings before launching.

Configure Mecc Weapons	
: Selecting items in this dialog allow the weapon for the game.  Unselecting it makes it completely unavailable to the player
	
Configure Reaper Weapons	
: Selecting items in this dialog allow the weapon for the game.  Unselecting it makes it completely unavailable to the player
	
Load				
: Load a currently saved dedicated server file (gdf file)
	
Save				
: Save the current dedicated server file (Note that in order for giants to run the dedicated server, the file MUST be saved in the /bin directory which this tool should default to)
	
Save As				
: Save the current dedicated server file with a new name (Note that in order for giants to run the dedicated server, the file MUST be saved in the /bin directory)
	
Copy				
: Copy currently selected server (in output window) into game settings
	
Launch				
: Run the dedicated server currently loaded (Note that in order for giants to run the dedicated server, the file MUST be saved in the /bin directory)
	
Exit				
: Exit the dedicated server tool
	
Overwrite			
: Overwrite the current server settings over the currently selected server in the output window
	
Add Top				
: Add current server settings to the top of the output window
	
Add Before			
: Add current server settings before the currently selected server in the output window
	
Add After			
: Add current server settings after the currently selected server in the output window
	
Add End				
: Add current server settings to the end of the output window
	
Delete				
: Delete the currently selected server setting from the output window

Reset
: Clear all current server settings and force back to initial state

Auto Copy
: Copy item selected from output window into the current settings on the left automatically

Auto Overwrite
: Automatically update the selected output window with changes made on the left hand side

-- Additional Command Line Parameters --

Extra command line paramaters used when launching the dedicated server.  Most valid Giants command line parameters can be used (-window strongly recommended).

Enabling/Disabling Weapons and Buildings:
"-wep X Y" 
The dedicated server tool allows a graphics interface for the selection of available weaopons.  A non-dedicated host can set weapon availability only through the command line.  Use "-wep X Y" where X and Y are hexadecimal numbers representing which weapons you do not want in the game.  X represents Mecc weapons/items, and Y represents Reaper weapons/spells/items.  Each number can be a combination of the following hex values:

WEP_UNAVAIL2_MECC_RPG			0x00000001
WEP_UNAVAIL2_MECC_SNIPER		0x00000002
WEP_UNAVAIL2_MECC_HOMING		0x00000004
WEP_UNAVAIL2_MECC_PROXIMITY		0x00000008
WEP_UNAVAIL2_MECC_ROCKET		0x00000010
WEP_UNAVAIL2_MECC_SYRINGE		0x00000020
WEP_UNAVAIL2_MECC_MINE			0x00000040
WEP_UNAVAIL2_MECC_FLARE			0x00000080
WEP_UNAVAIL2_MECC_GRENADE		0x00000100
WEP_UNAVAIL2_MECC_BUSH			0x00000200
WEP_UNAVAIL2_MECC_POPUPBOMB		0x00000400
WEP_UNAVAIL2_MECC_TURRET		0x00000800
WEP_UNAVAIL2_MECC_JETPACK		0x00001000
WEP_UNAVAIL2_MECC_SHIELD		0x00002000
WEP_UNAVAIL2_MECC_MACHINEGUN		0x00004000
WEP_UNAVAIL2_MECC_MILLENIUM		0x00008000
WEP_UNAVAIL2_MECC_PHTURRET		0x00010000
WEP_UNAVAIL2_MECC_PHSAM			0x00020000
WEP_UNAVAIL2_MECC_PHTELEPORT		0x00040000
WEP_UNAVAIL2_MECC_PHTOWER		0x00080000
WEP_UNAVAIL2_MECC_PHGIFTSHOP		0x00100000
WEP_UNAVAIL2_MECC_PHGYROPAD		0x00200000

WEP_UNAVAIL1_RP_SMARTIE_GRAB		0x00000001
WEP_UNAVAIL1_RP_CLUSTER			0x00000002
WEP_UNAVAIL1_RP_CLOAK			0x00000004
WEP_UNAVAIL1_RP_TELEPORT		0x00000008
WEP_UNAVAIL1_RP_FIREWALL		0x00000010
WEP_UNAVAIL1_RP_HAIL			0x00000020
WEP_UNAVAIL1_RP_TIME			0x00000040
WEP_UNAVAIL1_RP_SHRINKER		0x00000080
WEP_UNAVAIL1_RP_SLOW_FOLLOW		0x00000100
WEP_UNAVAIL1_RP_FIRE_CIRCLE		0x00000200
WEP_UNAVAIL1_RP_TORNADO			0x00000400
WEP_UNAVAIL1_RP_MINE			0x00000800
WEP_UNAVAIL1_RP_FLARE			0x00001000
WEP_UNAVAIL1_RP_SYRINGE			0x00002000
WEP_UNAVAIL1_RP_RPG			0x00004000
WEP_UNAVAIL1_RP_HOMING			0x00008000
WEP_UNAVAIL1_RP_SNIPER			0x00010000
WEP_UNAVAIL1_RP_POWERUP			0x00020000
WEP_UNAVAIL1_RP_PHTURRET		0x00040000
WEP_UNAVAIL1_RP_PHSAM			0x00080000
WEP_UNAVAIL1_RP_PHTOWER			0x00100000
WEP_UNAVAIL1_RP_PHTELEPORT		0x00200000
WEP_UNAVAIL1_RP_PHREAPERSKI		0x00400000
WEP_UNAVAIL1_RP_PHSEAMONSTER		0x00800000
WEP_UNAVAIL1_RP_PHSPELLSHOP		0x01000000

So if the command line had "-wep 0x00000009 0x01020000" the Reaper would not be able to use the powerup bow OR build a spellshop from the partyhouse and the Mecc would not be able to use the RPG or proximity missiles.  However, the Reaper would be able to get the tornado spell and the Mecc would be able to get the popup bomb even in non-fullbase games.

Designating Remote Host Abilities:
Remote hosts can now be designated through chat commands detailed below.
Currently Supported Features for the Designated Server:
1) Kick people from the game
2) Change any players team
3) Toggle team damage
4) Toggle party house friendly fire (from nophff in the chat window)
5) Adjust detente time
6) End the current game
7) Change the player markers (from pmarkers in the chat window)


-- New Chat Passwords --

Type these into the chat window during the game if you are the actual dedicated server.

1) "newhost name": 
"name" is the name of the player to become the remote administrator (assuming the player exists). This will remove administrator status from anybody currently with the status and give it to the new person.

2) "nonewhost"
Removes remote administrator status from all the clients.


========================================================
2.0 LEGAL INFORMATION

SOFTWARE USE LIMITATIONS AND LIMITED LICENSE

General Product License. This copy of Giants: Citizen Kabuto (the Software) is intended solely for your personal noncommercial home entertainment use. You may not decompile, reverse engineer, or disassemble the Software, except as permitted by law. Interplay Entertainment Corp. and Planet Moon Studios retain all right, title and interest in the Software including all
intellectual property rights embodied therein and derivatives thereof.
The Software, including, without limitation, all code, data structures, characters, images, sounds, text, screens, game play, derivative works and all other elements of the Software may not be copied, resold, rented, leased, distributed (electronically or otherwise), used on pay-per-play, coin-op or other for-charge basis, or for any commercial purpose. Any
permissions granted herein are provided on a temporary basis and can be withdrawn by Interplay Entertainment Corp. at any time. All rights not expressly granted are reserved.

MODEM AND NETWORK PLAY. If the Software contains modem or network play, you may play the Software via modem transmission with another person or persons directly without transmission through a third party service or
indirectly through a third party service only if such service is an authorized licensee of Interplay. For the purposes of this license, a third party service refers to any third party service which provides a connection between two or more users of the Software, manages, organizes, or facilitates game play,translates protocols, or otherwise provides a service which commercially exploits the Software, but does not include a third party service which merely provides a telephonic connection (and nothing more) for modem or network play. Authorized licensee services are listed on the Interplay Entertainment World Wide Web Site located at
http://www.interplay.com. This limited right to transmit the Software expressly excludes any transmission of the Software or any data streams thereof on a commercial basis, including, without limitation, transmitting the Software by way of a commercial service (excepting those
specific commercial services licensed by Interplay) which translates the protocols or manages or organizes game play sessions. If you would like information about obtaining a pay-for-play or commercial license to the
Software, please call Interplay Productions in the US at +(949) 553-6655.

ACCEPTANCE OF LICENSE TERMS. By acquiring and retaining this Software, you assent to the terms and restrictions of this limited license. If you do not accept the terms of this limited license, you must return the Software together with all packaging, manuals and other material
contained therein to the store where you acquired the Software for a full refund.

========================================================
Giants Citizen Kabuto: Copyright 2001 by Planet Moon Studios.  All Rights Reserved.  Planet Moon and the Planet Moon logo are trademarks of Planet Moon Studios.  Giants, Giants: Citizen Kabuto, Interplay, the Interplay logo, "By Gamers For Gamers", Digital Mayhem and the Digital Mayhem logo are trademarks of Interplay Entertainment Corp.  All Rights Reserved.  Exclusively licensed and distributed by Interplay Entertainment Corp.  All other copyrights and trademarks are the property of their respective owners.
========================================================

< End of File>