# MirkoPopovic5DanaUOblacima
-Aplikacija za beleženje igrača i timova za matchmaking sistem
-Radio Mirko Popović 2024.
-Kontakt: mimamirkop@gmail.com

Aplikacija rađena u Visual Studio Code okruženju, u Node.Js programskom jeziku, za packet manager je korišćen npm, a za "in memory" bazu podataka korišćen je SQLITE3.

Kako bi aplikacija funkcionisala potrebno je pokrenuti server pomoću terminala u VS code: node server/server.js. U terminalu će se potom pojaviti poruka sa linkom na lokalnoj stranici: http://localhost:8080. Klik na link odvešće korisnika na statičku HTML stranicu gde uz pomoć formi može da kreira igrače, timove i mečeve


U prilogu se nalaze screenshot-ovi pokretanja servera u terminalu i pojedinih delova stranice

<img width="1246" alt="Screenshot 2024-11-20 at 21 16 17" src="https://github.com/user-attachments/assets/0b6071ca-561d-4d84-b465-cbb54dc048ef">
<img width="1349" alt="Screenshot 2024-11-20 at 21 16 11" src="https://github.com/user-attachments/assets/1af422b0-f010-4e24-9c00-091370188dbc">
<img width="1380" alt="Screenshot 2024-11-20 at 21 16 04" src="https://github.com/user-attachments/assets/1106a470-11b6-4107-b0a7-0c6cbe4a6ecb">
<img width="1392" alt="Screenshot 2024-11-20 at 21 15 39" src="https://github.com/user-attachments/assets/e8b73053-5087-49b0-8473-2aaa2097e0ee">
<img width="1214" alt="Screenshot 2024-11-20 at 21 15 28" src="https://github.com/user-attachments/assets/7e350c1f-52f6-4e89-aadf-78d0cfd06ecb">


Korišćene tehnologije:

1. Node.JS - open-source okvir za izradu serverskih aplikacija, baziran na JavaScriptu. Omogućava izvršavanje JavaScript koda van pretraživača
2. npm - je menadžer paketa za node.js, omogućava lako upravljanje, instaliranje i deljenje paketa koji se koriste u node.js aplikacijama
3. Sqlite3 - lagana, samostalna baza podataka, korišćena za izradu "in memory" baze podataka tj. baze čiji se podaci brišu pri resetovanju servera
4. Postman - program za javne testove funkcionalnosti aplikacije
5. HTML/CSS - HTML predstavlja standardni jezik za strukturisanje veb stranica, CSS služi za stilizovanje HTML elemenata
6. VS Code - besplatan editor otvorenog koda plasiran od strane Microsoft-a

