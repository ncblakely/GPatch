========================================================
GIANTS:  CITIZEN KABUTO (TM)
Readme_English.txt file
========================================================
May 24, 2000

CONTENTS
1.  Latest changes
   	1.1 Retail release
	1.2 Revision history
	1.3 Dedicated server
	1.4 Proxy, NAT, and Firewall
	1.5 Multiplayer Connectivity

2.  Getting Started
	2.1 System requirements
	2.2 Default controls

3.  Manual Addenda
	3.1 Undocumented features
	3.2 Manual additions/corrections
	3.3 Extras

4.  Multiplayer
	4.1 Playing on the Internet
	4.2 Playing on a LAN
	4.3 Hosting a game

5.  Troubleshooting/Technical Information
	5.1 Video card compatibility
	5.2 Troubleshooting command line options
	5.3 Multiplayer command line options
	5.4 Improving Performance
	5.5 Known Issues
	5.6 Help References
	5.7 Ikernel.exe install error

6.  Interplay Customer Service Information

7.  Legal Information

========================================================
1.0 LATEST CHANGES
	1.1 - RETAIL RELEASE. You can check for software
updates or the latest Giants information on the web at "http://www.interplay.com/giants".

	1.2 - REVISION HISTORY. You can view additions and corrections made to Giants since the retail release by opening up the "history.txt" file in your Giants install directory.

	1.3 - DEDICATED SERVER. You can find information on running the dedicated server by opening up the "readme_dedicated.txt" file located in your Giants install directory.

	1.4 - PROXY, NAT, AND FIREWALL. Giants now has better support for shared internet connections.  It should now work more reliably through NATs (Ex. Internet Connection Sharing), and Proxies (WinSock Proxy).  Depending on your network setup you may have to forward or open up 19711 UDP port to run Giants.  The port that Giants uses can be changed via a command line option by using "-port ####".  Example, "C:\Program Files\Giants\Giants.exe -port 4000".

	1.5 - MULTIPLAYER CONNECTIVITY. In a multiplayer game of Giants with 6 or more players, some players on 56k modems may have trouble staying connected to the server. This is because a large game requires a high quality connection to the server due to the large amount of data that needs to be transmitted between the server and each player.  Although most players on modems have no trouble at all, your modem or your ISP may cause connectivity problems such as latency or packet loss, and you may get disconnected from a large Giants game with the message "You lost your connection to the server."  If this happens repeatedly, try joining a server that has fewer players or a server to which you have a lower ping (better connection).  Also, make sure your modem internet connection is configured correctly.  The following list of websites may provide some help in tweaking your internet connection to optimize your online Giants experience:

	http://www.tweak3d.net/tweak
	http://www.pattersondesigns.com/tweakdun
	http://www.speedguide.net
	http://www.dslreports.com

Note: Use caution when attempting to optimize your internet connection.  Neither Interplay nor Planet Moon Studios officially endorse the methods of optimization included in the links above.

========================================================
2.0 GETTING STARTED
	2.1 SYSTEM REQUIREMENTS
-<REQUIRED>-
Windows 95/98/2000/ME with DirectX 8.0 (included)
Pentium II/K62 350 MHZ
64MB RAM
875MB Hard Drive space for installation
4X CD-ROM drive
DirectX certified sound card
8MB Direct3D compatible video card
100% Microsoft compatible keyboard and mouse
-<RECOMMENDED>-
Pentium II/K62 450 MHZ or higher
128MB RAM
1200MB Hard Drive space for max installation
16MB or higher Direct3D compatible video card
-<MULTIPLAYER>-
Up to 10 players supported via TCP/IP protocol
Clients should have a minimum 28k connection
Host should have a minimum 56k connection
	
	2.2 DEFAULT CONTROLS
