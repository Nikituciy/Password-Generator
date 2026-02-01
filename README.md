# Password Generator (SCRUM Mini Project)

Prosta aplikacja webowa do generowania bezpiecznych haseł na podstawie parametrów podanych przez użytkownika. Projekt wykonany zespołowo zgodnie z podejściem Scrum (2 sprinty).

## Funkcjonalności
- Generowanie hasła o zadanej długości (zakres: 4–64)
- Wybór zestawu znaków:
  - litery (zawsze)
  - cyfry (opcjonalnie)
  - znaki specjalne (opcjonalnie)
- Walidacja danych wejściowych (min/max długości, komunikaty)
- Kopiowanie wygenerowanego hasła do schowka
- Proste komunikaty statusu (np. „Wygenerowano”, „Skopiowano”)

## Technologie
- HTML5
- CSS3
- JavaScript (Vanilla JS)
- Git + repozytorium zdalne (GitHub/GitLab)

## Uruchomienie projektu
1. Pobierz repozytorium:
   - `git clone <LINK_DO_REPO>`
2. Otwórz folder projektu.
3. Uruchom `index.html` w przeglądarce (dwuklik).

> Alternatywnie (opcjonalnie) możesz użyć lokalnego serwera, np. w VS Code:
> - Live Server → „Open with Live Server”

## Struktura projektu
- `index.html` – interfejs użytkownika oraz logika aplikacji (w jednym pliku)

## Jak używać
1. Ustaw długość hasła (np. 12).
2. Zaznacz opcje „Cyfry” i/lub „Znaki specjalne”.
3. Kliknij **Generuj**, aby utworzyć hasło.
4. Kliknij **Kopiuj**, aby skopiować wynik do schowka.
