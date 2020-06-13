# Zaščitno vžiganje avtom. motorja:
Navodilo naloge:

Ko obrnemo ključ v desno, se sklene kontakt A, ki aktivira zaganjalnik. Pogoj za to pa je, da je vklopljeno skrivno stikalo B. zaganjalnika tudi ni mogoče pognati, če motor že teče, kar zazna senzor M.	

Vhodi			
Oznaka v načrtu	 Naslov operanda	Vrsta kontakta	                    Pomen
A	               X0	              No	                                Prižig motorja
B	               X1	              No	                                Varnostno stikalo
			
Izhodi			
Oznaka v načrtu	 Naslov operanda	Aktiven pri	                        Pomen
M	               Y0	              Pozitivnem signalu stikala A in B	  Motor

Kosovnica: 
1x Arduino UNO,
1x Breadboard,
12x Kabel,
1x DC Motor,
1x Stikalo,
1x Upor, 
1x Tipka.


Komentar delovanja:
Ko zavrtimo ključ A (tipka) se motor M (DC motor) vklopi, ampak samo če je pri tem prižgano še dodatno skrivno stikalo B (stikalo).
Motor se lahko prižge s ključem A, samo če že ni prižgan. Motor se izkluči z ugasnitvijo stikala B. 

Predlogi za izboljšanje naprave:
Napravo bi lahko izboljšali z dodatnim stikalom/tipko, ki bi lahko delovala kot sklopka avta. Dodali bi pa še lahko stikalo, ki bi deloval kot menjava smeri vrtenja motorja (vzratna voćnja).