All three races share some of the controls.
-<Common controls>-
Look up/down:Turn left/right		Mouse
Run Forward				W
Run Backward				S
Run Left				A
Run Right				D
Use Weapon/Attack			L. mouse click
Special Camera				F
Toggle First Person			R
Zoom Mode				E
Zoom In					Z
Map Mode				C
Chat Team (multiplayer)			Y
Chat All (multiplayer)			T
Chat History				F2
Multiplayer Options and Score		F1

-<Meccaryns(Baz)>-
Activate Back Item			Left Shift
Activate Party House Item		X
Cycle Weapon Forward			Q
Cycle Weapon Backward			Tab
Give Health				H
Throw Grenade				G
Throw Mine				B
Use Flare				V
Thrust					R. mouse click
Nitro					Space bar
Disciple Mode				Left Control
Disciple Attack				L. mouse click
Disciple Recall				2
Disciple Goto				R. mouse click
Drop Smartie/Backpack item		Backspace
Drop Current Weapon			J
{Gyrochopter Keys}
Fly Forward				W
Fly Left				A
Fly Right				D
Thrust					R. mouse click
Attack/Use Machinegun			L. mouse click
Use Millenium Cannon			G

-<Reapers(Delphi)>-
Select Spell				Left Shift
Select Spell Backward			End
Select Spell Forward			Delete
Turbo					R. mouse click
Cast Spell				Space bar
Cycle Weapon Forward			Q
Cycle Weapon Backward			Tab
Jump					Left Alt
Select Spell 1				1
Select Spell 2				2
Select Spell 3				3
Select Spell 4				4
Select Spell 5				5
Drop Select Spell			K
Give Health				H
Throw Mine				B
Use Flare				V
Activate Party House Item		X
Drop Smartie			        Backspace
Drop Current Weapon			J
{Reaper Ski Keys}
Reaperski Forward			W
Reaperski Left				A
Reaperski Right				D
Reaperski Turbo				R. mouse click
Reaperski Fire				L. mouse click

-<Kabuto>-
Offspring Mode				Left Control
Grab					R. mouse click
Adrenaline				Left Shift
Lay Egg					L
Summon Offspring			2
Use Spike				X
Roar 1					Insert
Roar 2					Home
Roar 3					Page Up
Sprint					Space bar
Jump					Left Alt
Burn					Q

========================================================
3.0 MANUAL ADDENDA
	3.1 - UNDOCUMENTED FEATURES
*	Your mecc disciples(Tel, Reg, Gordon, and Bennett) have a limited amount of damage they can take. When their health gets to zero they have to rest for a little while.  If they get brought to zero enough times they will be too damaged to move for the rest of the mission.  If you have a repair gun you can heal them as well as yourself and buildings.
*	You can return to regular gameplay from inventory and building screens by clicking or pressing spacebar while the cursor is over the blue return arrow.
*	By going to the map screen (default 'c'), you can click or press spacebar while over the "i" symbol to toggle the mission objective screen on and off.
*	During single player base building missions the buildings that you have completed will stay in your base if you retry a mission.  This is not a bug, but the way we decided to allow the player to not have to start over from scratch on the longer base building missions.
*	You cannot carry smarties while carrying the Pop-up bomb, it is too heavy.
*	Reaper spell casts:  a)  Using your soul energy you can refill your spell casts by holding down the "select spell" button(default left shift) and left clicking on the spell you want to replenish.  The more powerful the spell the more soul energy is required.  b)  The tornado spell is too powerful for a Reaper to have more than one cast available at a time.

	3.2 - MANUAL ADDITIONS/CORRECTIONS
