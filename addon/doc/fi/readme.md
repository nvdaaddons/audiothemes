# Ääniteemat #

*   Tekijät: Musharraf Omer sekä muut
*   Lataa [vakaa versio][1]
*   Lataa [kehitysversio][2]

Tämä lisäosa luo virtuaalisen ääninäytön, joka toistaa ääniä objekteja
(kuten painikkeet, linkit jne.) aktivoitaessa tai siirryttäessä niiden
välillä. Ääni toistetaan sijainnissa, joka vastaa objektin sijaintia
visuaalisella näytöllä.

Lisäosa mahdollistaa myös ääniteemapakettien käyttöön ottamisen,
asentamisen, poistamisen, muokkaamisen, luomisen sekä jakelun.

## Käyttö

Tämän lisäosan avulla voit suorittaa kolme eri tehtävää, joita ovat
asentamiesi ääniteemojen hallinta, aktiivisen teeman muokkaaminen sekä uuden
luominen.

Voit käyttää näitä toimintoja lisäosan omasta valikosta, joka löytyy
NVDA-valikosta.

### Ääniteemojen hallinta

- Ääniteemojen hallinta -valintaikkunan avulla voit ottaa käyttöön
  ääniteemoja tai poistaa niitä käytöstä asentamisen ja poistamisen lisäksi.
- Tässä valintaikkunassa on joitakin lisäasetuksia, mukaan lukien:
 - Toista äänet 3D-tilassa: Kun tämä ei ole valittuna, lisäosa toistaa äänet mono-tilassa (aina ääninäytön keskellä) objektin sijainnista riippumatta.
 - Puhu rooli, kuten painike, muokkauskenttä, linkki jne.: Kun tämä ei ole valittuna, NVDA ilmoittaa roolin objekteja aktivoitaessa (oletusarvoisesti roolia ei ilmoiteta).
 - Käytä syntetisaattorin äänenvoimakkuutta: Tämän valintaruudun valitseminen määrittää tämän lisäosan äänisoittimen käyttämään aktiivisen puheäänen voimakkuutta, mikä saa kaikki äänet toistumaan samalla voimakkuudella.
 - Ääniteeman äänenvoimakkuussäädin: Voit vaihtoehtoisesti säätää lisä'osan äänenvoimakkuutta tätä liukusäädintä käyttäen. Jos arvoksi määritetään 0, kaikki äänet mykistetään. Suurin mahdollinen voimakkuus on 100.

### Aktiivisen ääniteeman muokkaaminen

- Kun painat Muokkaa aktiivista ääniteemaa -painiketta, kaikki aktiivisen
  ääniteeman äänet sisältävän listan näyttävä valintaikkuna
  avautuu. Valintaikkunassa on käytettävissä seuraavat vaihtoehdot:
- Muuta valittua: Äänen valitseminen listasta ja tämän painikkeen painaminen
  avaa standardinmukaisen tiedostonavausvalintaikkunan, josta voit valita
  wave-äänitiedoston, joka korvaa valitun äänen. Suorita toimenpide loppuun
  painamalla OK.
- Poista valittu: Tämä poistaa valitun äänen teemasta. Vahvista poisto
  painamalla Kyllä, jonka jälkeen valittu ääni poistetaan.
- Lisää uusi ääni: Tätä painiketta painettaessa avautuu uusi valintaikkuna. Valitse ensimmäisestä yhdistelmäruudusta objektin tyyppi (esim. painike, linkki, välilehti, valikko jne.), johon haluat liittää äänen, ja paina sitten Valitse äänitiedosto -painiketta valitaksesi äänen, jonka haluat liittää valittuun objektityyppiin. Esikuuntele-painikkeella voit halutessasi kuunnella valitsemaasi ääntä, ja OK-painikkeella tallentaa tekemäsi muutokset sekä liittää valitun äänen valitsemaasi objektiin. 
- Sulje: Sulkee valintaikkunan muutoksia tekemättä.

### Uuden ääniteeman luominen

- Mikäli omaat hyvät äänentuotantotaidot, voit käyttää niitä ja luoda oman
ääniteemasi olemassa olevan muokkaamisen sijaan. Luo uusi teema seuraamalla
näitä ohjeita.  - Kerää äänitiedostosi samaan paikkaan ja nimeä ne uudelleen
millä tahansa järkevillä nimillä. Esim. tämän lisäosan oletusääniteemaa
luotaessa äänet ryhmiteltiin vuorovaikutusmallin mukaan,
esim. yhdistelmäruudulla, pudotuspainikkeella ja jakopainikkeella on
kaikilla sama ääni, kun taas valintaruudulla, vaihtopainikkeella ja valikon
kohteena olevalla valintapainikkeella on sama ääni.  - Valitse
lisäosavalikosta Luo uusi ääniteema. - Seuraavaksi avautuu valintaikkuna,
jossa pyydetään joitakin tietoja uudesta ääniteemasta, mukaan lukien:
*	Teeman nimi: Ääniteeman nimi, joka näytetään ääniteemojen
hallinnassa. Nimen on oltava kelvollinen Windows-ympäristössä hyväksytty
kansion nimi.  *	Nimesi: Kirjoita oikea tai lempinimesi.  *	Teeman kuvaus:
Ääniteeman lyhyt kuvaus.  - Siirry seuraavaan vaiheeseen painamalla OK.  -
Seuraavassa vaiheessa näytetään ääniteemamuokkaimen kaltainen
valintaikkuna. Tästä eteenpäin toimenpiteet ovat samoja kuin teeman
muokkaamisessa, joten katso tiedot Aktiivisen ääniteeman muokkaaminen
-kappaleesta.

## Tekijänoikeus

Copyright (c) 2014-2016 Musharraf Omer sekä muut

Vaikka tämä lisäosa aloitettiinkin itsenäisenä projektina, se kehittyi
parannelluksi versioksi Austin Hicksin ja Bryan Smartin kehittämästä
Unspoken-lisäosasta. Suurin osa kehitystyöstä meni ääniteemojen hallintaan,
muokkaamiseen ja luomiseen tarkoitettuihin työkaluihin. Joten suurkiitos
heille näin hienon lisäosan luomisesta sekä jatkokehityksen
mahdollistamisesta.

## Huomautus kolmannen osapuolen äänitiedostoista

Tämän lisäosan oletusääniteema käyttää useista lähteistä kerättyjä ääniä,
tässä erittely niistä: - Unspoken 3D Audio: NVDA:n lisäosa - TWBlue:
Ilmainen ja avoimen lähdekoodin Twitter-asiakasohjelma - Mushy TalkBack:
Vaihtoehtoinen TalkBack-ruudunlukuohjelma Androidille paremmilla äänillä.

## Lisenssi
Tämä lisäosa on GNU General Public License -lisenssin alainen. Katso
lisätietoja **copying**-tiedostosta.

[[!tag dev stable]]

[1]: http://addons.nvda-project.org/files/get.php?file=ath

[2]: http://addons.nvda-project.org/files/get.php?file=ath-dev
