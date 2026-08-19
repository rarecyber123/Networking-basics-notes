
# Quick Explaination

> Jab data ko apne local network se bahar kisi doosre network par bhejna ho, toh router faisla karta hai ke use kis raste par bheja jaye. Yeh faisla karne ke liye router Routing Table ka istemal karta hai.

# Routing Table 

Routing table router ke andar ek address book ya map ki tarah hoti hai, jis mein alag alag networks tak pahunchne ke raste (routes) likhe hote hain.

- ### Layer 3 Decision:

  Switch MAC address dekh kar kaam karta hai, jabke Router destination IP address dekh kar routing table mein match dhoondta hai.

- ### Default Gateway:

   Agar local network ka device kisi aisi IP par data bhejna chahta hai jo local nahi hai, toh wo data sabse pehle apne Default Gateway (router) ko bhejta hai.

  ---

# Information in Routing Table 

Router apne table mein har route ke sath kuch zaroori cheezein store karta hai:

- ### Destination Network:

   Wo network jahan data ko pahunchana hai (e.g., 192.168.2.0/24).

- ### ext-Hop / Gateway:

     Agla router ya IP address jahan packet ko aage forward karna hai.

- ### Outgoing Interface:

   Router ka wo apna port (e.g., GigabitEthernet0/0/0) jahan se packet bahar nikle ga.

- ### Metric:

 Raste ki cost ya doori. Agar ek hi destination ke do raste hon, toh kam metric wala best route select hota hai.

 ---

# Routes Kaise Add Hote Hain?

- ### Directly Connected Networks:

   Jo networks router ke apne ports se seedhe connected hote hain, unka route khud-ba-khud table mein aa jata hai.

- ### Static Routes:

  Yeh raste Network Administrator khud manually router mein type karke add karta hai.

- ### Dynamic Routing Protocols:

   Routers aapas mein baat karke (OSPF, EIGRP wagerah ke zariye) raste khud seekhte hain aur table ko automatically update karte hain.

---