*Reference card error, the default Nitro for the Meccs is Spacebar not shift.
*Page 8  - The lighting option was removed.  Player Shadows and General Shadows were combined into Shadow Detail(High/Low/Off).  Enhanced Wave Effects(On/Off) was added.  This option chooses between using special wave effects on or off.
*Page 13 - Smarties: Not all Smarties can be trusted.  Sea Reapers have some Evil Smarties on their side.  They look darker and more sinister than regular Smarties, and will try to hide at the sight of you.
*Page 20 - Husks are listed as Barracks in the game.
*Page 24 - Spell Indicator:  Delphi can also get soul energy from other creatures, like Sea Reapermen.
*Page 26 - Adrenaline Indicator: You only see the Adrenaline Indicator when Kabuto is full-grown. 
*Page 22 - Weapon Icons: Green brackets surround the weapon icon, not blue.
*Page 48 - The cluster mine spell was removed from Giants.
*Page 49 - Persuader: The persuader will accept soul energy from any creature that gives you soul energy not just Vimps.
*Page 68 - Détente option replaced the Prevent Capture Time option.  This option prevents capturing Smarties or damaging buildings for a specified time.

	3.3 - EXTRAS
*If you pre ordered Giants from one of the participating stores like, "http://www.interplay-store.com" you will also receive the additional Lost World multiplayer maps. Only players with this bonus CD will be able to host multiplayer games with the bonus maps.  You can still join Lost World map games without this CD.
   
========================================================
4.0 MULTIPLAYER
Giants officially supports up to 10 players via TCP/IP.  The faster your connection and systems are, the more players you will be able to support.
	4.1 - PLAYING ON THE INTERNET
	You can find other players on the internet using Gamespy Arcade, or a direct IP address.
-<{Mplayer}>-	
	After the release of Giants, Gamespy bought out Mplayer and has since discontinued support for the Mplayer Giants lobby.  We can no longer support multiplayer through Mplayer, please use Gamespy Arcade instead.
-<Gamespy Arcade>-
	You can use gamespy arcarde to find other Giants players on the internet.  Go to http://www.gamespyarcade.com and download the latest version.  Follow the onscreen instructions for setup and go to the Giants lobby.
-<Direct IP>-
	The player that created the game needs to give his IP address to all the joining players. After a player selects to join a multiplayer game they will need to type the host's exact IP address to see the game.  The host can find out what their IP address is from the Windows desktop by selecting Start --> Run --> and typing winipcfg.exe or ipconfig.exe.

	4.2 - PLAYING ON A LAN
	If you have TCP/IP properly setup on all of the game systems, players will see all joinable games after searching the local net. 
	 
4.3 - HOSTING A GAME
	Connection and system speed are very important when hosting a game.  The system with the fastest connection and processor should host the game for optimal performance.  Internet lag/latency varies widely across different configurations, below is a recommendation for number of players a host should be able to support based upon connection speed.  The biggest limiting factor for the host is upstream connection speed.
*56K modem - 2 to 4 players
*ISDN	- 2 to 6 players
*Cable/DSL - 2 to 8 players
*T1/LAN - 2 to 10 players
*More than 10 players can theoretically be selected, but is not supported at this time.  
Try Mecc vs Mecc or Reaper vs Reaper games for some good balanced competition.  If you are looking for something not quite as equal, but a lot of fun try Mecc vs Reaper or Mecc vs Reaper vs Kabuto.  Each race is not meant to be an equal one on one.  One Kabuto to two Reapers to four Meccs is a good balance to start with, but have fun trying out different combinations for yourself.
	Advanced users might want to try some of the multiplayer command line options listed in section 5.3 of this readme.

========================================================
5.0 TROUBLESHOOTING INFORMATION
	5.1 VIDEO CARD COMPATIBILITY
	Below is some information mainly gathered from Interplay's quality assurance and compatibility departments regarding video card compatibility.  While we made every effort to get Giants to work with all video cards that we could the reality is not all cards are created equal.  Unless otherwise noted we found that using the VERY LATEST reference drivers provided the best stability and performance on all video cards. 

