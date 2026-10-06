# Strona — Jarosław / Szówsko

Gotowa strona statyczna: HTML, CSS i JavaScript. Bez CMS, formularza, mapy, zewnętrznej analityki i zewnętrznych usług ładowanych przez stronę. Zdjęcia WebP i fonty są lokalne.

## Podgląd

W tej sesji: http://127.0.0.1:4173. Ten adres działa na tym komputerze, dopóki uruchomiony jest podgląd. Nie jest publicznym adresem do wysłania klientowi.

Można również otworzyć index.html bezpośrednio w przeglądarce. Pełny podgląd przez lokalny serwer: `python -m http.server 4173` w katalogu projektu.

## Vercel

1. Umieść zawartość tego katalogu w nowym repozytorium i zaimportuj je do Vercel.
2. Framework Preset: **Other**. Root Directory: katalog zawierający index.html. Build Command: puste. Output Directory: `.`. Install Command: puste. Projekt nie wymaga instalowania zależności.
3. Plik vercel.json zawiera ustawienia strony statycznej i nagłówki odpowiedzi.
4. Po wdrożeniu sprawdź adres testowy Vercel na telefonie i komputerze. Prześlij klientowi publiczny adres testowy.

## Przed domeną i publikacją docelową

- Potwierdzić z Jackiem telefon **886 179 875**, zakres ofert i zdjęcia wybrane do publikacji.
- Nagłówek używa nazwy miejscowości **Szówsko**, ponieważ klient nie podał odrębnej marki. Potwierdzić tę formę przy odbiorze.
- Zebrać ewentualne poprawki klienta w jednej wiadomości; wprowadzić je przed akceptacją.
- Rozliczyć uzgodnione wykonanie strony. Warunki rozliczenia ustala wykonawca z klientem.
- Wybrać domenę; klient powinien kupić ją na swoim koncie i danych.
- Dodać domenę w Vercel, ustawić rekordy DNS zgodnie z instrukcjami dla tego projektu, sprawdzić HTTPS oraz przekierowanie www / bez www.
- Opcjonalnie otrzymać pełne adresy Facebooka, Instagrama i TikToka. Obecnie ich nie ma, więc nie dodano pustych linków.
- Po podpięciu domeny można dodać właściwy canonical URL i sitemap.xml; nie wpisano fikcyjnej domeny.

## Edycja

- Teksty i telefon: index.html. Numer jest też w opisie strony w sekcji head.
- Kolory i układ bazowy: styles.css; aktualna kompozycja, typografia i responsywność: art-integration.css.
- Przełączanie modeli oraz galerie: app.js.
- Zdjęcia: assets/. Przy wymianie aktualizuj odpowiednie wpisy w HTML i app.js.
- Fonty: Anton oraz Manrope; licencje w katalogu licenses/.

## Weryfikacja po poprawkach klienta

Sprawdzono w przeglądarce szerokości 320, 360, 390, 760, 768, 1024 i 1440 px: bez poziomego przewijania i elementów wychodzących poza ekran. Obejrzano header, hero, Izę, Różę Max, quady, pakiet i paintball. Sprawdzono menu mobilne, przełączanie modeli, galerie, kolejne zdjęcie, zamykanie przez Escape, linki telefoniczne i mailto oraz istnienie wszystkich celów nawigacji i lokalnych plików. Brak zgłoszonych błędów w konsoli podczas kontroli. Są to testy w przeglądarce, nie pomiar na fizycznym telefonie ani weryfikacja publikacji Vercel.

## Aktualne materiały

Główne grafiki ofertowe pochodzą z materiałów klienta. Plakat paintballa korzysta z wcześniej poprawionej wersji z napisem „Szówsko”. Prawdziwe zdjęcia pozostają w sekcjach i galeriach. Cztery modele: Jacek, Róża, Iza i osobna Róża Max z nowego załącznika. Zdjęcia modeli są wyświetlane w całości bez przycinania. Grafiki i zdjęcia mają lokalne, zoptymalizowane wersje WebP.

Strzelnica ma wyłącznie tarcze statyczne. Przejażdżki: Szówsko, Radawa i okolice Jarosławia. Pakiet obejmuje quady, strzelnicę i ognisko podczas jednego wyjazdu. Kontakt: tel. 886 179 875 oraz jacor_jto@interia.pl.

## Wgranie poprawionej wersji

Paczka strona-szowsko-poprawki.zip zawiera index.html bezpośrednio w głównym katalogu oraz foldery assets/ i licenses/. Zachowaj te foldery przy wgrywaniu do repozytorium. Podmień zawartość projektu plikami z paczki, w tym index.html, styles.css, art-integration.css, app.js i motion-effects.js oraz assets/ i licenses/. Nie spłaszczaj struktury folderów. Weryfikacja tego pakietu dotyczy lokalnego podglądu; publiczne wdrożenie wymaga aktualizacji repozytorium połączonego z Vercel.

## Integracja grafik i animacje

Główne grafiki AI są pokazywane w całości, łącznie z napisami i elementami plakatów, jako ograniczone rozmiarem materiały ofertowe w grafitowej oprawie. Bez masek, rozmycia, wycinania i filtrów. Każdy plakat można powiększyć. Hero zawiera jeden nagłówek i indeks usług. W quadach plakatowi towarzyszy większa prawdziwa fotografia i dwa zdjęcia dodatkowe; pod kompozycją znajduje się rząd konkretnych informacji. Paintball oraz modele mają ciemne tła, a galeria paintballa pokazuje cztery prawdziwe zdjęcia w równych proporcjach. Zdjęcia Izy i Róży Max nadal pokazują całe konstrukcje. Zachowano dane klienta oraz pakiet trzech atrakcji.

Subtelne wejścia sekcji, zdjęć modeli i galerii korzystają z lokalnego pakietu Motion 14 mini (motion-effects.js, około 9,3 KB). Bez Reacta, CDN i instalowania zależności na Vercel. Ustawienie ograniczonego ruchu wyłącza animacje. Treść pozostaje widoczna także bez JavaScriptu. Licencje Motion, Motion DOM i Motion Utils znajdują się w licenses/.

Po tej zmianie sprawdzono układ przy 320, 390, 768, 1024 i 1440 px, otwieranie i zamykanie galerii oraz zmianę modelu. Ponownie sprawdzono lokalne odwołania i kotwice. Publikacja publiczna nie została wykonana w tej aktualizacji.
