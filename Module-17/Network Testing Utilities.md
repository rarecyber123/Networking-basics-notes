
# 1. Quick Utilities Overview

- ipconfig: System ki current IP configuration details display karta hai.

- ping: Connectivity test karta hai ke distant/remote IP host reachable hai ya nahi.

- netstat: PC par filhal active network connections display karta hai.

- tracert: Destination tak jane wale poore path (route/hops) ko trace karke show karta hai.

- nslookup: Domain Name System (DNS) server ko directly query karta hai domain name resolution check karne ke liye.

  ---

# 2. Troubleshooting Highlights

## Basic vs Detailed IP Config:

- ipconfig: Standard IP address, Subnet Mask, aur Default Gateway batata hai.

- ipconfig /all: Advanced details jaise MAC Address, DNS Servers, DHCP Server address, aur Lease timing batata hai.

## DHCP Renewal Process:

- ipconfig /release: Current DHCP IP binding ko release kar deta hai.

- ipconfig /renew: DHCP server se nayi IP details request karta hai (incorrect/outdated IP issue solve karne ke liye).

##  Ping Mechanism:

- Echo Request packet destination par bhejta hai. Agar host reachable ho to wo Echo Reply return karta hai.

- Default Gateway Ping: Is se ye verify hota hai ke host apne local network se bahar doosre networks ke hosts tak pohanchne ki capability rakhta hai ya nahi.
