
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

- Examples:
  > 01ab $\rightarrow$ 1ab00ab $\rightarrow$ ab0000 $\rightarrow$ 0
