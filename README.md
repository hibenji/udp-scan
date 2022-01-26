# UDP SCAN (useful for public WIFI)
Scan Network for open UDP ports.

Use at your own risk lol. (uwu - blame Mr.Dev#5599)

How to port scan your own VPS to find out which ports are not block by your network.

# Requirements

A VPS
A Linux System (can be WSL)


# How To

For IP put in the Public ip of the computer you are connecting from (the network you want to scan).
```
tcpdump -nnq src host <ip> and not port ssh
```


Here put in the IP of your server.
```
sudo nmap -sU -v <server-ip>
```
