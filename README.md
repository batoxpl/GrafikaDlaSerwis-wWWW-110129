# Optymalizacja Windows 10 i nie tylko

Dzień dobry, jest to mój pierwszy markdown na Githubie. W tym dokumencie przedstawię wam w jaki sposób **optymalizuję pracę systemu Windows oraz programów (np. przeglądarki)**, z których większość ludzi korzysta na co dzień. Wiele z tych rzeczy **korzystam przynajmniej kilka lat** i często instaluje bądź konfiguruję je również na cudzych systemach. Do tej pory nie zdarzyło mi się, aby wykorzystane sposoby powodowały problemy, ani powodowały wysyp systemu. 

Będę wykorzystywać poniżej stworzoną **5-stopniową skalę,** która będzie określać następujące cechy **w mojej opinii**:

 - Trudność obsługi (Od laika do poziomu zaawansowanego)
 -  Stopień konfiguracji (Od praktycznie żadnej do pełnego wachlarzu możliwości)
 - Konfliktowość, czyli możliwość wpłynięcia niekorzystnie na dane środowisko lub wymagana częsta reakcja użytkownika (Od poziomu bardzo niskiego do poziomu bardzo wysokiego)
 
 - 🔵⚪️⚪️⚪️⚪️ 
 - 🔵🔵⚪️⚪️⚪️ 
 - 🔵🔵🔵⚪️⚪️ 
 - 🔵🔵🔵🔵⚪️
 -  🔵🔵🔵🔵🔵

oraz sytuacyjna ocena, gdy naprawdę nie ma co się stać:

 - ⚪️⚪️⚪️⚪️⚪️

Do tego przedstawię również krótki opis częstotliwości korzystania z programu oraz ogólne zagadnienia z tym związane. **Skalę traktuję w sytuacji - robię to  z głową i nie klikam wszystko co popadnie.**

> **Dodatkowa informacja:** Nie biorę odpowiedzialności za złe skonfigurowane programy oraz wyrządzone szkody jakie mogą spowodować niżej wymienione programy. U mnie działa, u Ciebie nie musi. Jak czegoś nie wiesz, to poczytaj na internecie - jest tego pełno.

 Zapraszam do lektury :)

## ShutUp10++

Link: https://www.oo-software.com/en/shutup10

 1. Trudność obsługi: 🔵🔵⚪️⚪️⚪️
 2.  Stopień Konfiguracji: 🔵🔵🔵⚪️⚪️
 3. Konfliktowość: 🔵🔵⚪️⚪️⚪️
 4. Częstotliwość korzystania: Zazwyczaj co aktualizację systemu 
 5. Zrzut ekranu programu:

