Mountfix Installer For Obsidian Conflict: (rev 3/5/2025)

Original manual workaround solution discovered by raidensnake (OC Beta) & Neico (OC Dev)

Original LUA Mountfix by Neico (OC Dev)

Improved C# version Coded by mrchemist (OC Beta)
Uses .NET Framework 4.8
Uses HLlib 2.4.5 by Nemesis (Ryan Gregg)
Uses SteamCMD by Valve Corporation
Uses SourceMod/MetaMod Source by AlliedModders LLC
Uses Obsidian Conflict Sourcemod Extensions by The Obsidian Conflict Development Team
Base Server Config based On the XenoAisam OC Anime Server by raidensnake & The Obsidian Conflict Development Team
Digitally Codesigned by raidensnake (OC Beta)

Lead Testing & Debugging:
raidensnake (OC Beta)
mrchemist (OC Beta)

Testers:
Shana (OC Dev Leader)
Maestra F�nix (OC Dev)

Special Thanks:
Neico (OC Dev)
Shana (OC Dev Leader)
Tesla-X4 (Former OC Dev)
Nemesis (Ryan Gregg)
Valve Corporation
AlliedModders LLC
Obsidian Conflict Development Team
Obsidian Conflict Community

Steam CMD & Source Engine �Valve Corporation http://www.valvesoftware.com
Obsidian Conflict �Obsidian Conflict Development Team http://www.obsidianconflict.net
Mount fix �mrchemist http://www.jfmhero.me & Raidensnake's Den Website Network (RSDNTWK) http://www.raidensnakesden.net
SourceMod & Metamod Source �AlliedModders LLC http://www.alliedmods.net/
HLLib �Nemisis (Ryan Gregg) http://nemesis.thewavelength.net/

Confirmed Tested Client OS: (As of 23/4/2025)

Windows 10 32/64-bit All Editions
Windows 11 64-bit All Editions

Confirmed Tested Server OS: (As of 23/4/2025)

Windows Server 2016 64-Bit All Editions
Windows Server 2019 64-Bit All Editions
Windows Server 2022 64-Bit All Editions
Windows Server 2025 64-bit All Editions

Requirements:
.NET framework 4.8
https://dotnet.microsoft.com/en-us/download/dotnet-framework/thank-you/net48-offline-installer

Features:
Client & Server-side mount fixing
Supports Server-side steamauth authorisation
Client-side mount loading by writing blank files into the obsidian/mounts folder
Server-side mount download & installation
Server-side folder clean-up
Command-Line options for Installer Integration

Usage:

Double Clicking Method:

Client side:
when prompted type client and press enter, the mountfix will run the process automatically.

Server side:
When prompted type server and press enter
a dialogue will ask for the installation location.
Enter the location including the obsidian folder in the path using quotes " and press enter. eg. "c:\obsidian conflict\obsidian"
Please Note: The obsidian folder will not be touched only the path that leads to it will be used for the mounts eg. "c:\obsidian conflict" during the installation process.
A new window will appear asking for a valid steam username and password. To proceed enter your steam username and password and click install server. The mountfix will begin the process.

PRIVACY & DATA PROTECTION LEGAL DISCLAIMER: 
The steam username and password that is requested by the mountfix is only ever used for the login to Official Valve SteamCMD background commands and is never logged or stored in any way shape or form.
The login details entered are automatically purged when the mountfix has completed the SteamCMD downloading tasks.
We respect people's privacy and data protection.

Please Note: Even if people don't have mounts both client and server side the mountfix will simply ignore those mounts with the exception of source sdk base 2007 which IS required.


Command Line Method:

Please Note: These commands can also be used for installer integration.

The usage commands are available by typing the command -help and pressing enter

Client side:

to run the mount fix use cmd to point to the obsidian folder and type mountfix.exe -client

Example:

cd "c:\program files (x86)\steam\steamapps\sourcemod\obsidian"

mountfix.exe -client

Just like the double click method the process will be automated

Server side:

To run the server side commands, use the following syntax on cmd -server "<steammountfolder\obsidian>" steamusername steampassword

Example:

cd c:\mountfix

mountfix.exe -server "c:\obsidian conflict\obsidian" steamusername steampassword

Pease Note: As stated before even if the mounts part isn't entered and people don't have some mounts the mountfix will ignore them if they are not found.

Just like before in the earlier disclaimer. The login details used are only used for SteamCMD commands and are never logged or stored in any way shape or form.