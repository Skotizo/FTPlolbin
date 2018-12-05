========================================================================================================
Cmd.exe and powershell.exe are commonly not directly callable on hardened PC's.
 
This batch file uses ftp.exe to make execute commands commonly made by powershell.exe/cmd.exe

The ! symbol is required before each command 

You can add multiple commands to the input.txt file by seperating each command by a line.

This research was found via https://twitter.com/0xAmit/status/1070063130636640256


********************************
The Bypass.bat file calls      *
	>ftp.exe -s:input.txt  *
********************************

========================================================================================================