![enter image description here](https://www.oo-software.com/oocontent/uploads/tour/oosu10-en/01.png)

Na początek ShutUp10++ czyli **mój Starter Pack** po zainstalowaniu świeżego Windowsa. Mały programik typu **włącz, skonfiguruj i zapomnij**  który potrafi zrobić wiele i zadba o nasze bezpieczeństwo i optymalizację systemu. **Potrafi wyłączyć zbędne usługi, aplikacji, widgety itp.**  Jeżeli ktoś nie chce się bawić w pojedynczą konfigurację, może od razu uruchomić optymalne ustawienia (czyli te 🟢Yes). Każdy wiersz z funkcją ma dokładny opis za co odpowiada i jakie są możliwe problemy. Oczywiście można pojechać po bandzie i wyłączyć wszystko ale wtedy można narobić sobie dużo krzywdy - więc **lepiej tego nie rób**. Stąd dałem konfliktowość lvl.2 bo nie ma co kombinować z tym programem. Część ustawień może się zrestartować po aktualizacji systemu, ale program od razu informuje co zostało zmienione.

 Program proponuje również zrobienia kopii zapasowej systemu przed zaakceptowaniem zmian. Osobiście jedynie zostawiam telemetrię, która służy Xbox Games do poprawnego działania gier z usługą Microsoftu.  


## Ublock Origin + Zgoda ciasteczkowa*

 Link: W każdym sklepie przeglądarki (Chrome,Firefox,Opera itd.)
 1.   Trudność obsługi: 🔵🔵🔵⚪️⚪️ 
 2. Stopień Konfiguracji: 🔵🔵🔵🔵⚪️
 3. Konfliktowość: 🔵🔵🔵⚪️⚪️     
4. Częstotliwość korzystania: Cały czas podczas korzystania z przeglądarki Podgląd programu:

![enter image description here](https://cloudo3.com/ArticleIMG/image-0724111700325.jpg)

Popularny adblock oraz mini dodatek*, które instaluje na każdej przeglądarce. Potrafi blokować natrętne reklamy, a także chronić nas przed SCAMAMI, krypto kopaniem itp. Instalacja jest prosta - wchodzimy w sklep przeglądarki, szukamy Ublocka, klikamy instaluj i tyle - nasz plug-in od razu będzie działać! Są jednak strony, które wycwaniły się i informują cię o korzystaniu adblocka - wtedy  jedyną opcją jaka pozostaje to wyłączenia pluginu.

Ale czy zawsze?

Otóż istnieją już takie zestawy skryptów oraz komend, które pozwalają chować informację o RODO, Cookies (Zgoda ciasteczkowa*), subskrypcji kanału, wszelakich powiadomieniach, social media widgety itd. Tutaj jednak trzeba potrafić znaleźć te dodatkowe listy - co nie jest problemem - ale zwykły Kowalski może mieć z tym problem. Najpopularniejszy zestaw w Polsce pochodzi z GitHuba https://majkiit.github.io/polish-ads-filter/. 

Nie tylko musimy ratować się cudzymi listami - możemy tworzyć własne ale tu już trzeba poświęcić ciut więcej czasu. Ja osobiście wyłączam sobie tak powiadomienie o reklamach na TVN Player. ( `##.player-alert`)

**Przy zrobieniu z  podstawowego adblocka, kombajnu skryptowego, może wystąpić wysoka konfliktowość**  ponieważ niektóre strony wysypują się bądź jest problem z interakcją ( nie działa scrollowanie, guziki, wirtualny koszyk itd.) Dlatego czasem wyłączam adblocka żeby część procesów przejść normalnie.



## CCLeaner 🛑

Link: https://www.ccleaner.com/pl-pl/ccleaner/download
Link do rozszerzenia: https://github.com/MoscaDotTo/Winapp2
 1. Trudność obsługi: 🔵🔵⚪️⚪️⚪️ 
 2. Stopień Konfiguracji: 🔵🔵🔵⚪️⚪️
 3. Konfliktowość: 🔵⚪️⚪️⚪️⚪️   ( ale są tacy co dadzą  🔵🔵🔵🔵🔵)   
 4. Częstotliwość korzystania: Raz na tydzień lub podczas usuwania resztek z odinstalowanych programów Podgląd programu:

![enter image description here](https://cdn-production.ccleaner.com/site/bywffrij/hero-banner_productpage-with-po.png)

Niektórzy go lubią, niektórzy nienawidzą. Są tacy, którym wyrządził ogromne szkody i są tacy jak ja, którzy wykorzystują go często. Ale i tak ostrzegam 🛑, bo to jedyny program z tej listy które może być bardzo kontrowersyjny. Nielubiany kolega Windowsa 10 ze szkoły - był przez moment traktowany jak Adware i Spyware. 

Sprząta, konserwuje, wyrzuca śmieci - kura desktopowa. Potrafi usunąć cache programów *(tutaj trzeba uważać z przeglądarkami - może usunąć wam zapisane hasła)*,  edytować listę rozwijaną (Menu kontekstowe) po kliknięciu PPM na ikonę programu, muzyki itd. Usuwa zbędne wpisy w rejestrze (przydatne podczas problemów z rozszerzeniami czy programami) a także programy które występują w "Dodaj lub Usuń Programy" i nie chcą się odinstalować. Do tego pokaże ci jakie sterowniki mają nowe wersje do aktualizacji.

Ja go wykorzystuję również do usuwania preinstalowanych aplikacji Windowsa 10 (kontakty, mapy, 3D explorer itp.) A także do usuwania zbędnych procesów w tle i uruchamianych programów które są widoczne w menadżerze zadań (Skype, CCleaner🤡, Teams, Java, Adobe itd.)

**Uważać na proces instalacji, bo może zainstalować zbędny syf. Lubi się często też przypominać w powiadomieniach i proponuje zniżki na wersję PRO**

Edit z 10.09.22 - Ostatnio się dowiedziałem o rozszerzeniu Winapp2 który zwiększa umiejętności CCleaner'a jeśli chodzi o usuwanie śmieci. Jest to zbiór lokalizacji w Windowsie, które również zawierają zbędne pliki cache, temp itd. Instalacja polega na wrzuceniu pliku Winapp2.ini do głównego folderu z programem a następnie przeklikanie interesujących checkboxów - choć tutaj trzeba być ostrożny bo nie są to oficjalne ścieżki folderów. Dlatego dorzucam extra 🔵 do stopnia konfiguracji.

## iBlock List Torrent  

Link: https://www.iblocklist.com

 1. Trudność obsługi: 🔵🔵⚪️⚪️⚪️
 2.  Stopień Konfiguracji: 🔵⚪️⚪️⚪️⚪️
 3.  Konfliktowość: ⚪️⚪️⚪️⚪️⚪️   
 4. Częstotliwość korzystania: Zaimportuj raz i zapomnij
 
![enter image description here](https://d3pkfiqitivr8j.cloudfront.net/sitefiles/images/iblocklist_white_1265x178.png)

Lista w txt bądź innym formacie, która służy do ignorowania połączeń potencjalnie śledzących jednostek takie jak firmy, organizacje rządowe itd. podczas pobierania Torrentów. Największym problemem jest znalezienie listy ale w linku powyżej macie przykładowy zbiór.  Import jest zależny od programu - w qbitTorrent  jest to banalne proste. Polecam przejrzeć jakie ciekawe jednostki są zablokowane - **mój ipfilter ma 647220 rekordów**

## MSConfig

Link: Jest wbudowany w systemie

 1. Trudność obsługi: 🔵🔵⚪️⚪️⚪️ 
 2. Stopień Konfiguracji: 🔵🔵🔵🔵⚪️
 3.  Konfliktowość:  🔵🔵🔵🔵⚪️ 
 4. Częstotliwość korzystania: Edytuj raz i  zapomnij

Wbudowany program do zarządzania procesami systemu. Pozwala wyłączyć zbędne usługi jak Bluetooth, Fax, Portfel itd a także procesy programów (coś podobnego jak w CCleaner). Dużo rzeczy można wyłączyć, ale może to powodować konflikt taki jak brak możliwości uruchomienia danego programu - Steam, Adobe, Office itd. W gorszym przypadku można wyłączyć sobie jakąś potrzebną usługę i mieć problemy np. z połączeniem internetowym. Na internecie można znaleźć listę procesów, które bez problemu można wyłączyć.. Opcje zaawansowane lepiej pominąć bo można wyrządzić ogromne szkody - ja np. przez przypadek usunął przydzielanie RAM podczas startu systemu. 

Kiedyś pozwalało zmniejszyć użycie RAM - teraz raczej wyłączam z przyzwyczajenia choć w komputerach z małą ilością RAM może się przydać.


## AutoRuns

Link: https://docs.microsoft.com/en-us/sysinternals/downloads/autoruns

 1. Trudność obsługi: 🔵🔵🔵⚪️⚪️ 
 2. Stopień Konfiguracji: 🔵🔵🔵⚪️⚪️
 3. Konfliktowość:  🔵🔵🔵🔵⚪️ 
 4. Częstotliwość korzystania: Edytuj raz i zapomnij
 5. Zrzut Ekranu

![enter image description here](https://docs.microsoft.com/en-us/sysinternals/downloads/media/autoruns/autoruns_v13.png)

Oryginalny program Microsoftu do zarządzania procesami w komputerze. Pozwala ukrywać oraz wyłączać zbędne procesy, zdarzenia itd. Interfejs bombarduje nas wieloma elementami i listami ale można na spokojnie to sobie ogarnąć. 

Lepiej tego nie opiszę niż sam Microsoft
> Narzędzie to, które posiada najbardziej wszechstronną wiedzę na temat lokalizacji autouruchamiania spośród wszystkich monitorów uruchamiania, pokazuje, jakie programy są skonfigurowane do uruchamiania podczas startu systemu lub logowania, a także podczas uruchamiania różnych wbudowanych aplikacji systemu Windows, takich jak Internet Explorer, Explorer i odtwarzacze multimedialne. Te programy i sterowniki znajdują się w folderze startowym, w folderach Uruchom, Uruchom raz i innych kluczach rejestru. Autoruns raportuje rozszerzenia powłoki Eksploratora, paski narzędzi, obiekty pomocnicze przeglądarki, powiadomienia Winlogon, usługi automatycznego uruchamiania i wiele innych. **Program Autoruns wykracza daleko poza inne narzędzia do automatycznego uruchamiania.** 

*Przetłumaczono z www.DeepL.com/Translator (wersja darmowa)*


## SoundSwitch

Link: https://www.instalki.pl/programy/download/Windows/multimedia_inne/SoundSwitch.html

 1. Trudność obsługi: 🔵⚪️⚪️⚪️⚪️ 
 2. Stopień Konfiguracji: 🔵⚪️⚪️⚪️⚪️
 3.  Konfliktowość:  ⚪️⚪️⚪️⚪️⚪️   
 4. Częstotliwość korzystania: Codziennie
 5. Zrzut ekranu programu:

![enter image description here](https://www.instalki.pl/components/com_djcatalog/images/296ad9288773a266f2ea00b91f6cd33d2016-03-12_21h02_13.png)

Program który pozwala w łatwy sposób zmienić źródło nadawania dźwięku (USB, MiniJack itd.)

## Podsumowanie

Chyba wystarczająco się rozpisałem o programach, które wykorzystuję na swoim codziennym komputerze oraz na cudzych. Poniżej krótka tabela podsumowująca, będąca inną perspektywą na wyżej wspomniany poradnik. 


| Program | Czy instaluję / konfiguruję na cudzym PC | Czy efekt konfiguracji **widać (dosłownie)** | Czy dasz radę wytłumaczyć Cioci? |
| ------ | ---- | ----- | --|
| ShutUp10++ |  Tak | Tak| Tak (ale nie będzie potrzeby) |
| Ublock Origin |  Raczej Tak | Zdecydowanie Tak| Tak (jeśli chodzi o wyłączenie pluginu)|
| CCleaner | Raczej Tak | Tak| Tylko podstawowe funkcje |
| IBlock List | Nie | Nie| Nie|
| Msconfig | Raczej Tak | Rzadko| Nie | 
| AutoRuns | Nie | Rzadko| Nie|
| Sound Switch | Raczej nie | Zdecydowanie Tak| Tak |


Każdy wyżej wymieniony program  mogę śmiało polecić.

# Dziękuję za przeczytanie i pozdrawiam.
Bartosz Wróbel 110129 
 Projekt wykonany do zaliczenia przedmiotu  **Grafika dla serwisów WWW**


 
