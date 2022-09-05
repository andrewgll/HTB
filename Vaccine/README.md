# Vaccine write up

1. Connect to vpn with command
	```
	sudo openvpn {vpnfile}
	```
2. Spawn machine
3. Make base nmap scan
	```
	nmap -sC -sV {targetIP}
	```
4. Checking nmap scan results in (Vaccine/scan_results.txt)[scan_result.txt]
5. Here we see that 21 (FTP), 22(SSH), 80(HTTP) are open.	
