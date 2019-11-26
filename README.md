# mytermux
1. Install Termux from Playstore.
2. `touch .hushlogin`
3. `apt update && apt upgrade`
4. `apt install nodejs git nano wget`
5. `cd ../usr/bin && nano c`
```
#!/data/data/com.termux/files/usr/bin/sh
clear
```
6. `nano ftpd`
```
#!/data/data/com.termux/files/usr/bin/sh
tcpsvd -vE 0.0.0.0 1024 ftpd -w /
```

