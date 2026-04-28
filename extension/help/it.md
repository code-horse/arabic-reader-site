---
layout: bare
title: Arabic Reader Extension — Guida utente
lang: it
---

# Arabic Reader — Guida utente

> Versione: v1.0.0

## Introduzione

Arabic Reader è un'estensione del browser per chi studia l'arabo. Aggiunge il Tashkeel (segni vocalici / حركات) alle parole arabe su pagine web e PDF, con vocalizzazione automatica, dizionario al passaggio del mouse (analisi delle radici e forme grammaticali), sintesi vocale e traduzione, per facilitare pronuncia e grammatica.

---

## Funzionalità principali

- **Tashkeel automatico** — Segni vocalici (fathah, kasrah, dammah, sukun, shadda, tanwin) su qualsiasi pagina web
- **Modalità pagina intera** — Tashkeel con un clic per tutte le parole arabe
- **Dizionario al passaggio** — Al passaggio del mouse: vocalizzazione, definizioni, radice e forme I'rab; modalità Dizionario, Tooltip o Disattivato
- **Analisi I'rab** — Desinenze di caso (nominativo, accusativo, genitivo) quando applicabile
- **Sintesi vocale** — TTS araba con evidenziazione parola per parola (voce ar-SA)
- **Lettura selezione** — Dopo la selezione del testo, una barra compatta offre lettura e traduzione
- **Traduzione** — Selezionare testo e fare clic su Traduci per una traduzione istantanea con Bing o Google Translate (108 lingue)
- **Lettore PDF** — Visualizzatore PDF RTL integrato con supporto Tashkeel
- **Rilevamento intelligente** — Rilevamento automatico dell'arabo e reindirizzamento PDF
- **Estrazione radici** — Per la morfologia araba
- **Scorciatoie da tastiera**
- **Interfaccia multilingue** — Arabo, inglese e cinese

---

## Utilizzo

### Passo 1: Installare l'estensione

Installare **Arabic Reader** dal [Chrome Web Store](https://chromewebstore.google.com/) o caricarla in locale in modalità sviluppatore.

### Passo 2: Aprire una pagina web

Visitare una pagina con contenuto in arabo.

### Passo 3: Abilitare il Tashkeel

Cliccare sull'icona dell'estensione. Attivare «Abilita Tashkeel» e «Tashkeel pagina intera».

### Passo 4: Visualizzare le annotazioni

Passare il mouse sulle parole per i tooltip Tashkeel. Cliccare sull'icona altoparlante per ascoltare.

### Passo 5: Leggere e tradurre la selezione

Selezionare testo arabo. Appare una barra con:
- **Altoparlante** — Legge la selezione con evidenziazione parola per parola
- **Traduci** — Mostra una bolla di traduzione sotto la barra

> **Suggerimento:** clic sull'icona per le impostazioni (modalità hover, velocità, motore di traduzione, ecc.).

---

## Modalità Tashkeel pagina intera

Con questa modalità, ogni parola araba riceve i segni vocalici. L'estensione rileva i blocchi di testo e applica il Tashkeel tramite dizionario e NLP.

---

## Dizionario al passaggio

Dizionario arabo integrato. Modalità nelle impostazioni:

| Modalità | Comportamento |
|----------|-----------------|
| **Dizionario** | Passaggio: Tashkeel + definizioni + radice + I'rab + pronuncia |
| **Tooltip** | Passaggio: Tashkeel + pronuncia (senza definizioni) |
| **Disattivato** | Nessun effetto |

In modalità **Dizionario** il tooltip mostra parola vocalizzata, pulsante audio, definizioni, radice trilittera e I'rab se abilitato.

---

## Lettore PDF

Lettore PDF integrato con supporto RTL completo per documenti arabi con Tashkeel.

### Aprire un PDF

**1 — Popup:** icona → «Apri lettore PDF», trascinare un file o «Scegli file», oppure incollare URL PDF.

**2 — Menu contestuale:** clic destro su link `.pdf` → «Apri PDF con Arabic Reader».

**3 — Rilevamento automatico:** con «Rilevamento intelligente PDF» le URL PDF vanno al lettore integrato.

### Funzioni PDF

- **Annotazioni Tashkeel**
- **Dizionario al clic**
- **Barra selezione** — Leggere, tradurre, copiare
- **Barra laterale** — Indice e miniature
- **Ricerca**
- **Temi** — Scuro, chiaro, seppia
- **Zoom** — Auto, pagina, larghezza
- **Layout RTL**

---

## Sintesi vocale

Voce TTS araba integrata in Chrome (ar-SA).

**Parola:** passare il mouse e cliccare l'altoparlante nel tooltip.

**Selezione:** barra mobile con altoparlante ed evidenziazione.

**Menu contestuale:** «Leggi selezione».

**Scorciatoia:** `Alt+Maiusc+S` (Mac: `Ctrl+Maiusc+S`).

---

## Traduzione

Selezionare testo per la traduzione immediata.

**1:** barra selezione → Traduci.

**2:** menu contestuale → «Traduci selezione».

**3:** scorciatoia — `Alt+Maiusc+T` (Mac: `Ctrl+Maiusc+T`).

**Motori:** **Bing Translate** (predefinito), **Google Translate**. Entrambi supportano **108 lingue di destinazione**.

---

## Scorciatoie da tastiera

| Scorciatoia | Mac | Azione |
|-------------|-----|--------|
| `Alt+Shift+A` | `Ctrl+Shift+A` | Attiva/disattiva Tashkeel |
| `Alt+Shift+S` | `Ctrl+Shift+S` | Leggi selezione |
| `Alt+Shift+T` | `Ctrl+Shift+T` | Traduci selezione |

> **Suggerimento:** personalizzare in `chrome://extensions/shortcuts`.

---

## Impostazioni

| Impostazione | Descrizione |
|--------------|-------------|
| **Abilita Tashkeel** | Interruttore principale |
| **Tashkeel pagina intera** | Vocali per tutte le parole arabe |
| **Modalità hover** | Dizionario, Tooltip o Disattivato |
| **Mostra forme I'rab** | Desinenze grammaticali |
| **Velocità voce** | Velocità di lettura |
| **Motore di traduzione** | Bing o Google |
| **Lingua di destinazione** | Lingua della traduzione |
| **Rilevamento intelligente PDF** | Reindirizza URL PDF al lettore integrato |

---

## FAQ

**Perché non funziona su alcune pagine?**  
Per sicurezza, le estensioni non girano su `chrome://`, impostazioni del browser né Chrome Web Store.

**Nessun audio dalla sintesi vocale?**  
Controllare volume e voci arabe installate. La compatibilità varia.

**Non rileva l'arabo.**  
Testo come immagine o codifica non standard può fallire.

**Traduzione non funziona?**  
Serve la connessione. In caso di errore Bing, provare Google nelle impostazioni.

**Come aprire un PDF con Arabic Reader?**  
«Apri lettore PDF», menu contestuale sul link, oppure «Rilevamento intelligente PDF».

---

## Collegamenti

- [Privacy policy](../privacy-policy)
- [Supporto e feedback](../support)

---