*Nvidia Geforce and Geforce2(all) - Giants is a real visual treat with this card.  
*Nvidia TNT2 - Works ok.
*Nvidia TNT - On some TNT 1 cards using 1280 x 1024 32bit: Switching to this resolution reports a Game Error screen, "Too many tries in texture reduction mode."  This may get corrected on a video card driver or game update. 
*3dfx Voodoo4/5 - Works ok.
*3dfx Voodoo3 - Works ok.  Frame rate may improve with a driver update from 3DFX.
*3dfx Voodoo Banshee - Works ok.
*3dfx Voodoo2 - The first time you switch to this card from your primary display adapter may cause some minor graphic corruptions.  This condition was corrected by exiting Giants and restarting the program.  The sun flare effect should be turned off on most of these cards.  The sky may not display properly in 640x480 on some cards.  Try using the -mixcolor and -noblend command lines if you are having problems.  
*3dfx Voodoo Rush - In 800 x 600: There is a horizontal green line the runs through the top of the in game screen.  This video card is no longer supported by the manufacturer.
*Ati Radeon - At the time of this writing, Ati has developer only drivers that correct a hard lock problem using their drivers while playing Giants.  Hopefully public drivers will be released from Ati that correct this problem by the time Giants is on store shelves.  Check "http://www.ati.com" for the absolute latest video drivers.  You can avoid this hard lock on most systems by disabling the Environment Mapping option on the Graphics Options menu.
*Ati Rage 128x2(Ex. Ati Rage Fury Maxx) - Works ok.
*Ati Rage 128 - Works ok.  
*Ati Rage pro, 2c, and earlier - Card manufacturer no longer supports these video cards.
*S3 Savage 4 - Works ok.
*S3 Savage 2000 - Some drivers might have this problem.  On the main menu screen the sun glare is not correct on the water surface.  This may get corrected in a driver update check your manufacturer's website.  Turning off sun flare effect helped on some cards.
*S3 Savage 3D - The ground is a solid brown, lacking texture. In 800 x 600: There is a white line that runs through the top of the in game screen.  This video card is no longer supported by the manufacturer.
*Matrox G400 - The game may have graphical issues and performance loss if Dualhead is enabled.  We recommend that you disable Dualhead before playing Giants.
*Matrox G200 - On some machines, bitmap screens and some ground textures were not displaying properly.  This may get corrected on a video card driver or game update.
*i810 - Some minor graphics issues check Intel's website for updates.  Some of these problems can be fixed by using the "-nofog" command line switch.
*i740 - Game error screen DXerr88760028 after launching.  This card is not supported.
*Permidia2 - The lens flare effect is in the foreground instead of the background. All in game objects have a greenish hue coloring. Large portions of the sea are textured black.
*Rendition Verite 2x00 - There are missing and corrupt textures with this card. This card is no longer supported by the manufacturer.
*SiS 6326(Ex. Diamond Speedstar A70) - There are black lines through the splash screens.   There is an orange glare all over the screen.  FPS is slow. This card is not supported.
*Number 9 T2R4 - Just after launch the screen comes up brown.  Main menu screen the text is unreadable.  This card is not supported.
*NEC Kyro - works ok.

	5.2 TROUBLESHOOTING COMMAND LINE OPTIONS
	The Giants program supports some command line options that might improve your performance. You should not be using these options if you are not experiencing problems, or do not feel comfortable with command line options. Interplay customer service support will not be provided for command line options, use these at your own risk.   Typically, one sets these options by creating a shortcut to the Giants.exe file and appending the options to the Target line of the shortcut properties.  Example target box:
