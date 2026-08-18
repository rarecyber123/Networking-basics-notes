
# 1. Default Gateway

- ### Role :

  Local network ke devices (hosts) ko doosre external networks ya internet ke saath communicate karne ke liye router ki zaroorat hoti hai. Router ke is interface IP address ko Default Gateway kehte hain.

- ### IP Configuration :

   Default Gateway address host par static (manually) set kiya ja sakta hai ya DHCP ke zariya dynamically milta hai.

- ### Impact :

  Agar Default Gateway galat configure ho, toh host local network (LAN) me communication kar sakta hai, lekin external/remote networks par connectivity nahi hogi.

  ---

 # 2. Network Boundaries & DHCP

- ### Home Wireless Router :

  Yeh local devices ke liye DHCP Server ki tarah kaam karta hai aur unhe Private IP addresses assign karta hai.

- ### ISP Connection :

   Connectivity ke waqt router ISP se ek public (internet-routable) IP address lene ke liye DHCP Client ki tarah kaam karta hai.

- Router local internal network aur public internet ke beech boundary ka kaam karta hai.

---

# 3. Network Address Translation (NAT)

- ### Purpose : 

> Private IP addresses ko Public (internet-routable) IP address me translate karna.

   Isse ek bada group (poora LAN) sirf ek ya kuch public IP addresses share karke internet access kar sakta hai, jisse IPv4 addresses save hote hain.

---

# 4. Essential Settings for Internet Access:

> PC ko Internet se connect hone ke liye teen cheezein chahiye hoti hain:

- IP Address

- Subnet Mask

- Default Gateway Address
