# Hangtémák #

*   Készítők: Musharraf Omer és mások
*   [stabil verzió][1] letöltése
*   [Fejlesztői verzió][2] letöltése

Ez a kiegészítő  különböző hangok lejátszásával jelzi a fókuszba kerülő elem
típusát (gomb, link, stb). A hang a vizuális megjelenítésnek megfelelően
szólal meg, így hallható, hogy az adott elem hol helyezkedik el a képernyőn.

A kiegészítő  lehetővé teszi hangtéma csomagok  aktiválását, telepítését,
eltávolítását, szerkesztését, létrehozását és terjesztését.

## Használat

Ezzel a kiegészítővel kezelheti a telepített hangtémáit, szerkesztheti
azokat, valamint újakat hozhat létre.

A kiegészítő menüje az NVDA főmenüjében található, onnan érheti el.

### Hangtémák kezelése

- Ezen a párbeszédpanelen váltogathat a különböző hangtémák közt, ill. itt
  telepítheti és el is távolíthatja azokat.
- További opciók:
 - 3D mód: Ha nincs bejelölve,akkor az NVDA a hangokat monó módban játssza le, mind egységesen középről szól, nem követi az egyes elemek elhelyezkedését a képernyőn.
 - hangjelzés helyett beszéd mint gomb, szerkesztőmező, hivatkozás stb.: Ha be van jelölve, az NVDA bemondja az egyes képernyőelemek nevét, ha nincs bejelölve,akkor az NVDA az egyes hangtémákban beállított hangjelzésekkel jelzi a képernyőelemeket. Ez utóbbi az alapértelmezett viselkedés.
 - használja a beszédszintetizátor hangerejét: Bejelölt állapotban a kiegészítő hangjai az aktív beszédszintetizátor hangerejéhez igazodnak, és követik a változásait.
 - Hangtéma hangerő csúszka: Ezzel a csúszkával beállíthatja a kiegészítő hangerejét az NVDA beszédszintetizátoraitól függetlenül. A 0 érték elnémítja az összes hangot, 100 a maximális hangerő.

### Aktív hangtéma szerkesztése

- Ezen a párbeszédpanelen megjelenik az aktív hangtéma hangjainak listája.
- Szerkesztés: A kiválasztott hangot lecserélheti egy másikra. Egy
  szabványos fájlmegnyitás párbeszédpanelen keresztül kiválaszthat egy másik
  ogg vagy wav fájlt a számítógépéről.
- Eltávolítás: Eltávolítja a kijelölt hangot a listáról. Az "Igen" gomb
  aktiválásával a folyamat véglegesíthető, és a kiválasztott hang
  eltávolításra kerül.
- Új hang hozzáadása: A gomb lenyomására egy párbeszédpanel jelenik meg. Az első kombinált listamezőben válassza ki azt az elemet,amihez hangot szeretne hozzárendelni (pl. gomb, hivatkozás, fül, menü, stb.), majd kattintson a 'Tallózás' gombra a kívánt hangfájl kiválasztásához. A 'Meghallgat' gombra kattintva ellenőrizheti, hogy a kívánt hangot választotta-e ki. Az OK gomb lenyomásával jóváhagyhatja a hozzárendelést.
- Bezárás: Bezárja a párbeszédpanelt.

### Új hangtéma létrehozása

- Ha Önnek jó képességei vannak hangtervezésre, itt megvalósíthatja és
készíthet magának hangtémát ahelyett, hogy egy létezőt szerkesztene
át. Ehhez kövesse az alábbi lépéseket.  - Gyűjtse össze a hangfájljait egy
helyre, legyenek ogg vagy wave formátumban, majd nevezze át őket
értelemszerűen. Például, amikor én ezt a hangtémát elkészítettem ehhez a
bővítményhez, a hangokat a vezérlés sémája szerint csoportosítottam, így
például a kombinált listamező, az osztott gomb és a körvonalgomb ugyanazt a
hangot kapta, míg a jelölőnégyzetnek, a bejelölhető menüelemnek és a
kapcsológombnak ugyanaz a hangja.  - Az NVDA/hangtémák menüben válassza az
új hangtéma készítése menüpontot, egy párbeszédpanel fog megnyílni. Ez
mutatja a hangtémák kezelőjét. Itt egy érvényes windows mappanevet kell
megadni.  *	Az Ön neve szerkesztőmezőbe írja be a saját valódi nevét vagy
egy nicknevet.  *	Leírás: itt lehet megadni egy rövid leírást a
hangtémához.  - Kattintson az ok gombra a folytatáshoz.  - A következő
lépésben egy hasonló párbeszédpanel, a hangtéma-szerkesztő jelenik meg, és
ettől kezdve a tennivaló ugyanaz, mint a hangtéma szerkesztésekor, a további
információkat a hangtéma szerkesztése szakaszban találja. 

## Copyright:

Copyright (c) 2014-2016 Musharraf Omer és mások

Annak ellenére, hogy ennek a bővítménynek az elkészítése egy független
projektként indult, hallgatólagosan Austin Hicks és Bryan Smart munkájának
kiterjesztett verziójaként bocsátották ki. Ennek a bővítménynek a
fejlesztésekor a munka oroszlánrészét azoknak az eszközöknek a fejlesztésére
fordították, amelyek hangtéma-csomagok készítésére, szerkesztésére és
kezelésére vonatkoznak. Nagy köszönet illeti őket ennek a nagyszerű
bővítménynek az elkészítéséért, valamint azért, hogy munkájukat a számunkra
hozzáférhetővé tették, és befejezhettük az ő munkájukat.

## Megjegyzés a külső forrásból származó audio fájlokhoz:

Az alapértelmezett hangcsomag az alábbi szoftverekből származó fájlokat
használja: - Unspoken 3D Audio: EgyNVDA kiegészítő;- TWBlue: Ingyenes és
nyílt forráskodú Twitter kliens;- Mushy TalkBack: Alternatív TalkBack, jobb
hangokkal.

## Licenc
GNU General Public License licensz. Bővebb információkért olvassa el a
**copying** fájlt.

[[!tag dev stable]]

[1]: http://addons.nvda-project.org/files/get.php?file=ath

[2]: http://addons.nvda-project.org/files/get.php?file=ath-dev
