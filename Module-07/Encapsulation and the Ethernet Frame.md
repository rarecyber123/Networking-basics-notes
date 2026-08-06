
# Core Concepts & Sequence

## Ethernet & Accessing the LAN:

- Local Area Network (LAN) me Ethernet sab se widely used networking technology hai.

- Devices network par connect hone ke liye Ethernet Network Interface Card (NIC) ka istemal karti hain.

- Har NIC me ek unique address permanently embedded hota hai jise MAC Address (Media Access Control) kehte hain.

  ---

 ## Encapsulation & De-encapsulation:

**Encapsulation:**

- Ek message/data format ko doosre format ke andar wrap (seal) karne ke amal ko encapsulation kehte hain (jaise ek letter ko envelope ke andar dalna).

- Network par transmit hone se pehle har computer message ko ek specific format me encapsulate kiya jata hai jise Frame kehte hain.

- Frame ek lifafe (envelope) ki tarah kaam karta hai jisme Source aur Destination addresses maujood hote hain.

**De-encapsulation:**

- Jab destination device message receive karke envelope (frame header) ko remove karti hai aur andar ka data parhti hai, use de-encapsulation kehte hain.

  ---

# 2. Important Terms Summary

## Ethernet Frame: 

Data Link Layer ka Protocol Data Unit (PDU) jo data ko header aur trailer ke sath wrap karta hai taakay physical media par transmission ho sake.

## MAC Address:

Physical Address jo NIC card par hard-code (burn) hota hai. Frame ke andar Source aur Destination MAC addresses shamil hote hain.

## OSI Model Layer:

Ethernet protocol OSI model ki Layer 2 (Data Link Layer) par kaam karta hai.

## Preamble & SFD (Start Frame Delimiter):

Ethernet frame ke shuru me lagne wale bits jo receiving device ko frame start hone ki notification/synchronization dete hain.

## FCS (Frame Check Sequence):

Frame ke aakhir me lagne wala error-checking mechanism jo check karta hai ke data corrupt to nahi hua.
