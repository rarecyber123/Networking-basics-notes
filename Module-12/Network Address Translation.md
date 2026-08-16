
# 1. NAT Ka Primary Purpose (Purpose of NAT)

- ### IP Address Translation:

  NAT ek aisa process hai jo private IPv4 addresses ko public IPv4 addresses mein translate karta hai, aur inverse translation bhi karta hai.

- ### IPv4 Preservation:

   Duniya mein IPv4 addresses ki kami ko door karne aur private networks ko secure rakhne ke liye NAT ka istemal hota hai.

---

# 2. Private vs. Public Addresses

- ### Private IPv4 Addresses:

  Local LAN ke andar laptops, phones, aur PCs ko assign kiye jaate hain (e.g., 192.168.x.x, 10.x.x.x). Yeh internet par Directly Routable nahi hote.

- ### Public IPv4 Addresses:

   Internet Service Provider (ISP) router ke external interface ko allocate karta hai. Yeh globally internet par uniquely identify hote hain.

  ---

  # 3. How NAT Works

 - ### Outbound Traffic (Internal to External):

   Jab koi local PC internet par request bhejta hai, to wireless router us ke Private Source IP ko mita kar apna Public IP address laga deta hai.

- ### NAT Table:

  Router ek NAT Translation Table maintain karta hai, jismein har local PC ka Request Connection, Internal IP Address, Port Number aur External Public IP mapped rehte hain.

- ### Inbound Traffic (External to Internal):

   Jab internet se response wapas aata hai, to router NAT table check karta hai aur us packet ko sahi local PC ke private IP address par forward kar deta hai.

  ---
  
# 4. Benefits of NAT

- ### Security:

   Internal network ke private IPs internet par direct reveal nahi hote, jisse internal hosts direct cyber attacks se bache rehte hain.

- ### Cost Effective:

  Ek single Public IP ka istemal karke hazaron internal devices internet access kar sakti hain.
