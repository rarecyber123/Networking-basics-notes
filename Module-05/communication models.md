
# 1. TCP/IP Model Layers

- ### Application Layer:
  User ko data represent karta hai, sath hi encoding aur dialog control handle karta hai.

- ### Transport Layer: 
  Diversified networks ke mehmaan devices ke darmiyan continuous communication ko support karta hai.

- ### Internet Layer:
  Network ke zariye data bhejne ke liye behtareen raasta (path/routing) determine karta hai.

- ### Network Access Layer: 
  Un hardware devices aur media ko control karta hai jo network banate hain (e.g., Physical + Data Link functions).

  ---

# 2. Model Types (Data Models)

- ### Protocol Model:
   Aisa model jo kisi specific protocol suite ke structure se closely match karta hai (e.g., TCP/IP Model).

- ### Reference Model:
   Aisa model jo kisi layer par hone wale functions ko describe karta hai lekin yeh nahi batata ki wo function kaise execute hoga (e.g., OSI Model).

   ---

# 3. OSI Reference Model Layers (Layer 1 to Layer 7)

### Layer 1 - Physical
> Physical connections (electrical, mechanical signals, bits) ko activate, maintain aur deactivate karta hai.

### Layer 2 - Data Link
> Common media par devices ke darmiyan data frames exchange karne ke tareeqe define karta hai.

### Layer 3 - Network
> End devices ke darmiyan individual data pieces (packets) ko exchange karne aur routing ke liye services deta hai (e.g., IP).

### Layer 4 - Transport
> Individual communications ke data ko segment, transfer aur reassemble karta hai (e.g., TCP).

### Layer 5 - Session: 
> Dialog organize karta hai aur data exchange manage karta hai.

### Layer 6 - Presentation
> Application layer services ke darmiyan transferred data ka common representation/formatting provide karta hai.