"C:\Program Files\Giants\Giants.exe" -nofog
	The following options exist:
	-safemode	Run Giants without cpu extensions in low resolution and with no sound. Useful if your graphics or audio options get corrupted, or determining compatibility problems.
	-noprimary  Bypasses the primary video card.  Useful if the user has more than one video card and the first card is incompatible.
	-snd3d 	Use 3D hardware sound. Hardware sound has been disabled in the initial release of Giants due to performance issues. On some systems, this may not be an issue and you may see an improvement in sound quality with this option if your sound card supports EAX.  Go to the "\Giants\EAL" folder of your CD-ROM drive and copy all of the files in this folder to the root of your Giants install folder before running with this command line.
	-amd3dnow	Force use of AMD 3DNow instructions. This should happen automatically if they are available
	-intelsse	Force use of Intel SSE instructions. This should happen automatically if they are available
	-nocpuext	Disable any CPU special instructions. This should only be needed if your CPU has compatibility problems.
	-notnl	Turns off graphics hardware transform and lighting.
	-agptex	Allows use of graphics AGP memory.  Not recommended to try on most systems.
	-lowtex	Reduce texture usage to 4MB.
	-5footclip	For those who prefer the longer range 'Z' precision when playing the game in 16 bit color.  Note this feature comes with the expense of some ugly clipping in first person, and is maybe only an issue with nVidia hardware in 16bit color.
	-equalz	Is for compatibility only and maybe required by some obscure or future video cards.  This setting forces the 'Z' depth to be the same as the color depth.
	-mixalpha This forces an advanced color management change that may benefit some cards that are having problems with alpha blending.  You should not try this switch on cards that support hardware T&L like the Nvidia Geforce family of cards.
	-nofog	This disables fog in Giants, which can be especially useful on Intel's i810 video card.

	5.3 MULTIPLAYER COMMAND LINE OPTIONS
The following multiplayer options are also available for the technically daring.
	-name <playername>		
Specify a multiplayer ID. Example: -name "Basil Johnson"
	-gametype <number>		
Specify a number indicating what type of game to play.
Legal values are 0-5. Example: -gametype 1
	-maxplayers <number>	
Specify maximum players in the multiplayer game. Example: -maxplayers 8
	-host <gamename>		
Start a new game as host, using the given game name.
Example: -host "My Game"
	-join <host IP address>	
Attempt to join the game at the given IP address.
Example: -join 192.168.1.1
	-highbandwidth			
Indicate to send updates much more often. If the host
uses this option, all players must be able to handle
the additional bandwidth.
	-lobby 
Indicate that this game was started via a DirectPlay lobby.
	-nogamespy
Prevents Giants from advertising on the Gamespy master server.  By default, all multiplayer games (except lobby-launched ones like Mplayer) will attempt to contact Gamespy and register on their master server.  Setting this flag will disable that.  This can be helpful when starting a LAN game without an internet connection.  Gamespy will attempt to use the internet and will fail, but this takes a few seconds before timing out.
	-port <port number>
Changes the port number that Giants uses.  The default is 19711 UDP.
Example: -port 4000 

	5.4 IMPROVING PERFORMANCE
	Of course getting a faster cpu, more memory, and a faster video card could drastically improve performance, but for those who don't want to or can't buy new hardware you can try some of these tips.
*	Giants requires the latest drivers for your hardware for optimal performance.  Updating video drivers, sound drivers, operating system, motherboard chipset, and your system's bios significantly improved frame rate on several systems we tested.
*	On some systems updating the AGP chipset controller improved framerate by three or four times.  This was especially true with non-Intel controllers.  To see which controller you have on most systems right click on My Computer and select properties.  Go to the Device Manager tab and open up System Devices.  Look for an entry that mentions AGP.  Most AGP controllers will be listed as Intel, Via, Ali, or Amd.  Go to the appropriate website to find your newest drivers and follow their install instructions.
Via: http://www.viatech.com/drivers/index.htm
Amd: http://www.amd.com/products/cpg/bin/
Ali: http://www.ali.com.tw/eng/support/driver.shtml
Intel:  http://support.intel.com/support/chipsets/driver.htm
Many users with Via motherboard chipsets and Geforce cards have reported increased stability by choosing the NORMAL Via drivers instead of the TURBO ones.  This problem might also be avoided by lowering the AGP multiplier down to 2X from 4X.  
*	Try turning off or lowering your graphic options.  Lowering view distance, model detail, and resolution normally have the greatest improvement on frame rate.
*Defragment your hard drive regularly, and make sure you have plenty of free hard drive space for a swap file.
*Close all other programs before running Giants.

	5.5 KNOWN ISSUES
