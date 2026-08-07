
# Purpose of an IPv4 Address

An **IPv4 address** is a logical network address assigned to a network interface connection (NIC) of a host. It uniquely identifies a device on a network to facilitate both local and remote communication.

---

1. **Logical Identification**
   
   - Serves as a unique identifier for host devices (computers, servers, IP phones, printers with integrated NICs).
     
   - Functions similarly to a postal addressing system:
     
     - **Network Portion:** Analogous to the city/postal code.
       
     - **Host Portion:** Analogous to the street address/house number.
       

3. **Scope of Uniqueness**
   
   - **Local Communication:** Must be unique within the Local Area Network (LAN).
     
   - **Remote Communication:** Public IP addresses must be globally unique across the internet.

3. **Packet Header Requirement**
   
   - Every IPv4 packet transmitted across a network contains a **Source IPv4 Address** and a **Destination IPv4 Address**.
     
   - Ensures data reaches its intended recipient and allows destination devices to reply back.

---

## Important Terms & Definitions

* **Logical Address:**

  A software-assigned address (IPv4/IPv6) that can change based on network location, unlike a physical MAC address burned into hardware.

* **Host:**

   Any end device connected to a network that receives or transmits traffic (e.g., PC, Server, Printer, IP Phone).

* **Network Interface Card (NIC):**

   The physical hardware component on a device that connects it to the network and holds the IP address configuration.

* **Source IPv4 Address:**

   The IP address of the device originating the data packet.

* **Destination IPv4 Address:**

  The target IP address where the packet is intended to be delivered.
