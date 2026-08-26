
# FTP (File Transfer Protocol)

> Basically remote computer across network files copy, upload ya download karne ka standard tareeqa hai. Simple wordings mai, yeh client aur server ke beech file sharing simple aur manage karne ke liye use hota hai.

# FTP Ka Operating Mechanism

### FTP do alag TCP ports ke zariye connection handle karta hai:

## Control Connection (TCP Port 21):

Jab client server se connect hota hai, sabse pehle port 21 par control connection banta hai. Yeh connection commands bhejne (jaise login, delete, rename, etc.) aur session control karne ke kaam aata hai.

---

# Key Features & Usage

- File Management: Download aur upload ke ilawa remote server par file delete karna ya rename karna bhi possible hota hai.

- Interfaces: Windows/Mac ke built-in command line, web browsers, ya FileZilla jaise dedicated GUI-based tools ke zariye utilize kiya ja sakta hai.

  ---
## Data Connection (TCP Port 20):

Commands clear hone ke baad actual files upload ya download karne ke liye server TCP port 20 ka istemal karke data transfer connection establish karta hai.
