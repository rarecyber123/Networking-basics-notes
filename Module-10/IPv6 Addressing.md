
# 1. IPv6 Address Kya Hai aur Kaise Likha Jata Hai?

- ## 128-Bit Address:

IPv4 ke muqable mai IPv6 bohot bada hota hai (128 bits). Is wajah se IP addresses kabhi khatam nahi honge.

- ## Hexadecimal System:

   Yeh 0–9 numbers aur A–F letters use karta hai.

 - ## Hextet:

   Address 8 hisson (segments) mai divide hota hai. Har segment ko Hextet kehte hain (16 bits = 4 hexadecimal digits).

> Preferred Format: Iska standard format x:x:x:x:x:x:x:x hota hai.

Example:

2001:0db8:0000:1111:0000:0000:0000:0200

---

# 2. Rule 1: Leading Zeros Omit Karna (Shuruati Zeros Hatana)

 Har hextet ke shuru wale zeros (0) ko aap hata sakte hain taake address chhota dikhe.

 - Rule: Sirf shuru ke zeros hataye ja sakte hain, baad ke (trailing zeros) nahi! Agar baad ke zeros hataye to address ki value change ho jayegi.

 "Examples":
  > 01ab $\rightarrow$ 1ab00ab $\rightarrow$ ab0000 $\rightarrow$ 0

- Rule 2: Double Colon (::) Ka Use
Agar address mai ek saath continuous zeros wale hextets aarahe hon, to un sab ko replace karke :: lagaya ja sakta hai.

### Golden Rule: 
  
   :: poore address mai sirf ek baar use ho sakta hai! Agar do baar use karoge to kisi ko samajh nahi aayega ke kis taraf kitne zeros the.

### Best Practice: 

   Agar address mai zeros ke alag alag groups hon, to sab se bade zeros wale group ki jagah :: lagayein.

---
Conversation with Gemini
10.2 human toone mai notes do 
Yahan 10.2: IPv6 Addressing ke aasan aur conversational style (human tone) mai clear notes hain, taake aapko concepts smoothly samajh aa jayein:

1. IPv6 Address Kya Hai aur Kaise Likha Jata Hai?
128-Bit Address: IPv4 ke muqable mai IPv6 bohot bada hota hai (128 bits). Is wajah se IP addresses kabhi khatam nahi honge.

Hexadecimal System: Yeh 0–9 numbers aur A–F letters use karta hai.

Hextet: Address 8 hisson (segments) mai divide hota hai. Har segment ko Hextet kehte hain (16 bits = 4 hexadecimal digits).

Preferred Format: Iska standard format x:x:x:x:x:x:x:x hota hai.

Example:

2001:0db8:0000:1111:0000:0000:0000:0200

2. Rule 1: Leading Zeros Omit Karna (Shuruati Zeros Hatana)
Har hextet ke shuru wale zeros (0) ko aap hata sakte hain taake address chhota dikhe.

Rule: Sirf shuru ke zeros hataye ja sakte hain, baad ke (trailing zeros) nahi! Agar baad ke zeros hataye to address ki value change ho jayegi.

Examples:

01ab → 1ab

00ab → ab

0000 → 0

- Rule 2: Double Colon (::) Ka Use
Agar address mai ek saath continuous zeros wale hextets aarahe hon, to un sab ko replace karke :: lagaya ja sakta hai.

### Golden Rule: :: poore address mai sirf ek baar use ho sakta hai! Agar do baar use karoge to kisi ko samajh nahi aayega ke kis taraf kitne zeros the.

### Best Practice: 

Agar address mai zeros ke alag alag groups hon, to sab se bade zeros wale group ki jagah :: lagayein.

4. Quick Comparison & Examples

| **Format Type** | **Address Example** | **Explanation** |
|---|---|
| Preferred Format2001:0db8:0000:0000:0000:0000:0000:0001Poora 32-digit representationRule 1 (No Leading Zeros)2001:db8:0:0:0:0:0:1Shuruati zeros hata diyeCompressed (Rule 1 + Rule 2)2001:db8::1Zeros wale block ko :: se replace kar diya

---

# Pro-Tip 💡

> Loopback address IPv6 mai 0:0:0:0:0:0:0:1 hota hai $\rightarrow$ Compress karke sirf ::1 likhte hain.

> Unspecified address 0:0:0:0:0:0:0:0 hota hai $\rightarrow$ Compress karke sirf :: likhte hain.
