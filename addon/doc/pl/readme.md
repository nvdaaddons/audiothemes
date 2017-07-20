# Audio Themes #

*   Autorzy: Musharraf Omer i inni
*   pobierz [stabilna wersja][1]
*   pobierz [wersja rozwojowa][2]

Ten dodatek stwarza wirtualny dźwiękowy wyświetlacz, który ottwarza dźwięki
przy nawigacji lub najeżdżaniu na objekt (tak jak przyciski, linki itd...)
dźwięk będzie ottworzony w lokalizacji, która odpowiada lokacji objektu na
monitorze.

Dodatek także umożliwia aktywowanie, instalowanie, usuwanie, edytowanie,
utwarzanie, i dystrybucję pakietów tematów dźwiękowych.

## Używanie

Ten dodatek umożliwia wykonywanie następujących funkcji, włączając w to
instalowanie tematów dźwiękowych, edytowanie aktualie używanego tematu
dźwiękowego, a także stwarzanie nowych tematów dźwiękowych.

Można się dostać do tych funkcji z meni dodatku, znajdujący się w głownym
meni NVDA.

### Zarżądzanie tematami dźwiękowymi

- Okno dialogowe 'zarządzaj tematami dźwiękowymi' umożliwia aktywacje, albo
  deaktywację, w dodatku instalowanie lub usuwanie tematy dźwiękowe.
- W tym oknie dialogowym zdajdują się następujące opcje:
 - Ottwarzaj dźwięk w trybie 3D: Przy odznaczaniu tego pola do wyboru, dodatek będzie ottwarzał dźwięki w trybie mono (Zawsze w środku wyświetlacza dźwiękowego) niezależnie od położenia obiektu.
 - Wymawiaj nazwy kontrolek, takie jak przycisk, pole do edycji, link itd.: Kiedy to pole do wyboru jest odznaczone, NVDA będzie oznajmiał nazwy kontrolek przy przemieszczaniu się nie ignorując je (co jest domyślnym zachowaniem, gdy dodatek jest instalowany).
 - Używaj głośność syntezatora: Zaznaczając to pole do wyboru, ustawi ottwarzacz dźwięków tego dodatku aby używał dźwięk aktywnego głosu, czyniąc wyjście dźwięku wyrównanym przy każdym razie, gdy zmieniasz głośność syntezatora.
 - suwak głośności tematu dźwiękowego: alternatywnie, można zmienić głośność dodatku używając ten suwak. Setting it to 0 will mute all sounds, and 100 is the maximum volume.

### Edycja aktywnego tematu dźwiękowego:

- Gdy klikniesz na przycisk 'edytuj aktywny temat dźwiękowy', będzie otwarty
  dialog, zawierający wszystkie dostępne dźwięki znajdujące się w aktualnie
  aktywnym temacie dźwiękowym. Z tego okna dialogowego można zrobić
  następujące rzeczy:
- Zmień oznaczone: zaznaczając dźwięk z listy o naciskając ten przycisk,
  otwiera standardowy dialog do otwierania pliku, zaznacz plik ogg lub wav z
  systemu plików, aby zamienić zaznaczony dźwięk, i liknij OK, aby zakończyć
  akcję.
- Usuń zaznaczenie: To usunie zaznaczony dźwięk z tematu, kliknij 'tak' aby
  potwierdzić proces usunięcia, a dźwięk zostanie usunięty.
- Dodaj nowy dźwięk: Po klinięciu tego przycisku Nowe okno dialogowe zostanie wyświetlone. Z pierwszego pola kombi w nowootwartym dialogu, zaznacz typ obiektu you, do którego chcesz przydzielić dźwięk do niego, na przykład (przycisk, link, tab, meni i tak dalej), a następnie kliknij przycisk 'przeglądaj' aby zaznaczyć plik dźwiękowy do przydzielonego wcześniej obiektu. Opcjonalnie, możesz kliknąć przycisk posłuchaj, i na koniec kliknij OK, aby zastosować dźwięk do typu obiektu. 
- Zamknij: Zamyka dialog bez zastosowania żadnej akcji.

### Stwarzanie nowego tematu dźwiękowego

- jeżeli masz dobre zdolności dźwiękoprodukcyjne możesz ję tutaj zastosować,
i stworzyć swój własny temat dźwiękowy, nie edytując istniejącego. Aby to
zrobić, śledź te kroki.  - Zachowaj pliki dźwiękowe w jednym miejscu, muszą
być w formacie .wav lub .ogg, i zmień im nazwę na jakąs sensowną. Na
przykład, kiedy tworzyłem swój temat dźwiękowy, pogrupowałem dźwięki według
wzorców interakcyjnych, na przykład, pole kombi, przycisk podzielony, i
rozdzielony przycisk, mogą mieć ten sam dźwięk, pole do wyboru, przycisk
zaznaczania i element do zaznaczania mogą mieć ten sam dźwięk.  - z meni
dodatku, kliknij 'stwórż nowy temat dźwiękowy' - otworzy się dialog, w
którym trzeba będzie podać niektóre informacje o temacie dźwiękowym,
włączając w to: *	nazwę tematu: nazwę tmeatu która będzie wyświetlana w
menedżerze tematów. to musi być poprawna nazwa katalogu w Windows.  *	imię:
Wpisz swoje imię lub ksywe.  *	opis tematu : szczególny opis tematu.  -
Kliknij OK, aby się przenieść na następny krok.  - W następnym kroku,
otworzy się dialog podobny do dialogu 'edytora tematów dźwiękowych', a potem
proces jest taki sam, jak proces edytowania tematu dźwiękowego, czyli,
popatrz na 'sekcje edytowanie tematu dźwiękowego'.

## Prawa autorskie:

Prawa autorskie (c) 2014-2016 Musharraf Omer i inni

Chociaż ten dodatek startował jako niezależny projekt, stał się on jednak
ulepszoną wersją dodatku 'Unspoken' napisanego przez Austina Hicksa i Bryana
Smarta. Rozwijanie dodatku poszło w stronę dodawania funkcji do, edytowania
i tworzenia pakietów tematów dźwiękowych. Czyli, wielkie dzięki dla nich, że
stworzyli ten cudowny dodatek, i możliwość zbudowania go w ramach
istniejącego.

## Uwaga o plikach trzeciej strony:

**Domyślny** pakeit tematów dźwiękowych używa dźwięki z różnych źródeł,
tutaj jest spis źrudeł: - Unspoken 3D Audio: dodatek dla NVDA - TWBlue: A
bespłatni i wolny klient twittera - Mushy TalkBack: alternatywny TAlkBack z
lepszymi dźwiękami.

## Licencja
Licencjonowano pod GNU General Public License. Zobacz plik **copying** dla
więcej informacji.

[[!tag dev stable]]

[1]: https://addons.nvda-project.org/files/get.php?file=ath

[2]: https://addons.nvda-project.org/files/get.php?file=ath-dev
