# Stara oczyszczalnia w Prudniku

Wirtualny spacer 3D po miejskiej oczyszczalni ścieków w Prudniku (dawniej Neustadt O.-S.), uruchomionej 4 listopada 1896 r. Model jest odtworzony z archiwalnych planów i opisów.

**Strona:** https://tomaszowsiak-cloud.github.io/stara-oczyszczalnia/

## Co to jest

Oczyszczalnię zaprojektował inż. Hugo Mairich z Gothy. Była to oczyszczalnia mechaniczno-chemiczna: ścieki płynęły grawitacyjnie przez piaskownik, dwie studnie klarujące, kanał mieszania z wapnem, cztery baseny ułożone w wachlarz, dwa płytkie stawy i filtr żwirowo-piaskowy, a na końcu trafiały do Młynówki i rzeki Prudnik. Zakład pracował do 3 września 1996 r.

Strona pokazuje ten zakład jako model trójwymiarowy, po którym można się poruszać w przeglądarce, bez instalowania czegokolwiek.

## Jak zwiedzać

- **Przystanki.** Jest ich piętnaście, w trzech częściach: „Start”, „Droga ścieków” (od dopływu do odpływu) i „Zaplecze” (maszynownia, wapno, napowietrzanie, osad, woda czysta, otoczenie). Każdy ma krótką opowieść i rozwijaną część „Dla dociekliwych” z wymiarami, rzędnymi i fragmentem planu.
- **Znaczniki.** Kółka z numerami w modelu to urządzenia z legendy oryginalnego arkusza. Kliknięcie przenosi do urządzenia i pokazuje jego opis.
- **Przełączniki.** Można zdjąć dach budynku, ukryć wodę, pokazać to, co jest pod ziemią, i ukryć oznaczenia.
- **Legenda.** Na dole panelu jest pełna legenda arkusza po polsku i po niemiecku (obiekty A–H, pozycje 1–42) oraz cały arkusz do powiększenia.
- **Obsługa.** Przeciąganie obraca widok, kółko myszy lub dwa palce przybliżają. Przycisk „Idź pieszo” pozwala chodzić po terenie.

## Źródła

- E. Ritzel, *Die Wasserversorgung und die Entwässerung der Stadt Neustadt in Oberschlesien*, 1900. Tablica „Kläranlage” (ark. II i III) oraz plan sytuacyjny w skali 1:1000, wyd. Wilhelm Ernst u. Sohn, Berlin.
- Karta ewidencyjna zabytku „Zespół oczyszczalni ścieków”, Prudnik, ul. Łucznicza, oprac. J. Sawiński, PDZ ALMA, 2009.
- B. Günther, *Denkschrift*, Neustadt O/S 1925.
- P. J. Kawecki, S. Waszczykowski, *Miejska oczyszczalnia ścieków w Prudniku wczoraj i dziś*, opracowanie wewnętrzne ZWiK Prudnik.

## Co jest pewne, a co umowne

**Z planów, w skali:**
- obrys i podział budynku maszynowni, wysokość ścian i dachu, położenie maszyn;
- studnie, kanał mieszania, baseny, rozdzielacz, stawy i filtr: wymiary w planie, rzędne zwierciadeł i den;
- układ rurociągów pod ziemią z ich średnicami;
- elewacja budynku od strony studni, podział ścian na osie, detal ceglany, rombowy wzór pokrycia dachu;
- przebieg Młynówki, rzeki Prudnik i kolejki polowej (z planu 1:1000, w przybliżeniu).

**Umowne:**
- kolor pokrycia dachu, kolory wody i ścieków, wygląd maszyn i wnętrz;
- miejsce wtłaczania powietrza za piaskownikiem i sposób rozprowadzania go w stawach;
- wygląd szopy i domu dozorcy (ich położenie pochodzi z planu);
- przebieg kilku przewodów wewnątrz budynku;
- drzewa, teren wokół zakładu i postacie dodane dla skali.

Opisy urządzeń, których funkcja została wywnioskowana z rysunku i nazwy, mają na stronie dopisek „do sprawdzenia”.

## Czego w modelu nie ma

- syfonu pod rzeką i piaskownika przed nim;
- poletek osadowych, które leżały około 500 m dalej;
- płuczki żwiru, którą plan sytuacyjny zaznacza obok maszynowni bez żadnych szczegółów.

## Technika

Cała strona to jeden plik `index.html`. Nie wymaga serwera ani bazy danych. Model jest zbudowany w bibliotece three.js (wersja r128, licencja MIT), która jest wbudowana w plik.

## Autorzy

Tomasz Owsiak: pomysł, źródła, wiedza technologiczna i weryfikacja.
Claude (Anthropic): odczyt planów, model 3D i strona.

## Uwagi o materiałach

Fragmenty archiwalnych planów i zdjęcia widoczne na stronie pochodzą ze źródeł wymienionych wyżej. Przed dalszym wykorzystaniem tych reprodukcji należy sprawdzić warunki instytucji, które je przechowują.
