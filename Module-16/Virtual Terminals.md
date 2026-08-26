
**Virtual Terminals (Telnet aur SSH) remotely kisi device ya computer ko access karne ke liye use hote hain**.

# Virtual Terminals

Pehle ke zamane mai log physical display terminals se central computer se connect hote the. Network aane ke baad remoto access ki zaroorat hui, jiske liye Telnet aur SSH banaye gaye.

---

# Telnet (TCP Port 23)

### Kiya karta hai:

Yeh software ke zariye ek virtual terminal (vty) session banata hai jisse aap door baithe kisi router, switch ya server ka CLI (Command Line Interface) access kar sakte hain.

### Problem (Unsecured):

Telnet bohot purana protocol hai (1970s ka) aur yeh saara data plaintext (plain text) mai bhejta hai. Yani agar koi hacker beech mai packet capture kar le, toh usko aapka username aur password saaf nazar aa jaye ga.

---

# Secure Shell - SSH (TCP Port 22)

### Kiya karta hai:

SSH bhi remote access ke liye use hota hai, lekin yeh completely encrypted hota hai.

### Best Practice (Secured): 

Security issues ki wajah se aaj kal hamesha Telnet ki jagah SSH ka istemal kiya jata hai taake login credentials aur session data safe rahe.

---

| **Telnet** | **SSH** | 
|---|---|
| Unencrypted (Plaintext) | Less Secure | Port 23 |
| Encrypted | Highly Secure | Port 22 |

---

