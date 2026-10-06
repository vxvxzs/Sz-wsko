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
- Kolory i układ: styles.css.
- Przełączanie modeli oraz galerie: app.js.
- Zdjęcia: assets/. Przy wymianie aktualizuj odpowiednie wpisy w HTML i app.js.
- Fonty: Anton oraz Manrope; licencje w katalogu licenses/.

## Weryfikacja

Sprawdzono renderowanie dla szerokości 320, 360, 390, 768, 1024 i 1440 px: bez poziomego przewijania, błędów JavaScript i brakujących zdjęć. Sprawdzono powiększenie tekstu do 200% na komputerze, menu mobilne, trzy modele, galerie, strzałki klawiatury, Escape i linki telefoniczne. To testy w przeglądarce z symulowanymi szerokościami ekranu; nie są pomiarem wydajności na fizycznym telefonie ani weryfikacją wdrożenia Vercel.

## Materiały i redakcja

13 wybranych zdjęć z materiałów klienta. Oryginały pozostały bez zmian. Dodatkowe kopie rozmiarów ograniczają transfer na telefonie. Galeria paintballa ma sześć zdjęć; modele odpowiadają podpisanym plikom klienta.

Usunięto rozbudowane hasła marketingowe, absolutne obietnice bezpieczeństwa i twierdzenia o certyfikatach UDT, których dokumentów nie otrzymano. Zachowano producenta placów zabaw, indywidualny transport i montaż, dodatki Róży, quady dwuosobowe, kaski, szkolenie, pakiet rodzinny, strzelanie do celów oraz mobilną strzelnicę w całej Polsce od 5. roku życia.

Poprawiony plakat paintballowy jest osobnym plikiem obok projektu. Nie jest ładowany przez stronę; galeria prezentuje rzeczywiste zdjęcia.
