# Zvučne teme (Audio Themes) #

*   Autori: Musharraf Omer i drugi
*   Preuzmi [stabilnu verziju][1]
*   Preuzmi [razvojnu verziju][2]

Ovaj dodatak izrađuje virtualni zvučni prikaz koji reproducira zvukove
tijekom fokusiranja objekta ili tijekom kretanja između objekata. Zvuk će se
reproducirati na mjestu koje odgovara mjestu objekta u vizualnom prikazu.

Dodatak također omogućuje aktiviranje, instaliranje, uklanjanje, uređivanje,
izradu i distribuiranje paketa zvučnih tema.

## Primjena

Ovaj dodatak omogućuje izvođenje triju različitih zadataka, uključujući
upravljanje trenutačno instaliranim zvučnim temama, uređivanje trenutačno
aktivne zvučne teme, te kreiranje nove zvučne teme.

Funkcijama se može pristupiti u podizborniku „Dodaci”, koji se nalazi u
glavnom NVDA izborniku.

### Upravljanje zvučnim temama

- Dijaloški okvir „Upravljanje zvučnim temama” omogućuje aktiviranje ili
  deaktiviranje zvučnih tema, kao i njihovo instaliranje ili uklanjanje.
- U ovom dijaloškom okviru se nalaze i neke dodatne opcije uključujući:
 - Reproduciraj zvukove u 3d modusu: Kad je ova opcija isključena, dodatak će uvijek reproducirati zvukove u mono modusu (uvijek u centru zvučnog prikaza) neovisno o lokaciji objekta.
 - Izgovori naziv kao što je gumb, polje za uređivanje, poveznica itd.: Kad je ova opcija isključena, NVDA će izgovarati nazive objekata (standardni način rada nakon instaliranja ovog dodatka).
 - Koristi glasnoću govorne jedinice: uključivanjem ove opcije, dodatak će koristiti glasnoću govorne jedinice, čime se izjednačava glasnoća zvukova, čak i kad se smanji glasnoća govorne jedinice.
 - Klizač za glasnoću zvučne teme: Alternativno je moguće podesiti glasnoću dodatka uz pomoć ovog klizača. Ako je podešen na 0, svi zvukovi će biti isključeni, a 100 je maksimalna glasnoća.

### Uređivanje aktivne zvučne teme:

- Klikom na opciju „Uređivanje aktivne zvučne teme”, otvorit će se dijaloški
  okvir koji sadrži popis svih zvukova dostupnih u trenutačno aktivnoj
  zvučnoj temi. Ovaj dijaloški okvir omogućuje:
- Promijeni odabrano: biranje nekog zvuka iz popisa i aktiviranje ovog
  gumba, otvorit će standardni dijaloški okvir za otvaranje
  datoteke. Odaberi neku ogg ili wav datoteku koja će zamijeniti odabrani
  zvuk i klikni gumb „U redu” za završavanje procesa.
- Ukloni odabrano: ova opcija će ukloniti odabrani zvuk iz teme. Za
  potvrđivanje uklanjanja, klikni na „Da”. Odabrani zvuk će biti uklonjen.
- Dodaj novi zvuk: kad klikneš na ovaj gumb, prikazat će se novi dijaloški okvir. Iz prvog odabirnog okvira odaberi vrstu objekta kojem želiš pridružiti zvuk, na primjer (gumb, izbornik, poveznica, kartica i tako dalje), a zatim klikni na „Pronađi zvučnu datoteku”, za biranje zvuka, koji će se reproducirati za prethodno odabrani objekt. Klikni na gumb za pregled, za slušanje odabranog zvuka. Klikom na gumb „U redu” će se promjene primijeniti i odabrani zvuk će se koristiti za odabranu vrstu objekta. 
- Zatvori: Izlazi iz dijaloga bez promjena.

### Kreiranje nove zvučne teme

- Ako znaš dizajnirati zvukove, možeš ih primijeniti ovdje i napraviti
vlastitu temu, umjesto uređivanja postojeće. Evo kako: - Skupi sve svoje
zvukove u jednu mapu (moraju biti u ogg ili wav formatu) te ih preimenuj
kako god želiš. Na primjer, prilikom izrade standardne teme za ovaj dodatak,
zvukovi su grupirani prema oblicima interakcije. Na primjer, izborni okvir,
padajući okvir i gumb za razdvajanje mogu imati isti zvuk, dok izborni
okvir, tipka prekidača i odabiruća stavka izbornika mogu imati jedan drugi
zvuk. - U izborniku dodatka odaberi „Stvori novu temu” – otvorit će se
dijaloški okvir koji zahtijeva informacije o temi, uključujući: *	Ime teme:
Ime teme koje će biti prikazano u dijaloškom okviru za upravljanje zvučnim
temama. Ovo mora biti ispravno ime za windows mapu. *	Vlastito ime: Upiši
svoje pravo ime ili nadimak. *	Opis teme: kratak opis teme. - Aktiviraj gumb
„U redu” za prelazak na sljedeći korak. - U sljedećem dijaloškom okviru,
otvorit će se dijaloški okvir koji je sličan kao „Uređivač zvučnih
tema”. Daljnje radnje su isti kao i za uređivanje zvučne teme, pa pogledaj
odjeljak „Uređivanje aktivne zvučne teme”.

## Autorska prava:

Autorska prava (c) 2014. – 2016. Musharraf Omer i drugi

Iako je ovaj dodatak počeo kao nezavisan projekt, razvio se kao poboljšana
verzija dodatka „Unspoken”, autora Austina Hicksa i Bryana Smarta. U razvoju
ovog dodatka je utrošeno najviše vremena na pravljenje alatki za
upravljanje, uređivanje i izradu paketa tema. Velika im hvala za pravljenje
odličnog dodatka, koji nam je koristio kao osnova.

## Napomena o zvukovima trećih stranki:

Standardna tema koristi različite izvore zvukova. Izvori su: - Unspoken 3D
Audio: Dodatak za NVDA, - TWBlue: Besplatan twitter klijent, otvorenog koda,
- Mushy TalkBack: Alternativan talkback s boljim zvukovima.

## Licenca
Licencirano pod GNU općom javnom licencom. Pročitaj datoteku **copying** za
daljnje detalje.

[[!tag dev]]

[1]: https://addons.nvda-project.org/files/get.php?file=ath

[2]: https://addons.nvda-project.org/files/get.php?file=ath-dev
