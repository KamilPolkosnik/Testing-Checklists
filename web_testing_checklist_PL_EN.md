# Web App Testing Checklist / Checklista testów aplikacji webowej

> Simple, practical checklist you can use during manual testing of a web app.  
> Prosta, praktyczna checklista do użycia podczas testów manualnych aplikacji webowej.

---

## 1. Basics / Podstawy

- [ ] **(EN)** The page opens without errors (no obvious 4xx/5xx pages).  
      **(PL)** Strona otwiera się bez błędów (brak widocznych stron 4xx/5xx).
- [ ] **(EN)** The main user flows are clear (I know what this app is for within a few seconds).  
      **(PL)** Główne ścieżki użytkownika są czytelne (w kilka sekund wiem, do czego służy aplikacja).
- [ ] **(EN)** All visible buttons and links look clickable and do something when I click them.  
      **(PL)** Wszystkie widoczne przyciski i linki wyglądają na klikalne i po kliknięciu coś robią.
- [ ] **(EN)** There are no obvious typos or “lorem ipsum” text on main pages.  
      **(PL)** Na głównych stronach nie ma oczywistych literówek ani tekstu „lorem ipsum”.

---

## 2. Navigation & URLs / Nawigacja i adresy URL

- [ ] **(EN)** Main menu items work and lead to the right pages.  
      **(PL)** Główne elementy menu działają i prowadzą do właściwych podstron.
- [ ] **(EN)** Back/forward browser buttons behave as expected (no broken history).  
      **(PL)** Przycisk wstecz/dalej w przeglądarce działa zgodnie z oczekiwaniem (historia nie jest „zepsuta”).
- [ ] **(EN)** Refreshing the page does not break the current state (or shows a clear message if it does).  
      **(PL)** Odświeżenie strony nie psuje obecnego stanu (albo pokazuje jasny komunikat, jeśli tak się dzieje).
- [ ] **(EN)** URLs are meaningful and stable (no random weird IDs where they are not needed).  
      **(PL)** Adresy URL są czytelne i stabilne (brak dziwnych losowych ID tam, gdzie nie są potrzebne).
- [ ] **(EN)** Deep links (copy–paste URL into a new tab) open the correct content.  
      **(PL)** Linki bezpośrednie (wklejenie URL w nowej karcie) otwierają właściwą zawartość.

---

## 3. Forms & Validation / Formularze i walidacja

- [ ] **(EN)** Required fields are clearly marked.  
      **(PL)** Pola wymagane są wyraźnie oznaczone.
- [ ] **(EN)** Client-side validation works (I get quick feedback without page reload when possible).  
      **(PL)** Walidacja po stronie przeglądarki działa (dostaję szybką informację zwrotną bez przeładowania strony, jeśli to możliwe).
- [ ] **(EN)** Server-side validation works (even if JS is off or bypassed, invalid data is rejected).  
      **(PL)** Walidacja po stronie serwera działa (nawet przy wyłączonym JS błędne dane są odrzucane).
- [ ] **(EN)** Error messages are understandable and point to the exact field/problem.  
      **(PL)** Komunikaty błędów są zrozumiałe i wskazują konkretne pole/problem.
- [ ] **(EN)** Successful actions show a clear confirmation (message, redirect, updated list).  
      **(PL)** Pomyślne akcje wyświetlają wyraźne potwierdzenie (komunikat, przekierowanie, zaktualizowana lista).
- [ ] **(EN)** Special characters, long text and edge cases (empty, spaces, emojis) are handled gracefully.  
      **(PL)** Znaki specjalne, długi tekst i przypadki graniczne (puste, spacje, emoji) są obsłużone poprawnie.
- [ ] **(EN)** Password fields hide input and allow secure paste (password managers).  
      **(PL)** Pola hasła ukrywają wpisywany tekst i pozwalają na wklejanie z menedżera haseł.

---

## 4. Content & UI / Treść i interfejs

- [ ] **(EN)** Text is readable (font size, contrast, spacing) on both small and large screens.  
      **(PL)** Tekst jest czytelny (rozmiar czcionki, kontrast, odstępy) na małych i dużych ekranach.
