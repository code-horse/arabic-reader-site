---
layout: bare
title: Arabic Reader Extension — Podręcznik użytkownika
lang: pl
---

# Arabic Reader — Podręcznik użytkownika

> Wersja: v1.0.0

## Wprowadzenie

Arabic Reader to rozszerzenie przeglądarki dla uczących się języka arabskiego. Dodaje znakowanie Tashkeel (حركات) do arabskich słów na stronach i w plikach PDF: automatyczna wokalizacja, słownik po najechaniu (korzeń i formy gramatyczne), zamiana tekstu na mowę oraz tłumaczenie — ułatwia naukę wymowy i gramatyki.

---

## Główne funkcje

- **Automatyczny Tashkeel** — Znaki vocaliczne (m.in. fathah, kasrah, dammah) na dowolnej stronie
- **Tryb całej strony** — Jednym kliknięciem taszkil dla wszystkich słów arabskich
- **Słownik po najechaniu** — Po najechaniu: wokalizacja, znaczenia, korzeń i formy I'rab; tryby Słownik, Podpowiedź lub Wyłączone
- **Analiza I'rab** — Końcówki przypadkowe tam, gdzie ma to zastosowanie
- **Synteza mowy** — Arabska TTS z podświetlaniem słów (głos ar-SA)
- **Mowa zaznaczenia** — Po zaznaczeniu tekstu pojawia się pasek z czytaniem i tłumaczeniem
- **Tłumaczenie** — Zaznacz tekst i kliknij Tłumacz, aby uzyskać natychmiastowe tłumaczenie przez Bing lub Google (108 języków)
- **Czytnik PDF** — Wbudowany przeglądarka PDF RTL z obsługą Tashkeel
- **Inteligentne wykrywanie** — Automatyczne wykrywanie arabskiego i przekierowanie PDF
- **Wyciąganie korzeni** — Dla morfologii arabskiej
- **Skróty klawiszowe**
- **Wielojęzyczny interfejs** — Arabski, angielski, chiński

---

## Korzystanie

### Krok 1: Instalacja

