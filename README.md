# calc
calc.airsca.com


# Kalkulator Energetyczny AIRSCA

Kalkulator Energetyczny AIRSCA to zaawansowane narzędzie do planowania energetycznego dla systemów monitorowania i analizy przestrzeni elektromagnetycznej. Umożliwia precyzyjne określenie zapotrzebowania energetycznego w oparciu o wybrane moduły i parametry operacyjne.

## Struktura projektu

```
/kalkulator-airsca
|-- index.html              # Główny plik HTML
|-- assets/
|   |-- favicon.svg         # Ikona strony
|-- css/
|   |-- styles.css          # Arkusz stylów
|-- js/
|   |-- config.js           # Konfiguracja i dane
|   |-- calculator.js       # Główny moduł kalkulatora
|   |-- portigen-light.js   # Moduł Portigen Light
|   |-- cema-sigint.js      # Moduł CEMA/SIGINT
|   |-- main.js             # Główny plik inicjalizujący
|-- README.md               # Dokumentacja
```

## Funkcjonalności

Kalkulator oferuje trzy główne moduły dostępne poprzez system zakładek:

### 1. Kalkulator podstawowy

- Wybór modułów z czterech kategorii: obliczeniowe, antenowe/SDR, komunikacyjne i specjalistyczne
- Konfiguracja czasu pracy i marginesu bezpieczeństwa
- Obliczanie całkowitego zapotrzebowania energetycznego
- Sugerowanie optymalnej konfiguracji stacji zasilania Portigen

### 2. Kalkulator Portigen Light

- Szczegółowa specyfikacja modułu Portigen Light
- Obliczanie czasu pracy na podstawie wprowadzonego poboru mocy
- Porównanie z innymi modelami stacji zasilania Portigen

### 3. Kalkulator CEMA/SIGINT

- Specjalistyczne moduły do operacji CEMA (Cyber Electromagnetic Activities), SIGINT (Signal Intelligence) i SDR (Software Defined Radio)
- Profile misji o różnym zapotrzebowaniu energetycznym
- Obliczanie energii potrzebnej dla różnych scenariuszy operacyjnych

## Technologie

Projekt wykorzystuje czysty JavaScript bez zewnętrznych zależności, co umożliwia łatwe wdrożenie i korzystanie z kalkulatora lokalnie, bez potrzeby połączenia z serwerem.

## Obsługa kalkulatora

1. **Kalkulator podstawowy**:
   - Wybierz urządzenia klikając na nie w listach po lewej stronie
   - Ustaw czas pracy i margines bezpieczeństwa
   - Wyniki obliczeń pojawią się automatycznie po prawej stronie

2. **Portigen Light**:
   - Wprowadź pobór mocy urządzeń
   - Odczytaj przewidywany czas pracy i ekwiwalent standardowych jednostek

3. **CEMA/SIGINT**:
   - Wybierz profil misji z rozwijanego menu
   - Ustaw czas trwania misji
   - Przeglądaj szczegółowe informacje o zapotrzebowaniu energetycznym

## Instalacja i uruchomienie

1. Pobierz wszystkie pliki projektu zachowując strukturę katalogów
2. Otwórz plik `index.html` w dowolnej nowoczesnej przeglądarce
3. Nie są wymagane żadne dodatkowe biblioteki ani serwer

## Rozwój projektu

Kalkulator można rozszerzyć o nowe funkcjonalności:

- Dodatkowe moduły specjalistyczne w pliku `config.js`
- Nowe profile misji dla różnych zastosowań
- Integracja z systemami monitorowania zużycia energii w czasie rzeczywistym
- Eksport konfiguracji do pliku PDF lub JSON

## Parametry techniczne Portigen Light

Portigen Light to innowacyjna stacja zasilania o cylindrycznej konstrukcji (40cm × 14cm) zawierająca 316 ogniw litowo-jonowych 18650. Oferuje pojemność 3792 Wh przy wadze zaledwie 14.7 kg, co daje wyjątkową gęstość energetyczną 258 Wh/kg.

## Zastosowanie w systemach CEMA/SIGINT

Kalkulator jest dostosowany do planowania energetycznego dla misji związanych z:

- Monitorowaniem przestrzeni elektromagnetycznej
- Pasywnym wykrywaniem i śledzeniem urządzeń bezprzewodowych
- Analizą protokołów i sygnałów radiowych
- Wykrywaniem dronów i innych obiektów latających

---

© 2025 AIRSCA Systems | Wszystkie prawa zastrzeżone