- [ ] **(EN)** Main buttons (e.g. “Save”, “Submit”, “Buy”) are visually distinct and easy to find.  
      **(PL)** Główne przyciski (np. „Zapisz”, „Wyślij”, „Kup”) wyróżniają się i łatwo je znaleźć.
- [ ] **(EN)** Icons have clear meaning or a label/tool-tip explaining them.  
      **(PL)** Ikony mają oczywiste znaczenie lub podpis/podpowiedź, który je wyjaśnia.
- [ ] **(EN)** Images load correctly and are not distorted or pixelated.  
      **(PL)** Obrazy ładują się poprawnie i nie są zniekształcone ani rozpikselowane.
- [ ] **(EN)** Empty states (no data yet) show helpful information, not just a blank screen.  
      **(PL)** Puste widoki (brak danych) pokazują pomocny komunikat, a nie tylko pusty ekran.

---

## 5. Responsiveness & Browsers / Responsywność i przeglądarki

- [ ] **(EN)** The layout adapts to common screen widths (mobile, tablet, desktop).  
      **(PL)** Układ strony dopasowuje się do typowych szerokości ekranów (telefon, tablet, komputer).
- [ ] **(EN)** Horizontal scroll is not needed on normal pages (unless it’s a deliberate design).  
      **(PL)** Przewijanie poziome nie jest potrzebne na zwykłych stronach (chyba że to celowy element projektu).
- [ ] **(EN)** Menus and dialogs work correctly on touch devices (no hidden or unreachable buttons).  
      **(PL)** Menu i dialogi działają poprawnie na urządzeniach dotykowych (brak ukrytych lub niedostępnych przycisków).
- [ ] **(EN)** App works at least in the target browsers (e.g. latest Chrome, Firefox, Edge, Safari).  
      **(PL)** Aplikacja działa przynajmniej w docelowych przeglądarkach (np. najnowszy Chrome, Firefox, Edge, Safari).

---

## 6. Performance & Stability / Wydajność i stabilność

- [ ] **(EN)** Pages open in a reasonable time on a normal connection (no endless spinners).  
      **(PL)** Strony otwierają się w rozsądnym czasie przy normalnym łączu (brak nieskończonych „kręcących się kółek”).
- [ ] **(EN)** Long operations show progress or loading indicators.  
      **(PL)** Długie operacje pokazują pasek postępu lub wskaźnik ładowania.
- [ ] **(EN)** The app handles simple errors gracefully (e.g. temporary network issues, timeouts).  
      **(PL)** Aplikacja radzi sobie z prostymi błędami (np. chwilowy brak internetu, timeout) w cywilizowany sposób.
- [ ] **(EN)** No obvious memory leaks or crashes during normal use.  
      **(PL)** Nie ma oczywistych wycieków pamięci ani zawieszek przy normalnym użytkowaniu.

---

## 7. Accessibility (Basic) / Dostępność (podstawy)

- [ ] **(EN)** Important elements can be reached with the keyboard (Tab, Enter, Space).  
      **(PL)** Ważne elementy są dostępne z klawiatury (Tab, Enter, Spacja).
- [ ] **(EN)** Links and buttons have clear text (no “click here” everywhere).  
      **(PL)** Linki i przyciski mają jasny tekst (a nie wszędzie „kliknij tutaj”).
- [ ] **(EN)** Color is not the only way to convey important information.  
      **(PL)** Kolor nie jest jedynym sposobem przekazywania ważnych informacji.

---

## 8. Security (Basic UI level) / Bezpieczeństwo (na poziomie UI)

- [ ] **(EN)** Sensitive data is not visible in the URL or page source more than necessary.  
      **(PL)** Dane wrażliwe nie są widoczne w adresie URL lub źródle strony bardziej niż to konieczne.
- [ ] **(EN)** After logout, using browser “Back” does not show private data.  
      **(PL)** Po wylogowaniu użycie przycisku „Wstecz” nie pokazuje prywatnych danych.
- [ ] **(EN)** Error messages do not reveal technical details about the system.  
      **(PL)** Komunikaty błędów nie zdradzają technicznych szczegółów systemu.
