# Audio Themes #

*   Autorzy: Musharraf Omer i inni
*   pobierz [wersja stabilna][1]
*   pobierz [wersja rozwojowa][2]

Ten dodatek tworzy wirtualny dźwiękowy wyświetlacz, który odtwarza dźwięki
podczas nawigacji lub najeżdżania na obiekty, takie jak przyciski, linki
itd. Dźwięk będzie ottworzony w lokalizacji, która odpowiada lokalizacji
objektu na ekranie.

Dodatek umożliwia także aktywowanie, instalowanie, usuwanie, edytowanie,
tworzenie i dystrybucję pakietów tematów dźwiękowych.

## Użycie

Ten dodatek umożliwia wykonywanie następujących czynności: instalowanie
tematów dźwiękowych, edytowanie aktualnie używanego tematu dźwiękowego oraz
tworzenie nowych tematów dźwiękowych.

Funkcje te są dostępne w menu dodatku, które znajduje się w głównym menu
NVDA.

### Zarządzanie tematami dźwiękowymi

- Okno dialogowe "zarządzaj tematami dźwiękowymi" umożliwia aktywację i
  dezaktywację oraz instalowanie i usuwanie tematów dźwiękowych.
- W tym oknie dialogowym znajdują się następujące opcje:
 - Odtwarzaj dźwięk w trybie 3D: Po zaznaczeniu tego pola wyboru, dodatek będzie odtwarzał dźwięki w trybie mono (Zawsze na środku wyświetlacza dźwiękowego) niezależnie od położenia obiektu.
 - Wymawiaj nazwy kontrolek, takich jak przycisk, pole edycyjne, link itd.: Kiedy to pole wyboru jest odznaczone, NVDA będzie oznajmiać nazwy kontrolek przy przemieszczaniu się nie ignorując ich (co jest domyślnym zachowaniem, gdy dodatek jest instalowany).
 - Używaj głośności syntezatora: Po zaznaczeniu tego pola wyboru, ottwarzacz dźwięków dodatku będzie używał dźwięku aktywnego głosu. Dzięki temu, dźwięki dodatku będą miały taką samą głośność jak aktywny głos, przy każdej zmianie głośności syntezatora.
 - suwak głośności tematu dźwiękowego: alternatywnie, można zmienić głośność dodatku używając tego suwaka. Ustawienie go na 0 wycisza wszystkie dźwięki dodatku, a 100 to maksymalna głośność.

### Edycja aktywnego tematu dźwiękowego:

- Gdy klikniesz na przycisk "edytuj aktywny temat dźwiękowy", otworzy się
  okno dialogowe, zawierające wszystkie dostępne dźwięki, które znajdują się
  w aktualnie aktywnym temacie dźwiękowym. Można tam wykonać następujące
  czynności:
- Zmień oznaczone: po zaznaczeniu dźwięku z listy i naciśnięciu tego
  przycisku, otworzy się standardowy dialog otwierania pliku. Zaznacz plik
  ogg lub wav z systemu plików, aby zamienić zaznaczony dźwięk. Kliknij OK,
  aby zakończyć akcję.
- Usuń zaznaczenie: usunie zaznaczony dźwięk z tematu. Kliknij "tak", aby
  potwierdzić proces usunięcia. Dźwięk zostanie usunięty.
- Dodaj nowy dźwięk: Po kliknięciu tego przycisku zostanie wyświetlone nowe okno dialogowe. W pierwszym polu kombi tego dialogu zaznacz typ obiektu do którego chcesz przypisać dźwięk, na przykład przycisk, link, tab, menu itd. Następnie kliknij przycisk "przeglądaj", aby wybrać plik dźwiękowy do przypisanego wcześniej obiektu. Opcjonalnie, możesz kliknąć przycisk posłuchaj. Kliknij OK, aby zastosować dźwięk do typu obiektu. 
- Zamknij: Zamyka dialog bez zastosowania żadnej akcji.

### Tworzenie nowego tematu dźwiękowego

- Jeżeli masz zdolności w zakresie produkcji dźwięku, możesz je tutaj
wykorzystać i stworzyć swój własny temat dźwiękowy, zamiast edytować już
istniejący. Aby to zrobić, wykonaj następujące kroki.  - Zbierz pliki
dźwiękowe w jednym miejscu, (muszą być w formacie .wav lub .ogg) i zmień im
nazwy tak, aby wiedzieć, do czego ma być użyty każdy z nich. Kiedy tworzyłem
domyślny temat dźwiękowy dla tego dodatku, pogrupowałem dźwięki według
wzorców interakcyjnych. na przykład, pole kombi, przycisk podzielony i
przycisk rozdzielony mają jeden dźwięk, natomiast pole wyboru, przycisk
przełączania i element zaznaczania mają kolejny dźwięk.  - Z menu dodatku,
wybierz "stwórz nowy temat dźwiękowy' - otworzy się dialog, w którym trzeba
będzie podać kilka informacji o nowym temacie dźwiękowym, takich jak:
*	Nazwa tematu: nazwa tematu która będzie wyświetlana w menedżerze tematów.
Musi to być poprawna nazwa katalogu w Windows.  *	Twoje imię: Wpisz swoje
prawdziwe imię lub pseudonim.  *	Opis tematu : krótki opis tematu.  -
Kliknij OK, aby przejść do następnego kroku.  - W następnym kroku, pojawi
się dialog podobny do dialogu 'edytora tematów dźwiękowych', dalsza część
procesu jest taka sama jak proces edytowania tematu dźwiękowego. Zajrzyj do
sekcji 'edytowanie tematu dźwiękowego'.

## Prawa autorskie:

Prawa autorskie (c) 2014-2016 Musharraf Omer i inni

Chociaż ten dodatek pierwotnie był niezależnym projektem, z czasem stał się
ulepszoną wersją dodatku 'Unspoken' napisanego przez Austina Hicksa i Bryana
Smarta. Zaczęto skupiać się przede wszystkim na dodawaniu funkcji do
edytowania i tworzenia pakietów tematów dźwiękowych. Bardzo dziękujemy
pierwszym twórcom tego wspaniałego dodatku za to, że powierzyli nam efekt
swojej pracy i jego dalszy rozwój.

## Uwaga na temat plików dźwiękowych trzeciej strony:

**Domyślny** pakiet tematów dźwiękowych tego dodatku zawiera dźwięki
pochodzące z różnych źródeł, Poniżej spis źrudeł: - Unspoken 3D Audio:
dodatek dla NVDA - TWBlue: Bespłatny i wolny klient twittera - Mushy
TalkBack: alternatywny TAlkBack z lepszymi dźwiękami.

## Licencja
Licencjonowano na warunkach GNU General Public License. Więcej informacji w
pliku **copying** .

[[!tag dev stable]]

[1]: https://addons.nvda-project.org/files/get.php?file=ath

[2]: https://addons.nvda-project.org/files/get.php?file=ath-dev
