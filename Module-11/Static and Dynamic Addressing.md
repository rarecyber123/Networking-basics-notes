
# 1. IP Address Assignment

### Kisi bhi device ko network par communicate karne ke liye IP address ki zaroorat hoti hai.
### Yeh address do tarah se assign kiya jata hai:

# Static IP Addressing (Manual):

- **Admin** khud har device par ja kar IP address, subnet mask, default gateway, aur DNS set karta hai.

- **Uses** : Servers, Printers, Routers, aur Network Switches ke liye (kyunki inka IP address kabhi badalna nahi chahiye).

- **Pros**: IP fix rehta hai, hamesha accessible hota hai.

- **Cons:** Har device par manually set karna mushkil aur time-consuming hai; human error (IP duplication) ka chance hota hai.

# Dynamic IP Addressing (Automatic):

- **Network** khud automated tarike se devices ko IP address deta hai using DHCP (Dynamic Host Configuration Protocol).

- **Uses** End-user devices jaise Laptops, Smartphones, PCs, aur Smart TVs ke liye.

- **Pros:** Plug-and-play convenience, koi manual effort nahi, IP conflict ka issue nahi hota.

- **Cons:** Device reconnect hone par IP address badal sakta hai.

  ---
  
# 2. DHCP (Dynamic Host Configuration Protocol)

 ###  Jab bhi aapka laptop ya mobile Wi-Fi se connect hota hai, woh DHCP server se IP address mangta hai.
 ### Is poore process ko DORA bolte hain:
 
- **D - Discover:** Device network par broadcast message bhejta hai: "Kya yahan koi DHCP server hai? Mujhe IP chahiye!"

- **O - Offer:** DHCP server reply karta hai: "Haan main hoon! Yeh lo ek IP address jo tum use kar sakte ho."

- **R - Request:** Device server ko bolta hai: "Teek hai, main yeh offered IP address accept kar raha hoon."

- **A - Acknowledge:** Server confirm karta hai: "Done! Yeh IP address ab tumhara hua (for a specific lease time)."

  ---
  
