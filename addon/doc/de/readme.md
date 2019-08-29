# Audio-Schema #

*   Autoren: Musharraf Omer und andere
*   [Stabile Version herunterladen][1]
*   [Entwicklerversion herunterladen][2]

Diese Erweiterung erstellt ein virtuelles akustisches Bild der auf dem
Bildschirm sichtbaren Objekte. Es werden Geräusche beim Fokussieren von oder
Navigieren zwischen Objekten (z.B. Schaltflächen, Links usw.)
wiedergegeben. Die Audioausgabe erfolgt bei Nutzung von Kopfhörern oder 5.1
Soundsystemen an einem Ort, der der Position des Objekts in der visuellen
Anzeige entspricht.

Das Add-On ermöglicht es Ihnen außerdem, Audio-schemenpakete zu aktivieren,
zu installieren, zu entfernen, zu bearbeiten, zu erstellen und zu teilen.

## Bedienung

Mit dieser Erweiterung können Sie drei Dinge erledigen, einschließlich die
Verwaltung, das Anpassen und das Erstellen eines neuen Audio-Schemas.

Diese Funktionen finden Sie im NVDA-Menü unter "Erweiterungen verwalten".

### Sound-Schemata verwalten

- Hiermit können Sie die Sound-Schemata aktivieren/deaktivieren oder
  hinzufügen/entfernen.
In diesem Dialog gibt es einige zusätzliche Optionen, wie z.B.:
 - Sound im 3D-Modus abspielen: Wenn Sie dieses Kontrollkästchen deaktivieren, werden die Sounds im Monomodus (immer in der Mitte der Audioanzeige) abgespielt, unabhängig von der Position des Objekts auf dem Bildschirm.
 - Rolle der Objekte ansagen z.B. Schalter, Eingabefeld, Link etc.: Wenn Sie dieses Kontrollkästchen deaktivieren, beginnt NVDA die Rolle beim Fokussieren von Objekten auszusprechen, anstatt sie zu ignorieren (Standardverhalten bei der Installation dieses Add-ons).
 - Sprachausgabenlautstärke verwenden: Wenn Sie dieses Kontrollkästchen aktivieren, wird der Soundplayer dieser Erweiterung so eingestellt, dass alle hörbaren Audioausgaben aus der Erweiterung mit der aktuellen Lautstärke der Sprachausgabe übereinstimmen.
 - Lautstärke-Regler für Audioschema: Alternativ können Sie die Lautstärke für die Audioausgaben der Erweiterung mit diesem Schieberegler einstellen. Wenn Sie ihn auf 0 setzen, werden alle Töne stumm geschaltet, und 100 ist die maximale Lautstärke.

### Aktives Sound-Schemata bearbeiten:

- Wenn Sie auf die Option"Aktuelles Audio-Schema bearbeiten" klicken, öffnet
  sich ein Dialog mit einer Liste aller Sounds, die im gerade aktiven Schema
  enthalten sind. Aus diesem Dialog heraus können Sie folgendes tun:
- Ändern: Wählen Sie einen Sound aus der Liste aus und klicken Sie dann auf
  diesen Schalter, so können Sie eine Audio-Datei im Ogg- oder Wave-Format
  auf Ihrem System auswählen. Den Sound können Sie mit der ausgewählten
  Datei ersetzen.
- Entfernen: Dies entfernt den ausgewählten Klang aus dem
  Sound-Schemata. Klicken Sie auf "Ja", um das Löschen zu bestätigen und die
  Datei zu entfernen.
Neuen Sound hinzufügen: Wenn Sie auf diese Schaltfläche klicken, wird ein neuer Dialog angezeigt. Wählen Sie aus der ersten Combobox im neu geöffneten Dialog den Objekttyp aus, dem Sie den Sound zuweisen möchten, z.B. (Schalter, Link, Registerkarte, Menü usw.), und klicken Sie dann auf die Schaltfläche"Audiodatei suchen", um den gewünschten Sound auszuwählen. Optional können Sie auf die Vorschau-Schaltfläche klicken, um den Sound in der Vorschau wiederzugeben. Schließlich auf die Schaltfläche OK klicken, um die Änderungen zu übernehmen und den ausgewählten Sound dem ausgewählten Objekt zuzuordnen. 
Schließen: Beendet den Dialog, ohne eine Aktion auszuführen.

### Neues Sound-Schema erstellen

- Wenn Sie über gute Kenntnisse in der Tonproduktion verfügen, können Sie
diese hier anwenden und ein eigenes Audio-Schemata erstellen anstatt ein
bestehendes zu bearbeiten. Führen Sie dazu die folgenden Schritte aus.  -
Sammeln Sie Ihre Audiodateien an einem Ort. Sie müssen im Ogg- oder
Wave-Format vorliegen.  - Benennen Sie die Dateien nach ihren Wünschen
um. Zum Beispiel, als ich das Standard-Audiodesign für dieses Add-On
erstellt habe, habe ich die Sounds nach Interaktionsmustern gruppiert,
z.B. das Kombinationsfeld, die Dropdown-Schaltfläche und der Split-Button
hatten den gleichen Sound. Das gleiche mit dem Kontrollkästchen, dem
Untermenü-Schalter und dem Menüeintrag.  - Klicken Sie im Add-on-Menü auf
'Neues Audio-Schemata erstellen'.  - Es öffnet sich ein Dialog, in dem Sie
nach Informationen zu Ihrem neuen Audio-Schemata gefragt werden, z.B.:
*	Name Ihres Schematas: Der Name Ihres Schematas, der im
Audio-Schemata-Manager angezeigt wird. Dies muss ein gültiger
Windows-Ordnername sein.  *	Ihr Name: Geben Sie Ihren richtigen Namen oder
einen Spitznamen ein.  *	Beschreibung Ihres Schematas: Eine Kurzbeschreibung
über Ihr Audio-Schemata).  - Klicken Sie auf OK, um zum nächsten Schritt zu
gelangen.  - Im nächsten Schritt wird ein Dialog angezeigt, der ähnlich dem
'Audioschemataeditor' ist. Von dort aus ist der Prozess derselbe wie der
Prozess beim Bearbeiten eines Schematas, siehe Abschnitt 'Bearbeiten des
aktiven Audio-Schematas'.

## Copyright:

Copyright (c) 2014-2016 Musharraf Omer und andere

Dabei war das Projekt von Austin Hicks und Bryan Smart eigentlich für die
NVDA-Erweiterung "Unspoken" geplant und sollte damit ergänzt werden. Es
endete damit, dass die Entwicklung anders verlief und somit wurde das Paket
um die Funktionen zur Verwaltung, Bearbeitung und Erstellung erweitert.
So a big thank you to them for creating such a wonderful add-on, and making
it available for us to build on top of their work.

## Anmerkung zu den Drittanbietern der Audio-Dateien:

In dem **Standard-Audioschemata** dieser Erweiterung werden Klänge aus
mehreren Quellen verwendet. Nachstehend eine Auflistung:- Unspoken 3D Audio:
Eine Erweiterung für NVDA.- TWBlue: Ein freier und quelloffener Twitter
Client.- Mushy TalkBack: Ein alternativer Talkback mit besseren Sounds.

## Lizenz
Lizenziert unter der GNU General Public License. Für weitere Informationen
lesen Sie bitte die Datei "Copying".

[[!tag dev]]

[1]: https://addons.nvda-project.org/files/get.php?file=ath

[2]: https://addons.nvda-project.org/files/get.php?file=ath-dev
