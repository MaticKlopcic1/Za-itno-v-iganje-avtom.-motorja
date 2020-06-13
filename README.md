# Zaščitno vžiganje avtom. motorja:
Navodilo naloge:

Ko obrnemo ključ v desno, se sklene kontakt A, ki aktivira zaganjalnik. Pogoj za to pa je, da je vklopljeno skrivno stikalo B. zaganjalnika tudi ni mogoče pognati, če motor že teče, kar zazna senzor M.	

Vhodi			
Oznaka v načrtu	 Naslov operanda	Vrsta kontakta	                    Pomen<br/>
A	               X0	        No	                                Prižig motorja
B	               X1	        No	                                Varnostno stikalo
			
Izhodi			
Oznaka v načrtu	 Naslov operanda	Aktiven pri	                        Pomen
M	               Y0	        Pozitivnem signalu stikala A in B	  Motor

Kosovnica: <br/>
1x Arduino UNO,<br/>
1x Breadboard,<br/><br/>
12x Kabel,<br/>
1x DC Motor,<br/>
1x Stikalo,<br/>
1x Upor, <br/>
1x Tipka.<br/>


Komentar delovanja:
Ko zavrtimo ključ A (tipka) se motor M (DC motor) vklopi, ampak samo če je pri tem prižgano še dodatno skrivno stikalo B (stikalo).
Motor se lahko prižge s ključem A, samo če že ni prižgan. Motor se izkluči z ugasnitvijo stikala B. 

Predlogi za izboljšanje naprave:
Napravo bi lahko izboljšali z dodatnim stikalom/tipko, ki bi lahko delovala kot sklopka avta. Dodali bi pa še lahko stikalo, ki bi deloval kot menjava smeri vrtenja motorja (vzratna voćnja).
