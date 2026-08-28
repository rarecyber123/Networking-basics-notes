
# Network Testing Commands 

> Computer networking mai jab kisi system mai connectivity issue aaye, to command-line utilities ki madad se issue trace kiya jata hai. Subse common OS (Windows, Linux, macOS) mai CLI tools predefined hote hain.

---

# 1. Main Troubleshooting Commands Overiew

- ipconfig: System ki IP address aur network details check karne ke liye.

- ping: Ye check karne ke liye ke target host reachable hai ya nahi.

- netstat: Currently active network connections dekhne ke liye.

- tracert / traceroute: Destination tak jane wale poore raste (hops) ki details check karne ke liye.

- nslookup: Domain Name System (DNS) se IP address resolve karne ke liye.

  ---

 # 2. The ipconfig Command

> Agar kisi host PC ko galat IP mil jaye ya IP na mile, to wo network ya internet se connect nahi ho paaye ga.


### Basic ipconfig:

Is se IP Address, Subnet Mask, aur Default Gateway show hota hai.

### ipconfig /all: 

Pure adapter ki gehri details batata hai—jaise MAC Address, DNS Servers, DHCP enabled hai ya nahi, aur IP Lease timing.

# ipconfig /release:

Current DHCP IP Address binding ko chhor (release kar) deta hai.

### ipconfig /renew:

DHCP Server se naya IP Address Request karta hai. (Boht se network issues bas release/renew karne se solve ho jate hain).

---
