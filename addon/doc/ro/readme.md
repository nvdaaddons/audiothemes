# Teme audio #

*   Autori: Musharraf Omer și alții
*   descărcați [versiunea stabilă][1]
*   descărcați [versiunea în dezvoltare][2]

Acest supliment crează un afișaj audio virtual care redă sunete atunci când
obiectele de focalizare sau navigare (precum butoane, linkuri etc...) vor fi
redate  audio într-o locație care corespunde cu locația obiectului în
afișajul vizual.

De asemenea, suplimentul vă permite să activați, instalați, ștergeți,
editați, creați și să partajați pachetele temelor audio.

## Utilizare

Acest supliment vă permite să efectuați trei activități distincte, incluzând
gestionarea temelor audio instalate, editarea temei audio activă în acel
moment, și crearea unor teme audio noi.

Puteți accesa această funcționalitate din meniul suplimentului care este
găsit în în meniul principal al NVDA.

### Gestionarea temelor audio

- Dialogul 'Manage Audio Themes'  vă permite să activați sau dezactivați
  teme audio, în plus puteți să instalați sau să ștergeți teme audio.
În acest dialog există niște opțiuni adiționale incluzând:
 - redarea sunetelor în modul 3D: Când debifați această casetă, add-on-ul va reda sunetele în modul mono (în totdeauna în centrul afișajului audio) indiferent de locația obiectului.
 - Rolul vorbirii precum buton, casetă de editare, link etc.: Când debifați această căsuță, NVDA va porni anunțarea rolului la focalizarea obiectelor, mai degrabă decât ignorarea lui (care este comportamentul implicit la instalarea acestui add-on).
 - utilizează volumul sintetizatorului: Bifând această casetă veți seta playerul sunetului la acest add-on pentru a utiliza sunetul vocal activ făcând astfel toate ieșirile sonore la fel ca și volumul vocii atunci când vreodată vă schimbați acel volum.
 - Glisorul de volum al temei audio: Alternativ, Puteți seta volumul pentru add-on folosind acest glisor. Setându-l la valoarea 0 veți dezactiva toate sunetele, iar 100 este valoarea maximă.

### Editarea temei audio active

- Când clicați pe opțiunea 'Editați tema audio', un dialog se va deschide cu
  o listă care conține toate sunetele din care este alcătuită tema audio
  activă. Din acest dialog, puteți:
- Modificați selecția: Selectând un sunet din listă și apăsând acest buton,
  va deschide un dialog cu un deschizător standard de fișiere, selectați un
  fișier audio ogg sau wave din computer pentru a înlocui sunetul selectat,
  apoi clicați pe OK pentru a completa procesul. 
- Ștergeți selecția: Aceasta va șterge sunetul selectat din temă, dați un
  click pe 'Da' pentru a confirma procesul de ștergere și sunetul selectat
  va fi șters.
- Adăugare sunet nou: Când apăsați acest buton, un nou dialog va fi afișat. Din prima căsuță combinată în noul dialog deschis, selectați tipul de obiect căruia vreți să atribuiți sunetul acestuia, de exemplu (buton, link, tab, meniu și așa mai departe), apoi dați un click pe butonul 'Browse to an audio file' pentru a selecta sunetul pe care vreți să-l alocați la tipul de obiect selectat. Opțional, puteți clica pe butonul de previzualizare pentru a examina sunetul, apoi clicând pe butonul OK modificările se vor aplica și sunetul selectat se va aloca la obiectul selectat.
Închide: Va ieși din fereastra de dialog fără a efectua vreo acțiune.

### Crearea unei teme  audio

- Dacă aveți o bună capacitate de producție de sunet le puteți aplica aici
și   creați o temă audio proprie, mai degrabă decât editarea uneia
existente. Pentru a face acest lucru, urmați acești pași. - Colectați
fișierele audio într-un singur loc, acestea trebuie să fie în format wave
sau Ogg, și redenumiți-le cum doriți. De exemplu, atunci când am creat tema
audio implicită pentru acest add-on, am grupat sunete în funcție de modele
de interacțiune, de exemplu, căsuța combinată, meniurile butonului de
coborâre și butonul de divizare, toate acestea pot avea același sunet, în
timp ce căsuța de bifat, butonul de comutare și meniul elementului de
verificare pot avea același sunet. - Din meniul add-on-ului clicați pe
"Creați o nouă temă audio" - Un dialog va fi deschis și vi se vor cere
informații despre noua temă audio, inclusiv: * Numele acesteia Numele temei
dumneavoastră. care va fi afișat în managerul audio de teme. Acest lucru
trebuie să fie un nume de folder  valid din PC. * Numele dumneavoastră:
Introduceți numele dumneavoastră real sau o poreclă. * Descrierea Temei: O
scurtă descriere despre tema audio. - Faceți clic pe OK pentru a trece la
pasul următor. - În pasul următor va fi afișat un dialog similar cu
„editorul temelor audio”", iar procesul este la fel ca și cel de editare al
temei.

## Drepturi de autor:

Drepturi de autor (c) 2014-2016 Musharraf Omer și alții

Cu toate că acest supliment a fost început ca un proiect independent, acesta
a evoluat pentru a fi o versiune îmbunătățită a suplimentului 'Unspoken' de
Austin Hicks și Bryan Smart. 

## O notă privind fișierele audio:

Tema audio implicită în acest supliment utilizează sunete de la diferite
aplicații terțe: - Unspoken 3D Audio: Un supliment pentru NVDA - TWBlue: O
aplicație de Twitter, gratis și open source - Mushy TalkBack: Unn talkback
alternativ cu sunete îmbunătățite.

## Licență
Licențiat de GNU General Public License. Citiți fișierul **copying** pentru
mai multe detalii.

[[!tag dev stable]]

[1]: https://addons.nvda-project.org/files/get.php?file=ath

[2]: https://addons.nvda-project.org/files/get.php?file=ath-dev
