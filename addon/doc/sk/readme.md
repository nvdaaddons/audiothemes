# Audio Themes #

*   Autory: Musharraf Omer a ďalší
*   stiahnúť [stabilnú verziu][1]
*   stiahnúť [vývojovú verziu][2]

Tento doplnok vytvára virtuálny zvukový displej, ktorý prehráva zvuky pri
zaostrovaní alebo navigácii objektov (ako sú tlačidlá, odkazy atď.), Zvuk sa
prehrá na mieste, ktoré zodpovedá umiestneniu objektu na vizuálnom displeji.

Doplnok tiež umožňuje aktivovať, nainštalovať, odstrániť, upraviť, vytvoriť
a distribuovať balíčky zvukových balíčkov.

## Použitie

Tento doplnok vám umožňuje vykonávať tri rôzne úlohy vrátane správy
nainštalovaných zvukových tém, úpravy aktuálne aktívnej zvukovej témy a
vytvorenia novej zvukovej témy.

K týmto funkciám sa dostanete z ponuky doplnku, ktorá sa nachádza v hlavnej
ponuke NVDA.

### Správa zvukových motívov

- Dialóg „Spravovať zvukové motívy“ umožňuje okrem inštalácie a
  odstraňovania zvukových motívov aj aktiváciu alebo deaktiváciu zvukových
  balíčkov.
- V tomto dialógu sú niektoré ďalšie možnosti vrátane:
 - Prehrať zvuky v režime 3D: Ak zrušíte začiarknutie tohto políčka, doplnok prehrá zvuky v mono režime (vždy v strede zvukového displeja) bez ohľadu na umiestnenie objektu.
 - Vyslovte rolu, ako je tlačidlo, editovacie pole, odkaz atď .: Ak zrušíte začiarknutie tohto políčka, NVDA začne oznamovať rolu pri zaostrovaní na objekty a nebude ich ignorovať (čo je predvolené správanie pri inštalácii tohto doplnku).
 - Použiť hlasitosť syntetizátora: Začiarknutím tohto políčka nastavíte zvukový prehrávač tohto doplnku na používanie aktívneho hlasového zvuku, takže pri každej zmene hlasitosti sa všetok zvukový výstup bude rovnať hlasitosti hlasu.
 - Posuvník hlasitosti zvukových tém: Prípadne môžete nastaviť hlasitosť doplnku pomocou tohto posúvača. Ak nastavíte na 0, stlmia sa všetky zvuky a maximálna hlasitosť je 100.

### Úpravy aktívneho zvukového motívu:

- Po kliknutí na možnosť „Upraviť aktívnu zvukovú tému“ sa otvorí dialógové
  okno so zoznamom všetkých zvukov obsiahnutých v aktuálne aktívnej téme. V
  tomto dialógovom okne môžete:
- Zmeniť vybrané: Výberom zvuku zo zoznamu a kliknutím na toto tlačidlo sa
  otvorí štandardný dialóg otvoreného súboru, vyberte zvukový súbor ogg
  alebo wave zo súborového systému, ktorý nahradí vybraný zvuk, a kliknutím
  na tlačidlo OK dokončite proces.
- Odstrániť vybrané: Týmto odstránite vybraný zvuk z témy, kliknutím na
  „Áno“ potvrďte proces odstránenia a vybratý zvuk bude odstránený.
- Pridať nový zvuk: Po kliknutí na toto tlačidlo sa zobrazí nový dialóg. V prvom rozbaľovacom zozname v novo otvorenom dialógovom okne vyberte typ objektu, ktorý chcete zvuku priradiť, napríklad (tlačidlo, odkaz, karta, ponuka atď.), Potom kliknutím na tlačidlo „Prejsť na zvukový súbor“ vyberte zvuk, ktorý chcete priradiť k predtým vybranému typu objektu. Prípadne môžete kliknutím na tlačidlo náhľadu zobraziť ukážku zvuku a nakoniec kliknutím na tlačidlo OK sa zmeny použijú a priradia vybraný zvuk k vybratému objektu.
- Zatvoriť: Ukončí dialóg bez vykonania akejkoľvek akcie.

### Vytvorenie nového zvukového motívu

- If you have a good sound production skills you can apply them here and
create an audio theme of your own, rather than editing an existing one. To
do this you can follow these steps.  - Collect your audio files in one
place, they must be in ogg or wave format, and rename them to what ever make
sense to you. For example when I was creating the default audio theme for
this add-on, I grouped sounds according to interaction patterns, for
example, the combo box, the drop down button, and the split button can all
have the same sound, while the Check box, The toggle button, and the menu
check item can have the same sound.  - From the add-on menu click 'Create a
new audio theme' - A dialogue will be opened asking you for some information
about your new audio theme, including: *	Theme Name : The name of your theme
which will be shown in the audio themes manager. This must be a valid
windows folder name.  *	Your Name: Enter your real name or a nick name.
*	Theme description : A Brief description about your audio theme.  - Click
OK to move to the next step.  - In the next step a dialogue similar to the
'Audio Themes Editor' will be shown, and from their the process is the same
as the Theme editing process, so refer to 'Editing The Active Audio Theme'
section.

## Autorské práva.

Copyright (c) 2014-2016 Musharraf Omer a ďalší

Although this add-on was started as an independent project, it evolved to be
an enhanced version of the 'Unspoken' add-on by Austin Hicks and Bryan
Smart. The majority of this add-on's development went into creating the
tools to manage, edit and create audio theme packages. So a big thank you to
them for creating such a wonderful add-on, and making it available for us to
build on top of their work.

## Poznámky k zvukovým súborom tretích strán:

Balíček tematických zvukov **Predvolené** v tomto doplnku používa zvuky z
niekoľkých zdrojov. Tu je rozpis podľa nich: - Nevyslovené 3D audio: Doplnok
pre NVDA - TWBlue: Bezplatný a otvorený klient Twitter - Mushy TalkBack:
Alternatívny spätný hovor s lepšími zvukmi.

## Licencie
Licencované na základe GNU General Public License. Ďalšie podrobnosti
nájdete v súbore **copying**.

[[!tag dev]]

[1]: https://addons.nvda-project.org/files/get.php?file=ath

[2]: https://addons.nvda-project.org/files/get.php?file=ath-dev
