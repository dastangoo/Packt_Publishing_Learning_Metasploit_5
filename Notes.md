```bash
msfconsole
---
hosts -c <col1>,<col2> 
hosts -c <col1>,<col2> -S 
hosts -c <col1>,<col2> -S <keyword> -R
services -c <col1>, <col2>
services -c <col1>, <col2> -S
services -c <col1>, <col2> -S <keyword> -R
db_nmap -O <IP>
search ssh_version
use <num>
show options
services -S ssh -R
run
```
