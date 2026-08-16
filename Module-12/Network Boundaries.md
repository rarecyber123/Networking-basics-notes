
# 1. Routers as Gateways

- ### Gateway Ka Role:

  Router ek gateway ka kaam karta hai jo local network ke hosts ko doosre networks ke hosts se communicate karwane mein madad karta hai.

- ### Default Gateway:

    Local network par maujood har host ko doosre networks par traffic bhejne ke liye router ke connected interface ka IPv4 address pata hona chahiye, jise Default Gateway kehte hain.

- ###  Automatic Assignment:

   Jab wireless router DHCP server banta hai, to yeh automatic tarike se local clients ko unka IP, Subnet Mask aur apna internal address as Default Gateway bhej deta hai.

---

# 2. Routers as Boundaries Between Networks

- ### Inside (Internal) Network:

  Wireless router local hosts (wired/wireless) ko private IP addresses assign karta hai. Private IPs ki wajah se internal network directly internet se access nahi ho sakta.

- ### Outside (External) Network:

  ISP router ke internet side (external interface) ko ek public routable IPv4 address assign karta hai. ISP aksar DHCP server ke zariye yeh public IP router ko deta hai (router yahan DHCP client ke taur par kaam karta hai).

- ### Network Boundary:

  Wireless router local private network aur external public internet ke beech boundary (had) ka kaam karta hai.

  ---

 # 3. Key Rules (Same vs. Different Networks)

### Same Network:

-  Subnet Mask aur Default Gateway address Same hota hai.

-  IP addresses aur MAC addresses Different hote hain.
