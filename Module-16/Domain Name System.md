
# Domain Name System (DNS) – 

> DNS internet ka "Phonebook" hai. Hum log websites ke naam yaad rakhte hain (jaise cisco.com), lekin computers sirf numbers (IP addresses) samajhte hain (jaise 172.230.155.162). DNS ka kaam naam ko IP address mai convert karna hota hai taake aapki request sahi jagah pahunch sake.

---

# How DNS works : 

- ## DHCP & ISP Connection:

  Jab aap apna device network se connect karte hain, toh aapka router (DHCP ke zariye) aapko ek DNS server ka address deta hai jo aapke ISP (Internet Service Provider) ka hota hai.

 - ## IP Address Ki Talaash:

   Jab aap browser mai koi URL (jaise www.cisco.com) likhte hain, toh sab se pehle aapka device DNS server se puchta hai: "Is website ka IP address kya hai?"

  - ##  Request Bhejna: 
  
  DNS server IP address dhoond kar wapas bhejta hai, aur phir aapka device us IP address par actual HTTP request bhejta hai.

---

# Nslookup Command (DNS Test Karne Ke Liye)

> Agar aap check karna chahte hain ke kisi domain ka IP address kya hai, toh aap terminal ya command prompt par nslookup utility ka istemal kar sakte hain.

## Windows Command Prompt:

C:\> nslookup enter karke aap manual DNS queries shuru kar sakte hain ya direct domain ka naam de kar IP address dekh sakte hain (e.g., nslookup cisco.com).

---

 # Takeaways

## Syntax Checker: NetAcad mai lab practice ke liye Syntax Checker istemal hota hai, jahan aapko exact commands type karni hoti hain.

## Packet Tracer: Yeh ek ziada advanced tool hai jahan aap real equipment ki tarah short commands bhi use kar sakte hain.
