Brief Netplay Tutorial 

1) Place N64 Roms inside of the Roms folder and Run Auto-Setup reg file, or go to File, Choose rom directory, and choose your rom folder location.

2) If the roms do not automatically load, go to File, Refresh Rom List (or press F5). This is so you can use the roms over kaillera.

3) Go to File, Start Netplay, then enter a username, find a server and connect.

4) Right-Click the game list or click the "CRT" or "Create" button if it appears.

5) To enable Gameshark cheats go to System, Gameshark Codes, then Enable the cheats you want.
	Note: You may want to Disable then Re-enable cheat codes to make sure they are sent to the other player.
		(for the most part the cheats should be saved in cache and sent without manual uncheck/checking)

______________________________________


Project64k can only sync a few games over Kaillera (Currently Emulinker X v2.x)

Known games to sync over Emulinker X 2.x servers are

~ SSB64 (Super Smash Bros 64, all versions work, Japanese version has Graphics issues with Jabo Direct3D6 and 7, Random stage causes DS)
~ Mario Kart 64 (Core emulation bug, 3-4 players cause inproper game speeds)
~ Star Fox 64 (Works fine with stable connections, desyncs with lag)
~ Super Mario 64 Multiplayer (Any Rom Hack made multiplayer will probably be better with Mupen64k since it supports saving game data used online)
Few other games work in sync over Kaillera with PJ64K 1.4. 

Every other game such as Mario Party, Cronker's Bad Fur Day, Goldeneye 007 will desync over Kaillera with PJ64k so you will need to use Mupen64K(renamed Mupen64++).

Download - www.Mupen64k.blogspot.com

______________________________________

			General Problems / Issues 
		
	`		       Graphics
*
Problem: Black Screen, Sound works (Resolution problem with Jabo Direct3D8)
	Solution: Go to Graphics unCheck "hide advance settings",  go to "Rom Settings" tab, DELETE the Width and Height number which should be 0.
		Solution 2: Open Project64.rdb in the Main Folder with text editor, then add the Rom information if it is not there, and you haven't tried the first solution.

				[CRC1-CRC2-C:45]
				Clear Frame=0
				Resolution Width=-1
				Resolution Height=-1

The top line is the CRC Information, you can get this by emulating the rom then File - Rom Info. It is the CRC1 and CRC2 information.

**
Problem: Screen Freeze (Jabo Direct3D8 issue with Windows Vista/7/8)
	Solution: Do not drag/put windows over Emulation. 
		Solution 2: Use Glide64 Finale Version (Resource heavy) 

***
Problem: Broken Sound / Lost Audio while emulating
	Solution: Use Azimer's Audio v0.30 (Old Driver)

****
Problem: Cannot close Project64k and cannot reopen Netplay / cannot connect to Kaillera Server (Ownaclient problem)
	Solution: Task Manager, Close Project64k. Or run Force Close PJ64k.bat

*****
Problem: Super Mario 64 Multiplayer White Screen / Frozen 
	Solution: Reset PJ64k

****** 
Problem: Error, "current controller dll could not be used please select another one"
	Solution: Run ~Force Close PJ64k~.bar  or Task manager, Close Project64k