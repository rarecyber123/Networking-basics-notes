
# Dono Addresses ka Dynamic Pair:

- ### Network communication ke liye MAC Address (Layer 2) aur IP Address (Layer 3) dono mil kar kaam karte hain.

- ## IP Address (Logical):

  Yeh batata hai ki target device poore network ya Internet par kahan located hai (jaise tumhara home address). Yeh network badalne par change ho sakta hai.

 - ## MAC Address (Physical):

   Yeh device ki hardware identity hai jo NIC par burned-in hoti hai (jaise tumhara Biometric ID / CNIC). Yeh hamesha same rehta hai chahe device kisi bhi network se jude.

---

# Local Network Par Delivery:

- Jab data same local network (LAN) ke kisi device tak pahunchana hota hai, toh actual delivery ke liye destination ka MAC Address zaroori hota hai.

- IP Address packet ko sahi destination network tak lata hai, lekin local physical medium par packet bhejney ke liye Layer 2 Frame mein destination MAC address attach karna padta hai.

---

# Destination Beyond Local Network (Remote Traffic):

- Agar target device local network se bahar ho (jaise Internet par), toh Ethernet frame ka Destination MAC Address target device ka nahi, balki tumhare Default Gateway (Router) ka hota hai.

 - Packet ka Destination IP Address target host ka hi rehta hai, lekin local network se nikalne ke liye frame Router ke MAC Address par bheja jata hai.
