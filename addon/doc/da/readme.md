# Audio Themes #

*   Forfattere: Musharraf Omer og andre
*   download [stabil version][1]
*   Download [udviklingsversion][2]

Denne tilføjelse skaber en virtual audio display, der spiller lyde, når der
fokuseres eller navigeres imellem objekter (f.eks. knapper, links osv..) lyd
vil blive spillet i en placering, der svarer til objektets placering i det
visuelle display.

Tilføjelsesprogrammet lader dig også aktivere, installere, fjerne, redigere,
oprette og distribuere lyd temapakker.

## Brug

Med denne tilføjelse kan du udføre tre særskilte opgaver, herunder
administration af dine installerede lydtemaer, redigere det aktive lydtema,
og oprette et nyt lydtema.

Du kan få adgang til disse funktioner fra menuen tilknyttet
tilføjelsespakken menu, som findes i hovedmenuen NVDA.

### Håndtering af dine lydtemaer

- Dialogen "Håndter lydtemaer" gør det muligt at aktivere eller deaktivere
  lydtemaer, udover installation og fjernelse af lydtemaer.
- I denne dialog er der yderligere indstillinger, herunder:
 - Afspil lyde i 3d-tilstand: Når du fjerner markeringen fra denne checkboks, vil alle lyde afspilles i mono-tilstand (alle lyde afspilles i midten af det aktuelle lyddisplay) uanset placeringen af det pågældende objekt.
 - Sig elementer såsom knap, edit, link, osv.: Når denne checkboks ikke er markeret, vil NVDA annoncérer diverse elementer på skærmen i stedet for at ignorere dette (hvilket er standardadfærden når denne tilføjelsespakke er installeret).
 - Brug talesyntesens lydstyrke: Dette indstiller lydene af det aktuelle lydtema til at spille ved samme lydstyrke, som din aktuelle stemme, således alle lydniveauer forbliver i overensstemmelse.
 - Skyderen til lydstyrke af lydtema: Med denne skyder kan du indstille lydstyrken af dette tilføjelsesprogram. Hvis du indstiller skyderen til 0%, vil lyden fra denne tilføjelsespakke være lydløs. 100% er den højeste lydstyrke.

### Redigerer det aktive lydtema:

- Når du klikker på indstillingen "Rediger aktive lydtema", åbnes en dialog
  med en liste med alle de lyde, der er tilgængelige i det aktuele aktive
  tema. Fra denne dialog kan du:
- Ændre valgte: Ved at vælge en lyd på listen og klikke på denne knap, vil
  der åbnes en standard filåbningsdialog. Vælg en .ogg eller .wav lydfil på
  dit filsystem til at erstatte den valgte lyd og klik på OK for at fuldføre
  processen.
- Fjern valgte: Dette vil fjerne den valgte lyd fra temaet. Du skal klikke
  på "Ja" for at bekræfte fjernelsen, og den valgte lyd vil blive fjernet.
- Tilføj ny lyd: Når du klikker på denne knap, vises en ny dialog. I den første combo boks i den nyåbnede dialog skal du vælge den objekttype, du vil tildele lyden til, f.eks. (Knap, link, fane, menu og så videre), og klik derefter på knappen "Find lydfil" for at vælge den lyd, du vil tildele til den tidligere valgte objekttype. Eventuelt kan du klikke på lyt-knappen for at høre lyden, og endelig ved et klik på OK-knappen anvende ændringerne og tildel den valgte lyd til det valgte objekt.
- Luk: Vil afslutte dialogen uden handling.

### Opret nyt lydtema

- Hvis du er god til lydproduktion, kan du anvende det her og oprette dit
eget lydtema i stedet for at redigere et eksisterende. For at gøre dette kan
du følge disse trin.
- Indsaml dine lydfiler på ét sted, de skal være i ogg eller wave format, og
omdøbe dem til, hvad der giver mening for dig. For eksempel da jeg lavede
standard lydtema for denne tilføjelse, grupperede jeg lyde efter
interaktionsmønstre, f.eks. Combo bokse, drop-down-knappen og split-knappen
kan alle have samme lyd, mens checkboksen, skifteknap og menupunktet kan
have samme lyd.
- Klik på "Opret et nyt lydtema" i tilføjelsespakkens menu.
- Der åbnes en dialog, der beder dig om nogle oplysninger om dit nye
lydtema, herunder:
*	Tema-navn: Navnet på dit tema, der vises i dialogen for håndtering af
lydtemaer. Dette skal være et gyldigt Windows-mappenavn.
*	Dit navn: Indtast dit rigtige navn eller et kaldenavn.
*	Temabeskrivelse: En kort beskrivelse af dit lydtema.
- Klik på OK for at gå til næste trin.
- I næste trin vises en dialog, der ligner 'Håndter Lydtemaer', og fra denne
er processen den samme som temaredigeringsprocessen, så se afsnittet
"Redigering af Aktive lydtema".

## Copyright:

Copyright (c) 2014-2016 Musharraf Omer m.fl.

Selv om denne tilføjelse blev startet som et selvstændigt projekt, udviklet
det sig til at være en forbedret version af den "Unspoken" tilføjelse af
Austin Hicks og Bryan Smart. Størstedelen af udviklingen af denne
tilføjelsespakke gik ind i at skabe værktøjer til at styre, redigere og
oprette lyd temapakker. Så en stor tak til dem for at skabe sådan en
vidunderlig tilføjelse, og gøre det tilgængeligt for os at bygge oven på
deres arbejde.

## Et notat om tredjeparts-lydfiler:

Den ** standard ** lyd tema pakke i denne tilføjelse bruger lyde fra flere
kilder, her er en opdeling af dem:-Unspoken 3D Audio: en tilføjelsespakke
for NVDA - TWBlue: en gratis og open source Twitter-klient - MushyTalkBack:
en alternativ talkback med bedre lyde.

## Licens
Licenseret under GNU General Public License. Se filen **copying** for flere
detaljer.

[[!tag dev stable]]

[1]: https://addons.nvda-project.org/files/get.php?file=ath

[2]: https://addons.nvda-project.org/files/get.php?file=ath-dev
