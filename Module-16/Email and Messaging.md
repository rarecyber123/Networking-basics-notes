
# 1. Email Clients & Servers

- Client/Server Model: Email works on a basic setup where your email client (like Gmail, Outlook, or Yahoo) talks to a mail server.

- Mailbox Format: Always written as user@company.domain.

 - How it flows: The sender's client uses SMTP to send the email to their local server $\rightarrow$ local server forwards it to the recipient's server via SMTP $\rightarrow$ recipient downloads or reads it using POP3 or IMAP4.

---

# 2. Core Email Protocols & Port Numbers

### SMTP (Simple Mail Transfer Protocol)

- Role: Used exclusively for sending emails (client to server, or server to server).

- Port: 25


### POP3 (Post Office Protocol v3)

- Role: Downloads emails from the server directly to your device.

- Key Feature: Deletes the email from the server once downloaded (by default).

- Port: 110

---

### IMAP4 (Internet Message Access Protocol v4)

- Role: Syncs and manages emails directly on the server.

- Key Feature: Keeps emails stored on the server so you can access them from multiple devices.

- Port: 143

  ---

# 3. Text Messaging (Instant Messaging)

### How it works:

Works in real-time where devices act as both Client and Server simultaneously to send and receive messages at the same time.

### Types: 

Web-based chats, integrated social media DMs, or standalone apps (WhatsApp, MS Teams, Cisco Webex).

### Beyond Text:

Modern messaging apps also handle files, audio, and video sharing.

---

# 4. Internet Phone Calls (VoIP)

- Voice over IP (VoIP) analog voice signals ko digital packets mai convert karke network par transfer karta hai.

- Regular landline ya mobile numbers par call karne ke liye Gateway ki zaroorat hoti hai jo PSTN (Public Switched Telephone Network) se connect karta hai.

  ---
