# Mobile App Testing Checklist / Checklista testów aplikacji mobilnej

> Simple checklist for testing mobile apps on Android/iOS.  
> Prosta checklista do testowania aplikacji mobilnych na Android/iOS.

---

## 1. Installation & First Launch / Instalacja i pierwsze uruchomienie

- [ ] **(EN)** The app installs and uninstalls cleanly from the store or APK/IPA.  
      **(PL)** Aplikacja poprawnie się instaluje i odinstalowuje ze sklepu lub z pliku APK/IPA.
- [ ] **(EN)** First launch is not extremely slow and shows some kind of progress if needed.  
      **(PL)** Pierwsze uruchomienie nie trwa zbyt długo i pokazuje jakiś postęp, jeśli to konieczne.
- [ ] **(EN)** Permission requests appear only when needed and are clearly explained.  
      **(PL)** Prośby o uprawnienia pojawiają się tylko wtedy, gdy są potrzebne, i są jasno wyjaśnione.
- [ ] **(EN)** The app behaves reasonably if I deny some permissions (shows a helpful message).  
      **(PL)** Aplikacja zachowuje się sensownie, jeśli odmówię uprawnień (pokazuje pomocny komunikat).

---

## 2. Login & Authentication / Logowanie i uwierzytelnianie

- [ ] **(EN)** Login, logout and registration flows work as expected.  
      **(PL)** Logowanie, wylogowanie i rejestracja działają zgodnie z oczekiwaniem.
- [ ] **(EN)** Error messages for wrong credentials are clear but do not expose app details.  
      **(PL)** Komunikaty błędów przy złych danych logowania są jasne, ale nie zdradzają szczegółów budowy aplikacji.
- [ ] **(EN)** “Remember me”, “Stay logged in” or similar options behave.  
      **(PL)** Opcje typu „Zapamiętaj mnie” lub „Pozostań zalogowany” działają.
- [ ] **(EN)** Biometric login (fingerprint/face) works if available, and can be turned off.  
      **(PL)** Logowanie biometryczne (odcisk palca/twarz) działa, jeśli jest dostępne, i można je wyłączyć.

---

## 3. Navigation & Gestures / Nawigacja i gesty

- [ ] **(EN)** Main navigation (tabs, side menu, bottom bar) is easy to understand.  
      **(PL)** Główna nawigacja (zakładki, menu boczne, dolny pasek) jest łatwa do zrozumienia.
- [ ] **(EN)** The app reacts correctly to system back button / swipe back.  
      **(PL)** Aplikacja poprawnie reaguje na systemowy przycisk wstecz / gest powrotu.
- [ ] **(EN)** Common gestures (tap, long press, swipe) do not cause random or confusing behavior.  
      **(PL)** Typowe gesty (tap, dłuższe przytrzymanie, przesunięcie) nie powodują losowych ani dziwnych zachowań.
- [ ] **(EN)** No important elements are hidden behind not-obvious gestures only.  
      **(PL)** Żadne ważne elementy nie są ukryte wyłącznie za mało oczywistymi gestami.

---

## 4. Forms, Input & Keyboard / Formularze, wpisywanie i klawiatura

- [ ] **(EN)** Correct keyboard type appears for each field (numbers, email, password).  
      **(PL)** Dla każdego pola pojawia się odpowiedni typ klawiatury (numeryczna, email, hasło).
- [ ] **(EN)** The screen scrolls so that the field is visible when the keyboard is open.  
      **(PL)** Ekran przewija się tak, aby pole było widoczne przy otwartej klawiaturze.
- [ ] **(EN)** Autocomplete, suggestions and copy–paste work where it makes sense.  
      **(PL)** Podpowiedzi, autouzupełnianie i kopiuj–wklej działają tam, gdzie ma to sens.
- [ ] **(EN)** Error messages are clear and positioned near the problematic field.  
      **(PL)** Komunikaty błędów są jasne i umieszczone blisko problematycznego pola.

---

## 5. Network & Offline / Sieć i tryb offline

- [ ] **(EN)** The app shows a clear message when there is no internet connection.  
      **(PL)** Aplikacja pokazuje jasny komunikat, gdy nie ma połączenia z internetem.
- [ ] **(EN)** Data is refreshed.  
      **(PL)** Dane są odświeżane.
- [ ] **(EN)** If offline mode is supported, it is clearly explained and works reliably.  
      **(PL)** Jeśli tryb offline jest wspierany, jest jasno opisany i działa przewidywalnie.

---

## 6. Push Notifications / Powiadomienia push

- [ ] **(EN)** The app asks for notification permission.  
      **(PL)** Aplikacja prosi o zgodę na powiadomienia.
- [ ] **(EN)** Notifications contain useful text and lead to the correct screen when tapped.  
      **(PL)** Powiadomienia zawierają przydatny tekst i po "tapnięciu" prowadzą do właściwego ekranu.
- [ ] **(EN)** Turning notifications on/off in the app actually changes behavior.  
      **(PL)** Włączenie/wyłączenie powiadomień w aplikacji faktycznie zmienia jej zachowanie.

---

## 7. Device Integration / Integracja z urządzeniem

- [ ] **(EN)** Features using camera, gallery, GPS, microphone etc. work as expected.  
      **(PL)** Funkcje korzystające z aparatu, galerii, GPS, mikrofonu itd. działają zgodnie z oczekiwaniem.
- [ ] **(EN)** The app reacts properly to rotation (portrait/landscape) or locks orientation if needed.  
      **(PL)** Aplikacja poprawnie reaguje na obrót ekranu (pion/poziom) albo celowo blokuje orientację.
- [ ] **(EN)** The app handles incoming calls and system dialogs without crashing.  
      **(PL)** Aplikacja radzi sobie z przychodzącymi połączeniami i systemowymi komunikatami bez wyłączeń.
- [ ] **(EN)** Dark mode/light mode look acceptable (no invisible text).  
      **(PL)** Tryb ciemny/jasny wygląda poprawnie (brak niewidocznego tekstu).

---

## 8. Performance, Battery & Stability / Wydajność, bateria i stabilność

- [ ] **(EN)** The app feels responsive (no long freezes while scrolling or tapping).  
      **(PL)** Aplikacja działa płynnie (brak długich przycięć przy przewijaniu lub dotyku).
- [ ] **(EN)** Battery usage is reasonable during normal use (no sudden drops).  
      **(PL)** Zużycie baterii jest rozsądne przy normalnym użytkowaniu (brak gwałtownych spadków).
- [ ] **(EN)** The app does not crash during basic flows (login, main actions, settings).  
      **(PL)** Aplikacja nie wyłącza się samoistnie przy podstawowych ścieżkach (logowanie, główne akcje, ustawienia).
- [ ] **(EN)** The app can be minimized and restored without losing important data/state.  
      **(PL)** Aplikację można zminimalizować i przywrócić bez utraty ważnych danych/stanu.

---

## 9. Updates & Versioning / Aktualizacje i wersje

- [ ] **(EN)** Updating the app keeps user data (unless changes are clearly communicated).  
      **(PL)** Aktualizacja aplikacji zachowuje dane użytkownika (chyba że inaczej jasno zakomunikowano).
- [ ] **(EN)** Old versions show a clear message if they are no longer supported.  
      **(PL)** Starsze wersje pokazują jasny komunikat, jeśli nie są już wspierane.
