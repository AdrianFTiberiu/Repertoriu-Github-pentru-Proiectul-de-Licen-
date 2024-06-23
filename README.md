# Repertoriu-Github-pentru-Proiectul-de-Licenta
Include, în principal, scripturile pentru configurarea dispozitivelor din rețeaua de comunicație proiectată în lucrare, dar și pașii de configurare când aceasta se face prin interfața grafică oferită de simulatorul Packet Tracer.

Pașii de simulare a rețelei de comunicație local:

1. Se descarcă simulatorul Packet Tracer de la link-ul: https://skillsforall.com/resources/lab-downloads?courseLang=en-US
Descărcarea va presupune crearea unui cont pe site.

2. Va trebui să creăm o topologie ca în imaginea de mai jos:

![Alt text](./poze/poze%20Readme/Topologie/1.png)
![Alt text](./poze/poze%20Readme/Topologie/2.png)
![Alt text](./poze/poze%20Readme/Topologie/3.png)

2.5. Indicații despre implementarea topologiei

Tipurile de dispozitive și fire folosite:

PC : PC-PT 

Laptop : Laptop-PT

Telefon IP : IP Phone 7960

Punct de Acces : LAP-PT

Server : SERVER-PT

Comutator pe un singur nivel OSI : 2960-24TT

Comutator pe mai multe nivele OSI : 3650-24PS

Router VoIP și ISP-uri : 2811

Celelalte Routere : 2911

Controler fără fir : WLC-2504

fire negre de conectare : copper straight-through (linie continua) / cross-over (linie intrerupta)

fire rosii (seriale) : DCE

Scheme de conectare:
Se află în fișierul aflat la Repertoriu-Github-pentru-Proiectul-de-Licenta/Implementare/Configurare Comutatoare_și_Routere preliminar/conectare interfețe în topologie.txt

3. Unele dispozitive trebuie modificate pentru a putea funcționa în rețea

3.1. Liniile seriale au nevoie de anumite module hardware pentru a funcționa, cum ar fi HWC-2T. Aceste module va face ca interfețe care suportă linii seriale, cum ar fi se1/0/1, să existe.

![Alt text](./poze/poze%20Readme/1.Punere%20module%20seriale%20pe%20routere/1.png)
![Alt text](./poze/poze%20Readme/1.Punere%20module%20seriale%20pe%20routere/2.png)

3.2. Telefoanele IP și Punctele de Acces au nevoie de un adaptor pentru a putea fi alimentate. 

Telefoane IP
![Alt text](./poze/poze%20Readme/2.Conectare%20adaptor%20la%20telefon%20IP/4.png)
![Alt text](./poze/poze%20Readme/2.Conectare%20adaptor%20la%20telefon%20IP/5.png)

Puncte de Acces
![Alt text](./poze/poze%20Readme/3.Conectare%20adaptor%20la%20LAP/6.png)
![Alt text](./poze/poze%20Readme/3.Conectare%20adaptor%20la%20LAP/7.png)

3.3. Pentru a putea fi conectate la Punctele de Acces, Laptop-urile au nevoie de noi module, WPC.

![Alt text](./poze/poze%20Readme/4.Conectare%20modul%20Wireless%20la%20laptop/9.png)
![Alt text](./poze/poze%20Readme/4.Conectare%20modul%20Wireless%20la%20laptop/10.png)

4. Cu topologia încheiată, se parcurg directoarele din directorul Implementare și se aplică pe dispozitivele indicate în fișierele interioare, configurările și scripturile aflate în acestea. În timp, ce fiecare fișierele din fiecare director trebuie parcurs în ordine numerică, directoarele se parcurg în această ordine: 
Configurare Comutatoare_și_Routere preliminar, LAN1_Client, LAN2_Client, Server_LAN, WAN.


