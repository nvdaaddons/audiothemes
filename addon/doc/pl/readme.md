# Audio Themes #

*   Autorzy: Musharraf Omer i inni
*   pobierz [stabilna wersja][1]
*   pobierz [wersja rozwojowa][2]

Ten dodatek tworzy wirtualny dźwiękowy wyświetlacz, który odtwarza dźwięki
przy nawigacji lub najeżdżaniu na objekt (tak jak przyciski, linki itd...)
dźwięk będzie ottworzony w lokalizacji, która odpowiada lokacji objektu na
monitorze.

Dodatek umożliwia także aktywowanie, instalowanie, usuwanie, edytowanie,
tworzenie, i dystrybucję pakietów tematów dźwiękowych.

## Używanie

Ten dodatek umożliwia wykonywanie następujących czynności, włączając w to
instalowanie tematów dźwiękowych, edytowanie aktualnie używanego tematu
dźwiękowego, a także tworzenie nowych tematów dźwiękowych.

Można się dostać do tych funkcji z meni dodatku, znajdującego się w głownym
meni NVDA.

### Zarżądzanie tematami dźwiękowymi

- Okno dialogowe 'zarządzaj tematami dźwiękowymi' umożliwia aktywację, albo
  dezaktywację, oraz dodatku instalowanie lub usuwanie tematów dźwiękowych.
- W tym oknie dialogowym znajdują się następujące opcje:
 - Odtwarzaj dźwięk w trybie 3D: Przy odznaczaniu tego pola wyboru, dodatek będzie odtwarzał dźwięki w trybie mono (Zawsze na środku wyświetlacza dźwiękowego) niezależnie od położenia obiektu.
 - Wymawiaj nazwy kontrolek, takie jak przycisk, pole do edycji, link itd.: Kiedy to pole do wyboru jest odznaczone, NVDA będzie oznajmiał nazwy kontrolek przy przemieszczaniu się nie ignorując ję (co jest domyślnym zachowaniem, gdy dodatek jest instalowany).
 - Używaj głośność syntezatora: Zaznaczając to pole do wyboru, ustawi ottwarzacz dźwięków tego dodatku aby używał dźwięk aktywnego głosu, czyniąc wyjście dźwięku wyrównanym przy każdym razie, gdy zmieniasz głośność syntezatora.
 - suwak głośności tematu dźwiękowego: alternatywnie, można zmienić głośność dodatku używając ten suwak. Setting it to 0 will mute all sounds, and 100 is the maximum volume.

### Edycja aktywnego tematu dźwiękowego:

- Gdy klikniesz na przycisk 'edytuj aktywny temat dźwiękowy', zosanie
  otwarte okno dialogowe, zawierające wszystkie dostępne dźwięki znajdujące
  się w aktualnie aktywnym temacie dźwiękowym. Z tego okna dialogowego można
  wykonać następujące czynności:
- Zmień oznaczone: zaznaczając dźwięk z listy naciśnięcie tego przycisku,
  otwiera standardowy dialog do otwierania pliku, zaznacz plik ogg lub wav z
  systemu plików, aby zamienić zaznaczony dźwięk, kliknij OK, aby zakończyć
  akcję.
- Usuń zaznaczenie: To usunie zaznaczony dźwięk z tematu, kliknij 'tak' aby
  potwierdzić proces usunięcia, a dźwięk zostanie usunięty.
- Dodaj nowy dźwięk: Po kliknięciu tego przycisku zostanie wyświetlone nowe okno dialogowe. Z pierwszego pola kombi w nowootwartym dialogu, zaznacz typ obiektu do którego chcesz przypisać dźwięk, na przykład (przycisk, link, tab, meni itd.), a następnie kliknij przycisk 'przeglądaj' aby wybrać plik dźwiękowy do przypisanego wcześniej obiektu. Opcjonalnie, możesz kliknąć przycisk posłuchaj, i na koniec kliknij OK, aby zastosować dźwięk do typu obiektu. 
- Zamknij: Zamyka dialog bez zastosowania żadnej akcji.

### Tworzenie nowego tematu dźwiękowego

- Jeżeli masz dobre zdolności do produkcji dźwięku możesz ję tutaj
zastosować, i stworzyć swój własny temat dźwiękowy, nie edytując
istniejącego. Aby to zrobić, śledź następujące kroki.  - Zachowaj pliki
dźwiękowe w jednym miejscu, muszą być w formacie .wav lub .ogg, i zmień im
nazwę na jakąs sensowną. Na przykład, tworząc włąsny temat dźwiękowy,
pogrupowałem dźwięki według wzorców interakcyjnych, na przykład, pole kombi,
przycisk podzielony, i rozdzielony przycisk, mogą mieć ten sam dźwięk, pole
do wyboru, przycisk zaznaczania i element do zaznaczania mogą mieć ten sam
dźwięk.  - z meni dodatku, kliknij 'stwórż nowy temat dźwiękowy' - otworzy
się dialog, w którym trzeba będzie podać niektóre informacje o temacie
dźwiękowym, włączając w to: *	nazwę tematu: nazwę tematu która będzie
wyświetlana w menedżerze tematów. to musi być poprawna nazwa katalogu w
Windows.  *	imię: Wpisz swoje imię lub ksywe.  *	opis tematu : szczególny
opis tematu.  - Kliknij OK, aby się przenieść na następny krok.  - W
następnym kroku, otworzy się dialog podobny do dialogu 'edytora tematów
dźwiękowych', a potem proces jest taki sam, jak proces edytowania tematu
dźwiękowego, czyli, popatrz na 'sekcje edytowanie tematu dźwiękowego'.

## Prawa autorskie:

Prawa autorskie (c) 2014-2016 Musharraf Omer i inni

Chociaż ten dodatek startował jako niezależny projekt, stał się on jednak
ulepszoną wersją dodatku 'Unspoken' napisanego przez Austina Hicksa i Bryana
Smarta. Rozwijanie dodatku poszło w stronę dodawania funkcji do, edytowania
i tworzenia pakietów tematów dźwiękowych. Czyli, wielkie dzięki dla nich, że
stworzyli ten cudowny dodatek, i możliwość zbudowania go w ramach
istniejącego.

## Uwaga o plikach trzeciej strony:

**Domyślny** pakiet tematów dźwiękowych używa dźwięki z różnych źródeł,
tutaj jest spis źrudeł: - Unspoken 3D Audio: dodatek dla NVDA - TWBlue: A
bespłatni i wolny klient twittera - Mushy TalkBack: alternatywny TAlkBack z
lepszymi dźwiękami.

## Licencja
Licencjonowano pod GNU General Public License. Zobacz plik **copying** dla
więcej informacji.

[[!tag dev stable]]

[1]: https://addons.nvda-project.org/files/get.php?file=ath

[2]: https://addons.nvda-project.org/files/get.php?file=ath-dev
