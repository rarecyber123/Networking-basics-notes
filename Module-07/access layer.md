
# Ethernet Switches

### Role in Access Layer:

Ethernet switches act as the primary connection point for end devices (computers, printers, IP phones) in a Local Area Network (LAN).

### Forwarding Decision:

Switches make forwarding decisions using the Destination MAC Address found in the header of an incoming Ethernet frame.

---

# MAC Address Tables 

### Learning Process (Source MAC):

When a frame enters a switch port, the switch looks at the Source MAC Address. It records this address along with the port number in its MAC address table (also called CAM table).

### Forwarding Process (Destination MAC):

 - Known MAC: If the Destination MAC address is already in the table, the switch forwards the frame directly out of the specific port assigned to that MAC address (Unicast).
   
 - Unknown MAC: If the Destination MAC address is not in the table, the switch performs Flooding—it forwards the frame out all ports except the port where the frame arrived.

   ---
# Access Layer Devices 

| *Switches* | *Hubs* |
|---|---|
| Ethernet Switches: Modern standard. They isolate collision domains per port and forward traffic intelligently based on MAC addresses.| Ethernet Hubs: Considered obsolete. They simply repeat incoming signals out all other ports without reading MAC addresses, causing frequent network collisions.|
   
---

# Key Vocabulary

**Access Layer**: 
   
    LAN topology ka wo layer jo end-user devices ko network se connect karta hai.

**MAC Address Table (CAM Table)**:
    
    Switch ki internal memory jahan Port Numbers aur unse jude Devices ke MAC Addresses ka record hota hai.                

**Destination MAC Address**: 

    Ethernet frame ka wo field jisko read karke switch frame ko agey pathanta (forward) karta ha

**Source MAC Address**:

    Ethernet frame ka wo field jisko read karke switch apni MAC table mein nayi entries add karta hai.

 **Flooding:**5
    
    Unicast frame ko tamam ports par bhejna jab destination MAC address table mein maujood na ho.
