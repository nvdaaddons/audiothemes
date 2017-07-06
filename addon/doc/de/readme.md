# Sound-Schemata #

*   Autoren: Musharraf Omer und andere
*   Herunterladen der [stabilen Version][1]
*   Herunterladen der [Entwicklerversion][2]

This add-on creates a virtual audio display that plays sounds when focusing
or navigating objects (such as buttons, links etc...) the audio will be
played in a location that corresponds to the object's location in the visual
display.

The add-on also enables you to activate, install, remove, edit, create, and
distribute audio theme packages.

## Bedienung

Mit dieser Erweiterung können Sie drei Dinge erledigen, einschließlich die
Verwaltung, das Anpassen und das Erstellen eines neuen Sound-Schemas.

Diese Funktionen finden Sie im NVDA-Menü unter "Erweiterungen verwalten".

### Sound-Schemata verwalten

- Hiermit können Sie die Sound-Schemata aktivieren/deaktivieren oder
  hinzufügen/entfernen.
- In this dialogue there are some additional options including:
 - Play sounds in 3D mode: When you uncheck this box the add-on will play the sounds in mono mode (always in the centre of the audio display) regardless of the object location.
 - Speak role such as button, edit box , link etc.: When you uncheck this box NVDA will start announcing the role when focusing objects rather than ignoring it (which is the default behaviour when installing this add-on).
 - Use Synthesizer Volume: Checking this box will set the sound player of this add-on to use the active voice sound, thus making all audible output the same as the voice volume when ever you change that volume.
 - Audio Theme Volume Slider: Alternatively you can set the volume for the add-on using this slider. Setting it to 0 will mute all sounds, and 100 is the maximum volume.

### Aktives Sound-Schema bearbeiten

- When you click on the 'Edit the active audio theme' option, a dialogue
  will open with a list containing all the sounds contained in the currently
  active theme. From this dialogue you can:
- Ändern: Wählen Sie einen Sound aus der Liste aus und klicken Sie dann auf
  diesen Schalter, können Sie eine Audio-Datei im Ogg- oder Wave-Format auf
  Ihrem System auswählen, die Sie damit anschließend ersetzen.
- Entfernen: Dies entfernt den ausgewählten Klang aus dem
  Sound-Schema. Klicken Sie auf "Ja", um das Löschen zu bestätigen und die
  Datei zu entfernen.
- Add New Sound: When clicking this button a new dialogue will be shown. From the first combo box in the newly opened dialogue select the object type you want to assign the sound to it, for example (button, link, tab, menu and so on), then click the 'Browse to an audio file' button to select the sound you want to assign for the previously selected object type. Optionally you can click the preview   button to preview the sound, and finally clicking the OK button will apply the changes and assign the selected sound to the selected object. 
- Close: Will  exit the dialogue without performing any action.

### Neues Sound-Schema erstellen

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

Copyright (c) 2014-2016 Musharraf Omer und andere

Dabei war das Projekt von Austin Hicks und Bryan Smart eigentlich für die
NVDA-Erweiterung "Unspoken" geplant und sollte damit ergänzt werden. Es
endete damit, dass die Entwicklung anders verlief und somit wurde das Paket
um die Funktionen zur Verwaltung, Bearbeitung und Erstellung erweitert.
So a big thank you to them for creating such a wonderful add-on,
and making it available for us to build on top of their work.

## Anmerkung zu den Drittanbietern der Audio-Dateien:

In dem Standard-Audioschema in dieser Erweiterung werden Klänge aus mehreren
Quellen verwendet. Nachstehend eine Auflistung:
- Unspoken 3D Audio: Eine Erweiterung für NVDA.
- TWBlue: Ein freier und quelloffener Twitter Client.
- Mushy TalkBack: Ein alternativer Talkback mit besseren Sounds.

## Lizenz
Lizenziert unter der GNU General Public License. Für weitere Informationen
lesen Sie bitte die Datei "Copying".

[[!tag dev stable]]

[1]: https://addons.nvda-project.org/files/get.php?file=ath

[2]: http://addons.nvda-project.org/files/get.php?file=ath-dev
