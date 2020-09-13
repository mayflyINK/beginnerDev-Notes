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
  - `ssh user123@example.com -p12345` (replace "example.com" with your domain name)
  - powershell may prompt you to confirm you want an remote connection - type `yes`
  - on password prompt - enter cpanel password
- powershell directory should change from local to server - example `PS C:\Users\examplename>` to `user123@server123 ~]$`
  - type `ls` to see local folders, this should display your cpanel root directory contents
  
**References**\
https://www.youtube.com/watch?v=FXbqO61_NVc

#### let's encrypt SSL certificates
Let's Encrypt is a free SSL certificate issuer, requires ACME protocol to issue and install certificates via ssh.
https://letsencrypt.org/getting-started/

acme.sh\
https://github.com/acmesh-official/acme.sh/wiki/Simple-guide-to-add-TLS-cert-to-cpanel
  
certbot\
- instructions for windows coming soon

(old instructions)\
https://www.youtube.com/watch?v=d-FQ0JTfUxI


#### commands
`exit` quits ssh session
