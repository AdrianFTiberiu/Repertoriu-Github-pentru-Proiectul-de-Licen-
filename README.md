# Repertoriu-Github-pentru-Proiectul-de-Licenta
Include, în principal, scripturile pentru configurarea dispozitivelor din rețeaua de comunicație proiectată în lucrare, dar și pașii de configurare când aceasta se face prin interfața grafică oferită de simulatorul Packet Tracer.

Pașii de simulare a rețelei de comunicație local:

1. Se descarcă simulatorul Packet Tracer de la link-ul: https://skillsforall.com/resources/lab-downloads?courseLang=en-US
Descărcarea va presupune crearea unui cont pe site.

2. Va trebui să creăm o topologie ca în imaginea de mai jos:

//poză cu întreaga topologie

2.5. Indicații despre implementarea topologiei

Tipurile de dispozitive și fire folosite:
PC : PC-PT /
Laptop : Laptop-PT /
Telefon IP : IP Phone 7960 /
Punct de Acces : LAP-PT /
Server : SERVER-PT /
Comutator pe un singur nivel OSI : 2960-24TT /
Comutator pe mai multe nivele OSI : 3650-24PS /
Router VoIP și ISP-uri : 2811 /
Celelalte Routere : 2911 /
Controler fără fir : WLC-2504 /
fire negre de conectare : copper straight-through (linie continua) / cross-over (linie intrerupta) /
fire rosii (seriale) : DCE

Scheme de conectare:
Se află în fișierul aflat la Repertoriu-Github-pentru-Proiectul-de-Licen-/Configurare Comutatoare_și_Routere preliminar/conectare interfețe în topologie.txt

3. Unele dispozitive trebuie modificate pentru a putea funcționa în rețea

//vezi folder-ul cu screenshot-uri

4. Cu topologia încheiată, se parcurg directoarele și se aplică pe dispozitivele indicate în fișierele interioare, configurările și scripturile aflate în acestea. În timp, ce fiecare fișierele din fiecare
director trebuie parcurs în ordine numerică, directoarele se parcurg în această ordine: 
Configurare Comutatoare_și_Routere preliminar, LAN1_Client, LAN2_Client, Server_LAN, WAN.


