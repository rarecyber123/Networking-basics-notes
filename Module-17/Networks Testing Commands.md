
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

# 3. The ping Command

> Subse zyada use hone wala utility tool. Ye ICMP Echo Request bhejta hai; agar target host sahi kaam kar raha hai, to wo ICMP Echo Reply wapas bhejta hai.

- IP Ping (ping 10.10.10.1): Direct host ya gateway ki reachability check karta hai.

- Domain Ping (ping [www.cisco.com](https://www.cisco.com)): Pahle DNS server se domain ko IP mai convert karwata hai, fir ping bhejta hai.

- Note: Agar IP se ping kaam kare par domain name se fail ho jaye, to issue DNS Server mai hota hai.

  ---
  
# 4. Ping Results analyze

## Ping Fail Hone Ke Cases:

- Request Timed Out: Network route mai koi blockage hai ya firewall ICMP packets ko block kar rahi hai.

- Ping Default Gateway Fail: Problem local network / router ki side par hai.

- Ping Gateway Success, Par Internet Down: Local network sahi hai, issue ISP ya outer routing mai hai.

 ## Common Ping Parameters:

- -t: Continuous ping bhejta rehta hai (jab tak Ctrl+C press na karein).

- -n count: Specific number of packets bhejne ke liye (e.g., ping -n 10 8.8.8.8).

- -4 / -6: Specifically IPv4 ya IPv6 force karne ke liye.

  ---
