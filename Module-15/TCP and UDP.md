
 # Transport Layer Protocols: TCP vs. UDP

### Transport Layer ka Role: 

> Yeh ensure karta hai ke data application level par sahi tarike se transfer ho. Is layer par do main protocols kaam karte hain: TCP aur UDP.

---

# 1. Transmission Control Protocol (TCP)

- ### Reliable Communication:

   TCP ek reliable protocol hai. Yeh guarantee deta hai ke saara data safely aur bina kisi loss ke destination tak pahuche.

- ### Tracking & Acknowledgments:

  Yeh har bheje gaye segment ka track rakhta hai. Agar koi segment raste mein miss ho jaye, toh destination confirmation (acknowledgment) nahi bhejti aur TCP us missing packet ko retransmit (dobara send) kar deta hai.

- ###  Connection-Oriented:

  Data bhejney se pehle sender aur receiver ke beech connection establish hota hai.

- ### Use Cases:

   Jahan accuracy critical ho, jaise Web Browsing (HTTP/HTTPS), File Transfer (FTP), aur Email (SMTP).

  ---

  # 2. User Datagram Protocol (UDP)

- ### Fast & Lightweight:

   UDP ek unreliable / connectionless protocol hai, lekin yeh TCP se bohot fast hota hai.

- ### No Tracking:

   Yeh acknowledgments use nahi karta aur na hi missing segments ko dobara bhejta hai ("Best-effort delivery").

- ### Low Overhead:

  Isme extra checking ka overhead nahi hota, isliye speed aur real-time delivery prioritize hoti hai.

- ### Use Cases:

 Jahan speed zyada zaroori ho aur thoda data loss chal jaye, jaise Live Video Streaming, Online Gaming, aur Voice Calls (VoIP).

 ---
