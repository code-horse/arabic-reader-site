---
layout: bare
title: Arabic Reader - Brugervejledning
lang: da
---
# Arabic Reader - Brugervejledning

> Version: v1.0.0

## Introduktion

Arabic Reader er en browserudvidelse designet til arabiske elever. Den føjer Tashkeel (vokalmærker / حركات) til arabiske ord på websider og PDF'er, giver automatisk vokalisering, en svæveordbog med rodanalyse og grammatiske former, tekst-til-tale og oversættelsesfunktioner - hjælper dig med at lære arabisk udtale og grammatik lettere.

---

## Hovedfunktioner

- **Automatisk Tashkeel** — Tilføjer vokaltegn (fathah, kasrah, dammah, sukun, shadda, tanween) til arabiske ord på enhver webside
- **Hele sidetilstand** — Et-klik Tashkeel for alle arabiske ord på siden
- **Hover Dictionary** — Hold markøren over ord for at se vokalisering, definitioner, rodanalyse og I'rab-former; vælg mellem Ordbogstilstand, Værktøjstip-tilstand eller Fra
- **I'rab Analyse** — Vis grammatiske kasusendelser (nominativ, akkusativ, genitiv) for relevante ord
- **Tekst-til-tale** — Arabisk TTS med ord-for-ord karaoke-fremhævning (ar-SA-stemme)
- **Valg tale** — Vælg en tekst, en kompakt værktøjslinje vises med tal- og oversæt-knapper
- **Oversættelse** — Vælg en tekst, klik på oversæt for at få øjeblikkelig oversættelse via Bing eller Google Translate (108 sprog)
- **PDF-læser** — Indbygget RTL PDF-fremviser med Tashkeel annoteringsunderstøttelse
- **Smart Detection** — Automatisk arabisk tekstgenkendelse og PDF smart omdirigering
- **Root Extraction** — Identificer ordrødder for bedre forståelse af arabisk morfologi
- **Tastaturgenveje** — Hurtig adgang til kernefunktioner
- **Flersproget grænseflade** — arabisk, engelsk og kinesisk brugergrænseflade

---

## Sådan bruges

### Trin 1: Installer udvidelsen