Zainstaluj **Arabic Reader** z [Chrome Web Store](https://chromewebstore.google.com/) lub wczytaj lokalnie w trybie deweloperskim.

### Krok 2: Otwórz stronę

Wejdź na stronę z treścią po arabsku.

### Krok 3: Włącz Tashkeel

Kliknij ikonę rozszerzenia. Włącz „Włącz Tashkeel”, potem „Tashkeel całej strony”.

### Krok 4: Podgląd adnotacji

Najedź na słowo, aby zobaczyć chmurkę z taszkilem i znaczeniami. Kliknij ikonę głośnika.

### Krok 5: Czytanie i tłumaczenie zaznaczenia

Zaznacz tekst arabski. Pojawi się pasek:
- **Głośnik** — Czyta zaznaczenie z podświetlaniem słów
- **Tłumacz** — Wbudowany dymek tłumaczenia pod paskiem

> **Wskazówka:** Przez ikonę rozszerzenia otwórz ustawienia (tryb najechania, szybkość mowy, silnik tłumaczenia itd.).

---

## Tryb Tashkeel całej strony

Po włączeniu każde słowo arabskie otrzymuje znaki vocaliczne. Rozszerzenie wykrywa bloki tekstu i stosuje Tashkeel za pomocą wbudowanego słownika i NLP.

---

## Słownik po najechaniu

Wbudowany słownik arabski. Tryby w ustawieniach:

| Tryb | Zachowanie |
|------|------------|
| **Słownik** | Najechanie: Tashkeel + znaczenia + korzeń + I'rab + przycisk wymowy |
| **Podpowiedź** | Najechanie: Tashkeel + przycisk (bez znaczeń) |
| **Wyłączone** | Brak efektu |

W trybie **Słownik** chmurka pokazuje słowo z pełną wokalizacją, przycisk audio, definicje, trzyliterowy korzeń i I'rab, gdy włączone.

---

## Czytnik PDF

Wbudowany czytnik z pełnym RTL dla dokumentów arabskich z Tashkeel.

### Otwieranie PDF

**1 — Z wyskakującego okna:** ikona → „Otwórz czytnik PDF”, przeciągnij plik lub „Wybierz plik”, możesz wkleić adres PDF.

**2 — Menu kontekstowe:** PPM na link `.pdf` → „Otwórz PDF w Arabic Reader”.

**3 — Auto:** przy „Inteligentnym wykrywaniu PDF” adresy `.pdf` kierują do wbudowanego czytnika.

### Funkcje PDF

- **Adnotacje Tashkeel** — Na tekście PDF
- **Słownik po kliknięciu**
- **Pasek zaznaczenia** — Czytanie, tłumaczenie, kopiowanie
- **Panel boczny** — Spis treści i miniatury
- **Wyszukiwanie**
- **Motywy** — Ciemny, jasny, sepia
- **Powiększenie** — Auto, strona, szerokość
- **Układ RTL**

---

## Synteza mowy

Wbudowany w Chrome arabski głos TTS (ar-SA).

**Słowo:** najeżdżaj i klikaj głośnik w chmurce.

**Zaznaczenie:** pływający pasek z głośnikiem.

**Menu kontekstowe:** „Czytaj zaznaczenie”.

**Skrót:** `Alt+Shift+S` (Mac: `Ctrl+Shift+S`).

---

## Tłumaczenie

Zaznacz tekst w celu natychmiastowego tłumaczenia.

**1:** Pasek zaznaczenia → Tłumacz.

**2:** Menu kontekstowe → „Tłumacz zaznaczenie”.

**3:** `Alt+Shift+T` (Mac: `Ctrl+Shift+T`).

**Silniki:** **Bing Translator** (domyślnie), **Google Translate**. Oba obsługują **108 języków docelowych**.

---

## Skróty klawiszowe

| Skrót | Mac | Akcja |
|-------|-----|-------|
| `Alt+Shift+A` | `Ctrl+Shift+A` | Włącz/wyłącz Tashkeel |
| `Alt+Shift+S` | `Ctrl+Shift+S` | Czytaj zaznaczenie |
| `Alt+Shift+T` | `Ctrl+Shift+T` | Tłumacz zaznaczenie |

> **Wskazówka:** Dostosuj w `chrome://extensions/shortcuts`.

---

## Ustawienia

| Ustawienie | Opis |
|------------|------|
| **Włącz Tashkeel** | Główny przełącznik adnotacji |
| **Tashkeel całej strony** | Znakowanie wszystkich słów arabskich |
| **Tryb najechania** | Słownik, Podpowiedź lub Wyłączone |
| **Pokaż formy I'rab** | Końcówki gramatyczne |
| **Szybkość mowy** | Szybkość czytania zdań |
| **Silnik tłumaczenia** | Bing lub Google |
| **Język docelowy** | Język tłumaczenia |
| **Inteligentne wykrywanie PDF** | Przekierowanie adresów PDF do wbudowanego czytnika |

---

## FAQ

**Dlaczego nie działa na niektórych stronach?**  
Ze względów bezpieczeństwa rozszerzenia nie działają na `chrome://`, w ustawieniach przeglądarki ani w Chrome Web Store.

**Brak dźwięku TTS?**  
Sprawdź głośność i pakiety głosów arabskich. Obsługa zależy od przeglądarki i systemu.

**Nie wykrywa arabskiego.**  
Tekst jako obraz lub niestandardowe kodowanie może nie być rozpoznany.

**Tłumaczenie nie działa?**  
Wymagane jest połączenie z internetem. Przy awarii Bing przełącz na Google w ustawieniach.

**Jak otworzyć PDF w Arabic Reader?**  
„Otwórz czytnik PDF”, menu kontekstowe na linku lub włącz „Inteligentne wykrywanie PDF”.

---

## Linki

- [Polityka prywatności](../privacy-policy)
- [Wsparcie i opinie](../support)

---
