# Audio Teme #

*   Autori: Musharraf Omer i drugi
*   Preuzmi [stabilna verzija][1]
*   Preuzmi [verzija u razvoju][2]

Ovaj dodatak pravi virtuelni audio ekran koji reprodukuje zvukove nakon
fokusiranja na određene objekte ili navigaciju(kao što su dugmići, linkovi i
tako dalje...) zvuk će biti reprodukovan na lokaciji koja odgovara lokaciji
na ekranu.

Dodatak vam takođe omogućava da aktivirate, instalirate, uklonite,
uređujete, kreirate i delite audio teme

## Korišćenje

Ovaj dodatak vam omogućava da radite na 3 različita zadatka, uključujući
upravljanje vašim audio temama, uređivanje trenutno aktivne teme, i
kreiranje nove audio teme.

Možete da pristupite ovim funkcijama u meniju dodatka koji se nalazi u NVDA
meniu.

### Upravljanje vašim audio temama 

- Dijalog za upravljanje audio temama vam omogućava da aktivirate ili
  deaktivirate teme, kao i da instalirate ili uklonite već instalirane teme.
- U ovom dijalogu imate i neke dodatne opcije uključujući:
 - Reprodukuj zvukove u 3d modu: Kada ova opcija nije omogućena, dodatak će uvek reprodukovati zvukove u mono režimu(uvek u centru audio ekrana) nezavisno od lokacije objekta.
 - Izgovori naziv kao što je dugme, polje za uređivanje, i tako dalje.: Kada je ova opcija onemogućena, NVDA će izgovarati nazive objekata(što je podrazumevano nakon instalacije ovog dodatka).
 - Koristi jačinu govorne sinteze: Štikliranjem ove opcije, dodatak će koristiti jačinu govorne sinteze Što čini zvukove jednake jačine, čak i kada smanjite jačinu govorne sinteze.
 - Klizač za jačinu audio teme: Alternativno možete podesiti jačinu dodatka uz pomoć ovog klizača. Ako je podešen na 0 svi zvukovi će biti isključeni, a 100 je najača jačina.

### Uređivanje trenutno aktivne teme:

- Kada kliknete na opciju uredi aktivnu temu, otvoriće se lista koja sadrži
  zvukove aktivne audio teme. Iz ovog dijaloga možete:
- Promeni izabrano: biranje nekog zvuka iz liste i aktiviranje ovog dugmeta,
  će otvoriti standardan dijalog za otvaranje datoteke, izaberite neku ogg
  ili wav dadoteku koja će zameniti odabran zvuk, i kliknite na uredu da
  završite proces.
- Uklanjanje odabranog zvuka: ova opcija će ukloniti trenutan zvuk iz teme,
  kliknite da kako biste završili uklanjanje , i izabran zvuk će biti
  uklonjen.
- dodajte nov zvuk: kada kliknete na ovo dugme novi dijalog će biti prikazan. Iz prvog izbornog okvira izaberite tip objekta kojem želite da pridružite zvuk, na primer(dugme, meni, link, kartica, i tako dalje), A zatim kliknite na pronađite audio datoteku dugme kako biste izabrali zvuk koji ćese reprodukovati za prethodno izabran objekat. Možete aktivirati dugme pregled kako biste čuli izabran zvuk, I nakon što kliknete na dugme uredu, promene će biti primenjene i izabran zvuk će biti korišćen za izabran tip objekta. 
- zatvori: Izlazi iz dijaloga bez ikakvih promena.

### Kreiranje nove audio teme

- Ako imate dobre veštine za dizajn zvukova možete ih primeniti ovde i
napraviti vašu temu, umesto uređivanja postojeće. Da uradite ovo pratite
sledeće korake.  - Skupite sve vaše zvukove u jedan folder, oni moraju biti
u ogg ili wav formatu, i preimenujte ih u ono što vama odgovara. Na primer
kada sam pravio podrazumevanu temu za ovaj dodatak, grupisao sam zvukove
prema oblicima interakcije, na primer, izborni okvir, padajući okvir, i
dugme za razdvajanje mogu imati isti zvuk, dok izborni okvir, dugme
prekidača, i štiklirajuća stavka menija mogu imati isti zvuk.  - Iz menia
dodatka izaberite napravi novu temu- dijalog će biti otvoren koji zahteva
informacije o vašoj temi, uključujući: *	ime teme : Ime teme koje će biti
prikazano u dijalogu za upravljanje audio tema. Ovo mora biti ispravno
windows ime.  *	Vaše ime: Upišite vaše pravo ime ili nadimak.  *	Opis teme :
kratak opis vaše teme.  - Aktivirajte dugme uredu da pređete na sledeći
korak.  - U sledećem dijalogu dijalog sličan uređivanju audio tema će biti
otvoren, i odatle proces je isti kao i uređivanje audio teme, pa pogledajte
sekciju za uređivanje aktivne audio teme.

## Autorska prava:

Copyright (c) 2014-2016 Musharraf Omer i ostali

Iako je ovaj dodatak počeo kao nezavisan projekat , Razvio se kao poboljšana
verzija dodatka unspoken autora Austin Hicks i Bryan Smart. Većina razvoja
ovog dodatka jeste bilo pravljenje alatki za upravljanje, uređivanje i
pravljenje tema. Velika zahvalnost njima za pravljenje odličnog dodatka, na
kojem smo radili.

## Napomena za zvukove:

Podrazumevana tema koristi više različitih zvukova, ovde su mesta sa kojih
ti zvukovi dolaze: - Unspoken 3D Audio: Dodatak za NVDA - TWBlue: Besplatan
twitter klijent, otvorenog koda- Mushy TalkBack: Alternativan talkback sa
boljim zvukovima.

## licenca
Licencirano pod GNU General Public License. Pročitajte datoteku copying za
više detalja.

[[!tag dev stable]]

[1]: https://addons.nvda-project.org/files/get.php?file=ath

[2]: https://addons.nvda-project.org/files/get.php?file=ath-dev
