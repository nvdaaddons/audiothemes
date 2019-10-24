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
- Aggiungi nuovo suono: quando si fa clic su questo pulsante verrà mostrata una nuova finestra di dialogo. Dalla prima casella combinata nella finestra di dialogo appena aperta, selezionare il tipo di oggetto a cui si desidera assegnare il suono, ad esempio (pulsante, collegamento, scheda, menu e così via), quindi fare clic sul pulsante "Cerca un file audio" per selezionare il suono che si desidera assegnare per il tipo di oggetto precedentemente selezionato. Facoltativamente, è possibile fare clic sul pulsante di anteprima per visualizzare l'anteprima del suono e infine fare clic sul pulsante OK per applicare le modifiche e assegnare il suono all'oggetto selezionato. 

- Chiudi: consente di uscire dalla finestra senza eseguire alcuna azione. \N

### Creazione di un nuovo tema audio

- Se hai una buona conoscenza di produzione del suono, puoi metterla in
pratica e creare un tuo tema audio, anziché modificarne uno esistente. Per
farlo puoi seguire questi passaggi. Raccogli i tuoi file audio in un unico
posto, devono essere in formato ogg o wave e rinominali in qualsiasi cosa
abbia senso per te. Ad esempio, quando stavo creando il tema audio
predefinito per questo componente aggiuntivo, ho raggruppato i suoni in base
ai modelli di interazione, ad esempio la casella combinata, il pulsante a
discesa e il pulsante di divisione possono avere tutti lo stesso suono, e
allo stesso modo la casella di controllo, il pulsante di attivazione /
disattivazione e la voce di controllo del menu possono avere lo stesso suono
anch'essi.
Dal menu del componente aggiuntivo fai clic su "Crea un nuovo tema audio":
verrà aperta una finestra di dialogo che ti chiederà alcune informazioni sul
nuovo tema audio, tra cui: * 	 Nome Tema: il nome del tema che verrà
mostrato nel gestore temi audio. deve essere un nome di cartella di Windows
valido. * 	Il tuo nome: inserisci il tuo vero nome o un nickname. * 	
Descrizione tema: una breve descrizione del tuo tema audio. - Fare clic su
OK per passare al passaggio successivo. - Nella fase successiva verrà
mostrato una finestra simile a "Editor temi audio" il processo di modifica è
il medesimo, quindi fai riferimento alla sezione "Modifica del tema audio
attivo".

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

[[!tag dev]]

[1]: https://addons.nvda-project.org/files/get.php?file=ath

[2]: https://addons.nvda-project.org/files/get.php?file=ath-dev
