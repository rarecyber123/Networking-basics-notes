
### 1.Broadcast Domain:

  - Fast definition: Network ka wo poora area jahan agar ek device broadcast message bheje, toh baaki saare devices ko wo message milta hai.
  - Switches broadcast traffic ko har jagah aage pass (propagate) karte hain.

--

### 2. Large Broadcast Domains ke Masley (Problems)

> Agar ek hi network/LAN me zaroorat se zyada devices (hosts) hon (jaise 400+ users):

1. **Slow Network:** Excess broadcast traffic ki waja se network clogging ho jati hai.
2. **Slow Devices:** Har individual device ko bewaja har broadcast packet process karna padta hai, jisse unki processing slow ho jati hai.

---

### 3. Solution: Subnetting

- **Subnetting:** Barray network/broadcast domain ko chhote networks (subnets) me divide karna.
- **Example (from course):**
  - Original Large Network: `172.16.0.0 /16` (400 users)
  - Subnetted into 2 Networks: 
    - `172.16.0.0 /24` (200 users)
    - `172.16.1.0 /24` (200 users)
- Subnetting se Subnet 1 ka broadcast Subnet 2 tak nahi pohnchega.

---
