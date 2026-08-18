
# Broadcast Domain & Traffic:

- Jab koi host Broadcast message bhejta hai, toh Switches us message ko network ke saare devices tak aage forward kar dete hain. Is poore local network ko Broadcast Domain kehte hain.

 - Network bada hone par Broadcast Traffic zyada ho jata hai, jisse performance slow ho sakti hai. Is traffic ko control/contain karne ke liye Routers ka use karke ek bade network ko chote Broadcast Domains mein divide kiya jata hai.

   ---

# Broadcast MAC Address:

- Ethernet mein Broadcast MAC address FFFF.FFFF.FFFF (48 Fs ya 48 ones in binary) hota hai. Network par moujood har device ki NIC is address vale frame ko accept aur process karti hai.

---

# ARP (Address Resolution Protocol) ka Concept:

- Jab local host ko kisi doosre host ka IP address pata ho lekin MAC address na pata ho, toh woh target host ka MAC pata karne ke liye ARP Request bhejta hai.

 - ARP Request ek Broadcast hoti hai, jo local domain ke sabhi devices tak pahunchti hai.

- Jis device ka IP match karta hai, woh wapas ek ARP Reply (Unicast) bhejta hai jismein uska MAC Address hota hai.

  ---

# ARP Table:

- MAC Address milne ke baad sender host us IP-to-MAC mapping ko apni ARP Table mein store kar leta hai taaki aage bar-bar broadcast na karni pade aur direct communication ho sake.

  ---