If you are having problems running Giants the first thing you should do is get the most current drivers for all of the hardware in your system.  Hardware drivers are constantly updated and may correct your problem.  Getting the latest video drivers corrected many problems during testing.
*WS2.32.DLL not found.  This error will appear on original Win95A and Win95B machines that have not upgraded to Winsock2.  You can find information on obtaining this upgrade from Microsoft at "http://www.microsoft.com/Windows95/downloads/contents/WUAdminTools/S_WUNetworkingTools/W95Sockets2/Default.asp".
*A minority of video cards have problems multitasking with Giants.  Multitasking with Giants is not supported. This is a video driver issue.
*Giants uses DiretPlay for multiplayer games.  The current version of DirectPlay has a limitation that requires the host to have a real Internet IP address.  If you host a game on a system whose IP address is masked or changed for internet access, players on the internet will not see your game.  Some firewalls including NAT, and Internet connection sharing will exhibit this problem.  If you want to host a game that people on the internet can see, you will need to use a system on your network with a real internet routable IP address.
*Giants multiplayer games may not run properly if some of the players are running with a proxy on.  If you have a proxy and are having connection problems you should try disabling the proxy, and use an alternate form of connection like LAN play or dial-up.
*On some systems it is possible to get a sound to not stop playing after a sudden transition.  Playing the same sound that is looping usually corrects the problem as does restarting the program.

	5.6 HELP REFERENCES
Giants uses Microsoft's DirectX products to generate sound and graphics. These products are constantly evolving and hardware manufacturers are constantly releasing new drivers to support all the features that today's games require.  You therefore need to make sure you have the latest drivers installed on you system for your graphics card, your sound card, and in some cases even your CPU motherboard.  Updating these drivers showed huge performance increases on some systems.  To assist you in this effort, the following is a list of websites which may be useful in finding the latest drivers or troubleshooting and understanding this technology.  This list is by no means complete and is just for reference, any information obtained here has no connection with Interplay Entertainment Corp. or Planet Moon Studios.

Graphics card driver locations
http://www.3dfxgamers.com/drivers/latest_drivers2.stm
http://www.nvidia.com/products.nsf/htmlmedia/detonator3.html
http://www.matrox.com/mga/support/drivers/home.cfm
http://support.ati.com/drivers/index.html
http://www.s3.com/default.asp?menu=support&submenu=drivers

Sound Card driver locations
http://www.creative.com/support/files/download.asp

Trouble Shooting for Advanced Users
http://www.geforcefaq.com
http://support.microsoft.com/support/kb/articles/Q261/6/06.asp
http://support.microsoft.com/support/kb/articles/Q270/7/15.ASP
http://www.tomshardware.com/mainboard/00q2/000417/kx133-04.html
http://www.reactorcritical.com/

Information on system motherboards and updates - advanced
http://support.intel.com/support/chipsets/driver.htm
http://www.viatech.com/drivers/index.htm

5.7 IKERNEL.EXE INSTALL ERROR
	This is a rare problem that happens on some systems while using Installshield.  Most of the time this problem can be corrected either by rebooting the machine and/or deleting the files in your Windows temp directory and trying the install again.  Written below is an excerpt from the makers of installshield's support site regarding this problem and a few possible solutions.  This article and other Installshield support information can be found on their website at
http://support.installshield.com/default.asp

Setup initialization errors can be caused by a number of factors. This is a non-exhaustive list of possible resolutions:
1) Insufficient permissions on the machine. If you are using a Windows NT or a Windows 2000 machine, you need to have administrative permissions to run an InstallShield Professional 6.x setup. Make sure you have the correct permissions. 
2) If you just ran an InstallShield setup, the engine takes a few seconds at the end of the installation to clean up. During this time Ikernel.exe (the engine file) is running in memory from a previous process; that is why you are not allowed to launch another setup. Waiting a few seconds and running the setup again should resolve this. 
3) Check and make sure Ikernel.exe is not in memory; if it is, and no setup is running at the time, end that task. 
4) Clean the temp directory. 
Delete the Program Files\Common Files\InstallShield\Engine folder and then rerun the setup. 
5) Reinstalling IE 5.x can also repair a number of corrupted/missing core windows files from your machine, so reinstalliing IE 5.x and the NT service pack is also suggested. 
6) Another possibility is that you do not have sufficient COM permissions. For information on how to troubleshoot this see article Q104986, INFO: Initialization Error Troubleshooting. 
7) The other potential cause is a missing Stdole32.tlb file. This is a core Windows file and should exist on your machine. Make sure that you if you get this file from another machine, the machine is running the same operating system as the target machine.

