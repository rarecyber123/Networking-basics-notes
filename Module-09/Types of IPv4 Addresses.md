
# Public and Private IPv4 Addresses


* **Public IPv4 Addresses:**
 
Yeh globally unique hote hain aur internet par direct route ho sakte hain (ISPs inhein handle karte hain).

* **Private IPv4 Addresses:**

Mid-1990s mein jab IP addresses khatam hone lage, tab RFC 1918 ke tehat private addresses banaye gaye. 
Yeh internal local networks (jaise ghar ya office) mein istemal hote hain aur internet par direct routable nahi hote.

---

# RFC 1918 Private Ranges:

- 10.0.0.0/8 ($10.0.0.0$ – $10.255.255.255$)
- 172.16.0.0/12 ($172.16.0.0$ – $172.31.255.255$)
- 192.168.0.0/16 ($192.168.0.0$ – $192.168.255.255$)

  ---

 # Routing to the Internet & NAT
 
Kyunke private IP addresses internet par direct nahi chal sakte, is liye NAT (Network Address Translation) ka istemal hota hai:

    Jab aapke local network ka packet bahar nikalta hai, toh aapka router uske private IP ko ek Public IP mein translate/change kar deta hai.

    Is tarah private IP wale devices bhi internet se communicate kar paate hain.

---

# Special Use IPv4 Addresses 

Kuch IP addresses specific tasks ke liye reserved hote hain:

   - Loopback Addresses ($127.0.0.0/8$): Commonly $127.0.0.1$ istemal hota hai. Yeh device apne hi TCP/IP stack aur internal connection ko test/ping karne ke liye use karta hai.
   
   - Link-Local Addresses ($169.254.0.0/16$): Isko APIPA (Automatic Private IP Addressing) bhi kehte hain. Jab kisi PC ko DHCP server se IP nahi milta, toh Windows client khud ko is range se auto-assign kar leta hai.
