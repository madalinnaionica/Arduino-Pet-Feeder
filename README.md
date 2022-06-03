# Arduino-Pet-Feeder
Proiectul Arduino Pet Feeder alimenteaza automat cu hrana animalul de companie la apsarea unui buton de pe matricea 4x4. Avem la dispozitie 9 viteze (testele 1-9) in functie de care putem stabili cantitatea de mancare necesara. Actionarea butoanelor determina deplasarea la 118 grade in partea stanga a componentei ce blocheaza trecerea mancarii. Fiecare tasta are asociat un delay, de la 50 de milisecunde pana la 5000, acestea reprezentand intervalele de timp de la deplasarea componetei pana la revenirea ei in stare initiala.

Elementele folosite au fost
- Breadbord
- 16x2 LCD
- Arduino UNO R3
- Matrice 4x4
- Servo motor
- Rezistenta 4.7k
- Fire de legatura

In partea de cod, am integrat in functia main (loop) cate o structura if pentru fiecare tasta, asociindu-i delay-ul dar si numarul de grade de rotatie. Mai mult decat atat, am afisat pe ecranul LED un mesaj sugestiv pentru utilizator.
