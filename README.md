# Dump-Clear-Text-Password-after-KB2871997-installed

Auto start Wdigest Auth,Lock Screen,Detect User Logon and get clear password.

Base on:

https://github.com/PowerShellMafia/PowerSploit/blob/master/Exfiltration/Invoke-Mimikatz.ps1

Author: 3gstudent

##Usage:

PowerShell.exe -ExecutionPolicy Bypass -File dump.ps1

##Update:

###Add the following Function:

- Set the regedit value to 1 and start Wdigest Auth
- Auto Lock Screen
- Auto Detect User Logon
- Auto Get clear-text password and save
