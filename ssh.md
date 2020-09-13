# ssh
Secure Shell (ssh) uses encryption to make a secure connection between a client and a server for remote command execution
#### ssh on Windows
- can use powershell (windows 10) or PuTTY
#### ssh for cpanel
- in cpanel search for "manage shell" and check "enable ssh" is on
- this will present details for
  - `server IP:`- example: 12.12.123.12
  - `username` - example: user123
  - `ssh port` - example: 12345
- open powershell type `ssh` and enter to check "openssh" is installed on windows machine
- to login remotely type
  - `ssh user123@example.com -p12345` (powershell may prompt you to confirm you want connection - type `yes`)
  - enter cpanel password on the next prompt
- powershell directory should change from local to server - example `PS C:\Users\computername>` to `user123@server123 ~]$`
  - type `ls` to see local folders, this should display your cpanel root directory contents
  
**References**\
https://www.youtube.com/watch?v=FXbqO61_NVc

#### let's encrypt SSL certificates

  



#### commands
`exit` quits ssh session
