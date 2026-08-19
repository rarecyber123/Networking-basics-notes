
" Jab hum ek bara network banate hain, toh sabse bara masla ye hota hai ke har device ki traffic sab jagah phail jati hai, jis se speed slow aur management mushkil ho jati hai. Isliye network ko chote chote hisson mein taqseem karna parhta hai." 

# Dividing the Local Network 

- ### Broadcast Domains:

   Jab network chota hota hai, toh fazool traffic (broadcasts) doosri jagahon par nahi jati, jis se network fast rehta hai.

- ### Security:

   Chote networks mein security lagana aur data ko secure rakhna kaafi aasan ho jata hai.

- ### Troubleshooting:

   Agar koi masla aaye, toh poore network ko chhanne ki bajaye chote segment mein masla dhoondna aasan hota hai.

  ---
  
# Role of Router 

> Jab do alag networks aapas mein baat karte hain, toh wahan Router ka kaam shuru hota hai.


- ### Switch vs Router:

  Switch local network ke andar MAC Address dekh kar data bhejta hai. Lekin Router IP Address par kaam karta hai aur yeh decide karta hai ke data ko doosre network tak pahunchane ka sabse behtar rasta (best path) kaunsa hai.

- ###  Network Portion Check:

   Router IP address ka pehla hissa (Network Portion) dekhta hai. Agar sender aur receiver ka network alag ho, toh Router packet ko pakadta hai, uski purani packaging (Ethernet Frame) kholta hai, naye raste ke mutabiq nayi packaging karta hai, aur aage bhej deta hai.

  ---

 # Quick Summary Points

- ### Network Divider:

  Networks ko alag karne aur dividing ke liye Routers use hote hain.

- ### Routing Definition:

   Destination tak pahunchne ke liye best path select karne ke process ko Routing kehte hain.

- ### Key Purpose:

   Security barhana, traffic kam karna, aur troubleshooting aasan banana.

  ---
