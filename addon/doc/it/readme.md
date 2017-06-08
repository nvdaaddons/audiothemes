# Audio Themes #

*   Autori: Musharraf Omer e altri
*   download [Versione stabile][1]
*   download [Versione in sviluppo][2]

Questo componente aggiuntivo crea un display audio virtuale che riproduce i
suoni durante lo spostamento del focus o la navigazione tra oggetti (come
pulsanti, link, ecc...), l'audio verrà riprodotto cercando di far coincidere
la posizione del suono con quella visuale dell'oggetto.

Il componente consente inoltre di attivare, installare, rimuovere,
modificare, creare e distribuire pacchetti di temi audio.

## Utilizzo

Questo add-on consente di eseguire tre operazioni distinte, tra cui la
gestione dei temi audio installati, modificare il tema audio attivo, e la
creazione di un nuovo tema audio. 

è possibile accedere a queste funzioni attraverso il menu del relativo
componente aggiuntivo situato al menu principale di NVDA.

### Gestione dei propri temi audio

- La finestra di dialogo gestione audio temi consente di attivare o
  disattivare i temi, oltre a poterli installare o rimuovere.
- In questa finestra di dialogo ci sono ulteriori opzioni, tra cui:
 - riproduci suoni in modalità 3d: se si deseleziona la casella di controllo, i suoni verranno riprodotti in mono, sempre al centro a prescindere dalla posizione dell'oggetto.
 - Annuncia ruoli quali pulsanti, campi editazione, link, etc.: deselezionando questa opzione NVDA annuncerà la presenza di questi controlli, leggendone il ruolo, quando viene focalizzato un oggetto. Il comportamento predefinito è di ignorare i ruoli di questi controlli quando il componente aggiuntivo viene installato.
 - Usa il volume del sintetizzatore: selezionando la casella di controllo si imposterà la riproduzione dei suoni di questo componente aggiuntivo al medesimo volume della sintesi vocale in uso, cosicché modificando il volume della voce verrà modificato anche il volume dei suoni dell'addon.
 - Volume di Audio Theme: in alternativa è possibile controllare il volume con questo cursore d'avanzamento, nel caso lo si imposti a 0 non verrà più eseguito alcun suono da parte di questo componente aggiuntivo.

### Modifica del tema audio attivo

- When you click on the 'Edit the active audio theme' option, a dialogue
  will open with a list containing all the sounds contained in the currently
  active theme. From this dialogue you can:
- Change Selected: Selecting a sound from the list and clicking this button,
  will open a standard open file dialogue, select an ogg or wave audio file
  from your file system to replace the selected sound, and click OK to
  complete the process.
- Remove Selected: This will remove the selected sound from the theme, click
  'Yes' to confirm the removal process, and the selected sound will be
  removed.
- Add New Sound: When clicking this button a new dialogue will be shown. From the first combo box in the newly opened dialogue select the object type you want to assign the sound to it, for example (button, link, tab, menu and so on), then click the 'Browse to an audio file' button to select the sound you want to assign for the previously selected object type. Optionally you can click the preview   button to preview the sound, and finally clicking the OK button will apply the changes and assign the selected sound to the selected object. 
- Close: Will  exit the dialogue without performing any action.

### Creazione di un nuovo tema audio

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

## Copyright:

Copyright (c) 2014-2016 Musharraf Omer e Altri

Sebbene questo componente aggiuntivo sia iniziato come un progetto
indipendente, esso si è evoluto in una versione avanzata del componente
aggiuntivo 'Unspoken', di Austin Hicks e Bryan Smart. Un sentito
ringraziamento a loro per aver creato un componente aggiuntivo così bello e
utile, ed aver permesso quindi di poter costruirci un'interfaccia adatta
allo scopo.

## Nota sui file audio di terze parti

Il tema audio predefinito di questo componente aggiuntivo utilizza suoni
provenienti da più fonti. Ecco un breve riassunto:
 - Unspoken 3D Audio: An add-on for NVDA - TWBlue: A free and open source
twitter client - Mushy TalkBack: An alternative talkback with better sounds.

## Licenza
Realizzato con Licenza GNU General Public License. Si veda il file
**copying**  per ulteriori informazioni

[[!tag dev stable]]

[1]: https://addons.nvda-project.org/files/get.php?file=ath

[2]: https://addons.nvda-project.org/files/get.php?file=ath-dev
