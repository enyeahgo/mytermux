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
Save and `chmod +x c`
<br />6. `nano ftpd`
```
#!/data/data/com.termux/files/usr/bin/sh
tcpsvd -vE 0.0.0.0 1024 ftpd -w /
```
Save and `chmod +x ftpd`
<br />7. If you want to install debian
```
cd ~
hash -r
wget https://raw.githubusercontent.com/sp4rkie/debian-on-termux/master/debian_on_termux.sh
sh debian_on_termux.sh
```
<br />8. If all went well then create your shortcut bash script
`cd  ../usr/bin && nano sd`
```
#!/data/data/com.termux/files/usr/bin/sh
$HOME/bin/enter_deb
```
Save and `chmod +x sd`
<br />9. `sd` then `unset LD_PRELOAD && apt-get update && apt-get upgrade`
<br />10. `apt-get install nodejs`
<br />11. `apt-get install npm`
<br />12. `apt-get install create-react-app`
