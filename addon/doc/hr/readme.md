# Audio Themes #

*   autori: Musharraf Omer i drugi
*   Preuzmite [stabilnu inačicu][1]
*   preuzmite [razvojnu inačicu][2]

Ovaj dodatak kreira virtualni zvučni prikaz koji reproducira zvuk dok se
krećete između objekata ili ste fokusirani na određeni objekt (kao što su
gumbi, linkovi itd...), zvuk će se reproducirati na mjestu koje odgovara
mjestu prikaza objekta na zaslonu. 

Dodatak vam također omogućava da aktivirate, instalirate, uklonite,
uređujete, kreirate i distribuirate pakete zvučnih tema.

## Korištenje 

Ovaj dodatak omogućava izvođenje tri tipa zadataka, uključujući upravljanje
trenutno instaliranim zvučnim temama, uređivanje trenutno aktivne zvučne
teme, te kreiranje nove zvučne teme. 

Ovim funkcijama možete pristupiti iz podizbornika Dodaci koji se nalazi u
glavnom NVDA izborniku.

### Upravljanje zvučnim temama 

- Dijaloški okvir 'Upravljanje zvučnim temama' omogućuje vam da aktivirate
  ili deaktivirate zvučne teme, kao i instaliranje ili uklanjanje istih.
- U ovom dijaloškom okviru nalaze se i neke dodatne opcije uključujući:
 - Reproduciraj zvukove u 3d modu: Kada ova opcija nije omogućena, dodatak će uvijek reproducirati zvukove u mono režimu(uvijek u centru zvučnog prikaza) nezavisno od lokacije objekta.
 - Izgovori naziv kao što je gumb, polje za uređivanje, link i tako dalje.: Kada je ova opcija onemogućena, NVDA će izgovarati nazive objekata(što je podrazumijevano nakon instalacije ovog dodatka).
 - Koristi glasnoću govorne sinteze: ukljućivanjem ove opcije dodatak će koristiti glasnoću govorne sinteze Što čini zvukove jednake glasnoće, čak i kada smanjite glasnoću govorne sinteze.
 - Klizač za glasnoću zvučne teme: Alternativno možete podesiti glasnoću dodatka uz pomoć ovog klizača. Ako je podešen na 0, svi zvukovi će biti isključeni, a 100 je maksimalna glasnoća.

### Uređivanje aktivne zvučne teme 

- Kada kliknete na opciju 'Uređivanje aktivne zvučne teme, otvorit će se
  dijaloški okvir koji sadrži popis svih zvukova dostupnih u trenutno
  aktivnoj zvučnoj temi. U ovom dijaloškom okviru možete 
- Promijeni odabrano: biranje nekog zvuka iz popisa i aktiviranje ovog gumba
  otvorit će standardni dijaloški okvir za otvaranje datoteke, izaberite
  neku ogg ili wav datoteku koja će zamijeniti odabrani zvuk i kliknite na
  uredu da završite proces.
- Uklanjanje odabranog zvuka: ova opcija će ukloniti trenutni zvuk iz teme,
  kliknite da kako biste završili uklanjanje i zvuk koji ste odabrali će
  biti uklonjen.
- dodajte novi zvuk: kada kliknete na ovaj gumb, novi dijaloški okvir će biti prikazan. Iz prvog odabirnog okvira izaberite tip objekta kojem želite pridružiti zvuk, na primjer(gumb, izbornik, link, kartica, i tako dalje), a zatim kliknite na pronađite zvučnu datoteku kako biste izabrali zvuk koji će se reproducirati za prethodno izabrani objekt. Možete aktivirati gumb pregled kako biste čuli odabrani zvuk i nakon što kliknete na gumb uredu, promjene će biti primijenjene i izabrani zvuk će biti korišten za odabrani tip objekta. 
- zatvori: Izlazi iz dijaloga bez ikakvih promjena.

### Kreiranje nove zvučne teme 

- Ako imate dobre vještine za dizajn zvukova, možete ih primijeniti ovdje i
napraviti vašu temu, umjesto uređivanja postojeće. Kako biste to učinili,
pratite sljedeće korake.  - Skupite sve vaše zvukove u jednu mapu, oni
moraju biti u ogg ili wav formatu, te ih preimenujte u ono što vama
odgovara. Na primjer kada sam pravio podrazumijevanu temu za ovaj dodatak,
grupirao sam zvukove prema oblicima interakcije, na primjer, izborni okvir,
padajući okvir, i gumb za razdvajanje mogu imati isti zvuk, dok izborni
okvir, tipka prekidača i odabiruća stavka izbornika mogu imati isti zvuk.  -
U izborniku dodatka odaberite napravi novu temu- bit će otvoren dijaloški
okvir koji zahtijeva informacije o vašoj temi, uključujući: *	ime teme : Ime
teme koje će biti prikazano u dijaloškom okviru za upravljanje zvučnim
temama. Ovo mora biti ispravno windows ime.  *	Vaše ime: Upišite vaše pravo
ime ili nadimak.  *	Opis teme : kratak opis vaše teme.  - Aktivirajte gumb
uredu da pređete na sljedeći korak.  - U sljedećem dijaloškom okviru,
dijaloški okvir sličan uređivanju zvučnih tema će biti otvoren i odatle
proces je isti kao i uređivanje zvučne teme, pa pogledajte sekciju za
uređivanje aktivne zvučne teme.

## Autorska prava 

Autorska prava i drugi 

Iako je ovaj dodatak počeo kao nezavisan projekt , Razvio se kao poboljšana
verzija dodatka unspoken autora Austina Hicksa i Bryana Smarta. Većina
razvoja ovog dodatka bilo je pravljenje alatki za upravljanje, uređivanje i
pravljenje tema. Velika zahvalnost njima za pravljenje odličnog dodatka, na
kojem smo radili.

## Napomena za zvukove 

Podrazumijevana tema koristi više različitih zvukova, ovdje su mjesta sa
kojih ti zvukovi dolaze: - Unspoken 3D Audio: Dodatak za NVDA - TWBlue:
Besplatan twitter klijent, otvorenog koda- Mushy TalkBack: Alternativan
talkback sa boljim zvukovima.

## Licenca 
Licencirano pod GNU General Public License. Pročitajte datoteku copying za
više detalja.

[[!tag dev]]

[1]: https://addons.nvda-project.org/files/get.php?file=ath

[2]: https://addons.nvda-project.org/files/get.php?file=ath-dev
