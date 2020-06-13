# Zaščitno vžiganje avtom. motorja:
Navodilo naloge:

Ko obrnemo ključ v desno, se sklene kontakt A, ki aktivira zaganjalnik. Pogoj za to pa je, da je vklopljeno skrivno stikalo B. zaganjalnika tudi ni mogoče pognati, če motor že teče, kar zazna senzor M.	

Vhodi<br/>			
Oznaka v načrtu &nbsp; Naslov operanda &nbsp; Vrsta kontakta &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; Pomen<br/>
A &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; X0 &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; No &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; Prižig motorja <br/>
B &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; X1 &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; No &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; Varnostno stikalo <br/>
			
Izhodi	<br/>		
Oznaka v načrtu &nbsp; Naslov operanda &nbsp; Aktiven pri &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; Pomen<br/>
M &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; Y0 &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; Pozitivnem signalu stikala A in B &nbsp; &nbsp; &nbsp; Motor<br/>

Kosovnica: <br/>
1x Arduino UNO,<br/>
1x Breadboard,<br/>
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