Installer **Arabic Reader** fra [Chrome Web Store](https://chromewebstore.google.com/), eller indlæs det lokalt i udviklertilstand.

### Trin 2: Åbn enhver webside

Besøg enhver webside, der indeholder arabisk indhold.

### Trin 3: Aktiver Tashkeel

Klik på udvidelsesikonet i din browsers værktøjslinje. Slå "Aktiver Tashkeel" til, og skift derefter "Hele siden Tashkeel" for at kommentere alle arabiske ord på siden.

### Trin 4: Se annoteringer

Hold markøren over ord for at se Tashkeel værktøjstip med vokalisering, definitioner og udtale. Klik på højttalerikonet for at høre ordet.

### Trin 5: Læs og oversæt valgt tekst

Vælg enhver arabisk tekst med musen. En kompakt værktøjslinje vises nær markeringen med to knapper:
- **Højttaler** — Læser den valgte tekst højt med karaoke-stil ord for ord fremhævelse
- **Oversæt** — Viser en indlejret oversættelsesboble under værktøjslinjen

> **Tip:** Klik på udvidelsesikonet i din browsers værktøjslinje for at åbne indstillingspanelet og justere svævetilstand, talehastighed, oversættelsesmotor og mere.

---

## Hele siden Tashkeel tilstand

Når tilstanden for hele side Tashkeel er aktiveret, får hvert arabisk ord på siden tilføjet vokaltegn. Udvidelsen bruger smart detektion til at identificere arabiske tekstblokke og anvender Tashkeel ved hjælp af dens medfølgende ordbog og NLP-algoritmer.

---

## Hover Ordbog

Udvidelsen inkluderer en indbygget arabisk ordbog. Du kan vælge mellem flere svævetilstande i indstillingerne:

| Tilstand | Adfærd |
|------|--------|
| **Ordbog** | Hover viser Tashkeel + definitioner + root + I'rab + udtaleknap |
| **Værktøjstip** | Hover viser Tashkeel + udtaleknap (ingen definitioner) |
| **Fra** | Ingen svæveeffekt |

I **Ordbogstilstand** viser værktøjstippet:
- Ordet med fuld vokalisering (Tashkeel)
- En udtaleknap (klik for at høre)
- Orddefinitioner
- Rodanalyse (rod på tre bogstaver)
- I'rab (grammatiske store og små bogstaver) dannes, når det er aktiveret

---

## PDF-læser

Arabic Reader inkluderer en indbygget PDF-læser med fuld RTL-understøttelse, der giver dig mulighed for at læse arabiske PDF-dokumenter med Tashkeel-annoteringer.

### Åbning af en PDF

**Metode 1: Fra pop op-vinduet**  
Klik på udvidelsesikonet, og klik derefter på "Åbn PDF Reader". Træk og slip en PDF-fil, eller klik på "Vælg fil" for at åbne en lokal PDF. Du kan også indsætte en PDF-URL.

**Metode 2: Kontekstmenu**  
Højreklik på et vilkårligt `.pdf`-link på en webside, og vælg "Åbn PDF med Arabic Reader".

**Metode 3: Automatisk registrering**  
Når "PDF Smart Detection" er aktiveret i indstillingerne, omdirigerer udvidelsen automatisk `.pdf` URL'er til den indbyggede læser.

### PDF-læserfunktioner

- **Tashkeel Annoteringer** — Alle annoteringsfunktioner fungerer på PDF-tekst
- **Klik på Ordbog** — Klik på et hvilket som helst ord for at se dets definition
- **Værktøjslinje** — Vælg tekst, der skal læses, oversættes eller kopieres
- **Sidebjælke** — Indholdsfortegnelse og sideminiaturebilleder
- **Søg** — Søg efter tekst i PDF'en
- **Temaer** — Mørke, Lyse og Sepia læsetemaer
- **Zoom** — Flere zoomniveauer inklusive Auto, Sidetilpasning og Sidebredde
- **RTL-layout** — Fuld støtte fra højre mod venstre

---

## Tekst-til-tale

Udvidelsen bruger Chromes indbyggede arabiske TTS-stemme (ar-SA) til udtale.

**Enkelt ord:** Hold markøren over et ord, og klik på højttalerknappen i værktøjstippet.

**Udvalgstale:** Vælg en hvilken som helst arabisk tekst. En flydende værktøjslinje vises med en højttalerknap - klik på den for at læse op med karaoke-stil ord-for-ord-fremhævning.

**Højreklik-menu:** Vælg tekst, højreklik og vælg "Oplæs markering".

**Tastaturgenvej:** Vælg tekst, og tryk på `Alt+Shift+S` (Mac: `Ctrl+Shift+S`).

---

## Oversættelse

Vælg en tekst på siden, og brug oversættelsesfunktionen til at få øjeblikkelige oversættelser.

**Metode 1: Udvælgelsesværktøjslinje**  
Vælg tekst, og klik derefter på oversæt-knappen på værktøjslinjen.

**Metode 2: Højreklik på menuen**  
Vælg tekst, højreklik og vælg "Oversæt markering".

**Metode 3: Tastaturgenvej**  
Vælg tekst, og tryk på `Alt+Shift+T` (Mac: `Ctrl+Shift+T`).

**Oversættelsesmotorer:**
- **Bing Translate** (standard) — Drevet af Microsoft Translator
- **Google Translate** — Drevet af Google

Begge motorer understøtter **108 målsprog**.

---

## Tastaturgenveje

| Genvej | Mac genvej | Handling |
|--------|-------------|--------|
| `Alt+Shift+A` | `Ctrl+Shift+A` | Slå Tashkeel annoteringer til/fra |
| `Alt+Shift+S` | `Ctrl+Shift+S` | Læs valgt tekst |
| `Alt+Shift+T` | `Ctrl+Shift+T` | Oversæt valgt tekst |

> **Tip:** Du kan tilpasse disse genveje i Chrome på `chrome://extensions/shortcuts`.

---

## Indstillingsvejledning

| Indstilling | Beskrivelse |
|--------|-------------|
| **Aktiver Tashkeel** | Hovedkontakt til at aktivere eller deaktivere Tashkeel annotationsfunktionen |
| **Hel side Tashkeel** | Når det er aktiveret, føjer vokaltegn til alle arabiske ord på siden |
| **Svævetilstand** | Vælg svæveadfærd: Ordbog (definitioner + lyd), Værktøjstip (Tashkeel + lyd) eller Fra |
| **Vis I'rab formularer** | Vis grammatiske bogstaver for relevante ord |
| **Talehastighed** | Juster hastigheden for sætningslæsning |
| **Oversættelsesmotor** | Vælg mellem Bing Translate og Google Translate |
| **Målsprog** | Indstil oversættelsesmålsproget |
| **PDF Smart Detection** | Når det er aktiveret, omdirigerer PDF-URL'er automatisk til den indbyggede læser |

---

## Ofte stillede spørgsmål

**Sp: Hvorfor virker det ikke på nogle sider?**  
A: Af sikkerhedsmæssige årsager kan browserudvidelser ikke køre på specielle sider som `chrome://`, browserindstillinger eller Chrome Web Store.

**Sp: Ingen lyd fra tekst-til-tale?**  
A: Kontroller venligst dine systemlydstyrkeindstillinger og sørg for, at arabiske stemmepakker er installeret. Taleunderstøttelse varierer på tværs af browsere og operativsystemer.

**Spørgsmål: Udvidelsen registrerer ikke arabisk tekst.**  
A: Udvidelsen bruger smart detektion til at finde arabiske tekstblokke. Hvis teksten gengives som billeder eller bruger ikke-standard kodning, kan den muligvis ikke registreres.

**Sp: Oversættelse virker ikke?**  
A: Oversættelse kræver en internetforbindelse. Hvis Bing Translate fejler, prøv at skifte til Google Translate i indstillingerne.

**Sp: Hvordan åbner jeg en PDF med Arabic Reader?**  
A: Klik på "Åbn PDF-læser" i pop op-vinduet, højreklik på et PDF-link og vælg "Åbn PDF med Arabic Reader", eller aktiver "PDF Smart Detection" i indstillingerne.

---

## Relaterede links

- [Privatlivspolitik](../privatlivspolitik)
- [Support & Feedback](../support)

---

---
