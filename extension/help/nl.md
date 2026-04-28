---
layout: bare
title: Arabic Reader Extension — Gebruikershandleiding
lang: nl
---

# Arabic Reader — Gebruikershandleiding

> Versie: v1.0.0

## Introductie

Arabic Reader is een browserextensie voor wie Arabisch leert. Het voegt Tashkeel (klinkertekens / حركات) toe aan Arabische woorden op webpagina's en in PDF's: automatische vocalisatie, een woordenboek bij zweven (stam en grammaticale vormen), tekst-naar-spraak en vertaling — om uitspraak en grammatica te vergemakkelijken.

---

## Belangrijkste functies

- **Automatisch Tashkeel** — Klinkertekens (o.a. fathah, kasrah, dammah) op elke webpagina
- **Hele pagina** — Eén klik voor alle Arabische woorden
- **Zweefwoordenboek** — Bij zweven: vocalisatie, definities, stam en I'rab-vormen; modi Woordenboek, Tooltip of Uit
- **I'rab-analyse** — Naamvallen waar van toepassing
- **Tekst-naar-spraak** — Arabische TTS met woord-voor-woord markering (stem ar-SA)
- **Selectie voorlezen** — Na selectie verschijnt een compacte balk met voorlezen en vertalen
- **Vertaling** — Selecteer tekst en klik op Vertalen voor directe vertaling via Bing of Google (108 talen)
- **PDF-lezer** — Ingebouwde RTL-PDF-viewer met Tashkeel
- **Slimme detectie** — Automatische Arabische tekstdetectie en PDF-doorsturing
- **Stamextractie** — Voor morfologie
- **Sneltoetsen**
- **Meertalige interface** — Arabisch, Engels, Chinees

---

## Gebruik

### Stap 1: Extensie installeren

Installeer **Arabic Reader** via de [Chrome Web Store](https://chromewebstore.google.com/) of laad lokaal in ontwikkelaarsmodus.

### Stap 2: Pagina openen

Bezoek een pagina met Arabische inhoud.

### Stap 3: Tashkeel inschakelen

Klik op het extensiepictogram. Schakel «Tashkeel inschakelen» en «Tashkeel hele pagina» in.

### Stap 4: Annotaties bekijken

Beweeg over woorden voor tooltips met Tashkeel. Klik op het luidsprekerpictogram.

### Stap 5: Selectie voorlezen en vertalen

Selecteer Arabische tekst. Er verschijnt een balk met:
- **Luidspreker** — Leest de selectie voor met woordmarkering
- **Vertalen** — Toont een inline vertaling onder de balk

> **Tip:** Open via het pictogram de instellingen (zweefmodus, spreeksnelheid, vertaalengine, enz.).

---

## Modus Tashkeel hele pagina

Elk Arabisch woord krijgt klinkertekens. De extensie detecteert tekstblokken en past Tashkeel toe met woordenboek en NLP.

---

## Zweefwoordenboek

Ingebouwd Arabisch woordenboek. Modi in instellingen:

| Modus | Gedrag |
|-------|--------|
| **Woordenboek** | Zweven: Tashkeel + definities + stam + I'rab + uitspreekknop |
| **Tooltip** | Zweven: Tashkeel + uitspreekknop (zonder definities) |
| **Uit** | Geen effect |

In de modus **Woordenboek** toont de tooltip het volledig ge vocaliseerde woord, audiobutton, definities, drieletterige stam en I'rab indien ingeschakeld.

---

## PDF-lezer

Ingebouwde lezer met volledige RTL voor Arabische PDF's met Tashkeel.

### PDF openen

**1 — Popup:** pictogram → «PDF-lezer openen», bestand slepen of «Bestand kiezen», of PDF-URL plakken.

**2 — Contextmenu:** rechtsklik op `.pdf`-link → «PDF openen met Arabic Reader».

**3 — Automatisch:** bij «PDF slimme detectie» worden PDF-URL's naar de ingebouwde lezer gestuurd.

### PDF-functies

- **Tashkeel-annotaties** — Op PDF-tekst
- **Woordenboek bij klik**
- **Selectiebalk** — Voorlezen, vertalen, kopiëren
- **Zijbalk** — Inhoudsopgave en miniaturen
- **Zoeken**
- **Thema's** — Donker, licht, sepia
- **Zoom** — Auto, pagina, breedte
- **RTL-layout**

---

## Tekst-naar-spraak

Ingebouwde Arabische TTS-stem van Chrome (ar-SA).

**Woord:** zweven en klik op luidspreker in tooltip.

**Selectie:** zwevende balk met luidspreker.

**Contextmenu:** «Selectie voorlezen».

**Sneltoets:** `Alt+Shift+S` (Mac: `Ctrl+Shift+S`).

---

## Vertaling

Selecteer tekst voor directe vertaling.

**1:** Selectiebalk → Vertalen.

**2:** Contextmenu → «Selectie vertalen».

**3:** `Alt+Shift+T` (Mac: `Ctrl+Shift+T`).

**Engines:** **Bing Translate** (standaard), **Google Translate**. Beide ondersteunen **108 doeltalen**.

---

## Sneltoetsen

| Sneltoets | Mac | Actie |
|-----------|-----|-------|
| `Alt+Shift+A` | `Ctrl+Shift+A` | Tashkeel aan/uit |
| `Alt+Shift+S` | `Ctrl+Shift+S` | Selectie voorlezen |
| `Alt+Shift+T` | `Ctrl+Shift+T` | Selectie vertalen |

> **Tip:** Aanpassen via `chrome://extensions/shortcuts`.

---

## Instellingen

| Instelling | Beschrijving |
|------------|--------------|
| **Tashkeel inschakelen** | Hoofdschakelaar |
| **Tashkeel hele pagina** | Klinkertekens voor alle Arabische woorden |
| **Zweefmodus** | Woordenboek, Tooltip of Uit |
| **I'rab-vormen tonen** | Grammaticale uitgangen |
| **Spreeksnelheid** | Snelheid van zinnen |
| **Vertaalengine** | Bing of Google |
| **Doeltaal** | Vertaaldoel |
| **PDF slimme detectie** | PDF-URL's naar ingebouwde lezer |

---

## FAQ

**Waarom werkt het niet op sommige pagina's?**  
Om veiligheidsredenen draaien extensies niet op `chrome://`, browserinstellingen of de Chrome Web Store.

**Geen geluid bij TTS?**  
Controleer volume en Arabische stemmen. Ondersteuning verschilt per browser en OS.

**Detecteert geen Arabisch.**  
Tekst als afbeelding of niet-standaard codering kan mislukken.

**Vertaling werkt niet?**  
Internet is nodig. Bij falen van Bing: schakel over naar Google.

**PDF openen met Arabic Reader?**  
«PDF-lezer openen», contextmenu op link, of schakel «PDF slimme detectie» in.

---

## Links

- [Privacybeleid](../privacy-policy)
- [Ondersteuning en feedback](../support)

---
