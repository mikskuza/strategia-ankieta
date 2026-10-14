# Ankieta strategiczna marki · KOSMΛ

Formularz briefu dla nowych klientów. Odpowiedzi trafiają na mik@kosma.design przez Web3Forms.
Jeśli wysyłka się nie powiedzie, klient dostaje zapasową ścieżkę: otwarcie maila, kopiowanie odpowiedzi albo pobranie pliku .md.

## Zawartość

- `index.html` – cała ankieta (style i skrypt w jednym pliku)
- `fonts/` – Quablo (nagłówki), Geist (UI), Geist Mono (pola tekstowe)

## Publikacja na GitHub Pages

1. Na github.com utwórz nowe repozytorium, np. `ankieta`. Może być publiczne.
2. Kliknij **Add file → Upload files** i przeciągnij całą zawartość tego folderu (`index.html` i folder `fonts`).
3. Kliknij **Commit changes**.
4. Wejdź w **Settings → Pages**. W sekcji *Build and deployment* wybierz **Deploy from a branch**, gałąź `main`, folder `/ (root)`, i zapisz.
5. Po minucie lub dwóch strona będzie pod adresem `https://mikskuza.github.io/strategy-questionnaire/`.

## Języki

Ankieta domyślnie otwiera się po angielsku. Przełącznik ENG / PL jest nad nagłówkiem, a wybór zapamiętuje się w przeglądarce.
Link od razu po polsku: dopisz `?lang=pl` (albo `#pl`) na końcu adresu, np. `https://mikskuza.github.io/strategy-questionnaire/?lang=pl`.
Odpowiedzi przychodzą mailem w języku, w którym klient wypełniał ankietę (pierwsze linijki maila to mówią).

## Po publikacji

- Wypełnij ankietę raz testowo i sprawdź, czy wiadomość dotarła (zajrzyj też do spamu).
- Klucz Web3Forms jest w `index.html` w zmiennej `WEB3FORMS_KEY`. Ten klucz jest z założenia publiczny, służy tylko do wysyłania na Twój adres.
- Darmowy plan Web3Forms: 250 zgłoszeń miesięcznie.

## Własna domena (opcjonalnie)

W **Settings → Pages → Custom domain** możesz wpisać np. `brief.kosma.design`, a u swojego dostawcy domeny dodać rekord CNAME wskazujący na `<twój-login>.github.io`.