========================================================
6.0 INTERPLAY CUSTOMER SERVICE INFORMATION
TROUBLESHOOTING DOCUMENTS ONLINE!
Interplay Productions Technical Support now offers troubleshooting guides with complete installation and setup instructions as well as information that will help you overcome the most common difficulties.  If you have access to the World Wide Web, you can find these at 
http://www.interplay.com/support/
Here you will find troubleshooting information on as well as information on regular system maintenance and performance.
 DirectX 				 http://www.interplay.com/support/directx/
 Joysticks				 http://www.interplay.com/support/joystick/
 Modems and Networks		 	 http://www.interplay.com/support/modem/
(For game-specific information and additional troubleshooting, visit our main page at
http://www.interplay.com)

If you have questions about the program, our Technical Support Department can help. Our web site contains up-to-date information on the most common difficulties with our products, and this information is the same as that used by our product support technicians. We keep the product support pages updated on a regular basis, so please check here first for no-wait solutions:
http://www.interplay.com/support/
If you are unable to find the information you need on our web site, please feel free to contact Technical Support via e-mail, phone, fax, or letter.  Please be sure to include the following information in your e-mail message, fax, or letter:
* 	Title of Game
* 	Computer manufacturer
* 	Operating system (Windows 95, DOS 6.22, etc.)
*	CPU type and speed in MHz
*	Amount of RAM
*	Sound card type and settings (address, IRQ, DMA)
*	Video card
*	CD-ROM
*	Mouse driver and version
*	Joystick and game card (if any)
*	A copy of the CONFIG.SYS and AUTOEXEC.BAT files from your hard drive
*	A description of the problem you're having
If you need to talk to someone immediately, call us at (949) 553-6678 Monday through Thursday between 8:00AM-5:45PM and Friday between 9:00AM-4:45PM, Pacific Standard Time with 24 hours, 7 days a week support available through the use of our 
automated wizard.   Please have the above information ready when you call. This will help us answer your question in the shortest possible time. When you call you will initially be connected with our automated wizard.  For information pertaining to your specific title, press "1" on the main menu and listen carefully to all prompts.  All titles are listed alphabetically.  After you have selected your title, the most common difficulties will be listed.  If the difficulty you are having is not listed or you need additional assistance, you may press "0" on your games main menu, and you will be transferred to a Technical Support Representative.  No hints or codes are available from this line.  

Interplay Productions Support Fax: (949) 252-2820
Interplay Productions Technical Support
16815 Von Karman Avenue
Irvine, CA  92606
HOW TO REACH US ONLINE
INTERNET E-MAIL: support@interplay.com
WORLD WIDE WEB: Web Site at http://www.interplay.com
FTP: ftp.interplay.com

========================================================
7.0  LEGAL INFORMATION

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
Giants Citizen Kabuto: Copyright 2000 by Planet Moon Studios.  All Rights Reserved.  Planet Moon and the Planet Moon logo are trademarks of Planet Moon Studios.  Giants, Giants: Citizen Kabuto, Interplay, the Interplay logo, "By Gamers For Gamers", Digital Mayhem and the Digital Mayhem logo are trademarks of Interplay Entertainment Corp.  All Rights Reserved.  Exclusively licensed and distributed by Interplay Entertainment Corp.  All other copyrights and trademarks are the property of their respective owners.
========================================================

< End of File>


