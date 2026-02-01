## Scenariusze testów manualnych (podstawowe)
1. **Generowanie domyślne**  
   - Długość: 12, cyfry: ON, specjalne: ON  
   - Oczekiwane: hasło długości 12, zawiera różne znaki
2. **Minimalna długość**  
   - Długość: 4  
   - Oczekiwane: hasło długości 4
3. **Przekroczenie zakresu**  
   - Długość: 100  
   - Oczekiwane: aplikacja ogranicza do 64
4. **Brak dodatkowych zestawów**  
   - Cyfry: OFF, specjalne: OFF  
   - Oczekiwane: hasło składa się z liter
5. **Kopiowanie do schowka**  
   - Kliknij „Kopiuj” po wygenerowaniu  
   - Oczekiwane: komunikat „Skopiowano do schowka”

## Znane ograniczenia
- Funkcja kopiowania może nie działać w części przeglądarek, jeśli strona jest uruchomiona w trybie z ograniczeniami (np. blokady uprawnień). W takim przypadku hasło można skopiować ręcznie.

## Zespół i role (SCRUM)
- Scrum Master: [Imię Nazwisko]
- Developer: [Imię Nazwisko]
- Tester: [Imię Nazwisko]

## Backlog i sprinty
Projekt zrealizowany w 2 sprintach:
- Sprint 1: przygotowanie UI, logika generowania, opcje znaków, walidacja
- Sprint 2: kopiowanie do schowka, komunikaty, testy manualne, stabilizacja, README

## Licencja
Projekt edukacyjny (laboratorium) – do użytku niekomercyjnego.
