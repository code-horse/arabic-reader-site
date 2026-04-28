---
layout: bare
title: Arabic Reader - Guia de l'usuari
lang: ca
---
# Arabic Reader - Guia de l'usuari

> Versió: v1.0.0

## Introducció

Arabic Reader és una extensió del navegador dissenyada per a estudiants d'àrab. Afegeix Tashkeel (marks vocals / حركات) a les paraules àrabs a les pàgines web i als PDF, proporcionant vocalització automàtica, un diccionari flotant amb anàlisi d'arrel i formes gramaticals, característiques de text a veu i traducció, ajudant-vos a aprendre la pronunciació i la gramàtica àrabs més fàcilment.

---

## Característiques principals

- **Automàtic Tashkeel** — Afegeix marques de vocals (fathah, kasrah, dammah, sukun, shadda, tanween) a les paraules àrabs a qualsevol pàgina web
- **Mode de pàgina sencera**: feu clic a Tashkeel per a totes les paraules àrabs de la pàgina
- **Diccionari del cursor**: passeu el cursor per sobre de les paraules per veure la vocalització, les definicions, l'anàlisi de les arrels i les formes I'rab; tria entre el mode de diccionari, el mode d'informació eines o desactivat
- **I'rab Anàlisi** — Mostra les terminacions de majúscules i minúscules gramaticals (nominatiu, acusatiu, genitiu) per a les paraules aplicables
- **Text a veu** — TTS àrab amb ressaltat de karaoke paraula per paraula (veu ar-SA)
- **Discurs de selecció**: seleccioneu qualsevol text, apareixerà una barra d'eines compacta amb botons de parlar i traduir
- **Traducció**: seleccioneu qualsevol text, feu clic a traduir per obtenir una traducció instantània mitjançant Bing o Google Translate (108 idiomes)
- **Lector de PDF**: visualitzador de PDF RTL integrat amb suport d'anotacions Tashkeel
- **Detecció intel·ligent**: detecció automàtica de text àrab i redirecció intel·ligent de PDF
- **Extracció d'arrels** — Identificar les arrels de les paraules per entendre millor la morfologia àrab
- **Dreceres de teclat** — Accés ràpid a les funcions bàsiques
- **Interfície multilingüe**: interfície d'usuari àrab, anglès i xinès

---

## Com s'utilitza

### Pas 1: instal·leu l'extensió

Instal·leu **Arabic Reader** des de [Chrome Web Store](https://chromewebstore.google.com/), o carregueu-lo localment en mode de desenvolupador.

### Pas 2: obriu qualsevol pàgina web

Visiteu qualsevol pàgina web que contingui contingut àrab.

### Pas 3: habiliteu Tashkeel

Feu clic a la icona de l'extensió a la barra d'eines del vostre navegador. Activeu "Activa Tashkeel" i, a continuació, activeu "Pàgina sencera Tashkeel" per anotar totes les paraules àrabs de la pàgina.

### Pas 4: visualitza les anotacions

Passeu el cursor per sobre de les paraules per veure els consells eines de Tashkeel amb vocalització, definicions i pronunciació. Feu clic a la icona de l'altaveu per escoltar la paraula.

### Pas 5: parla i tradueix el text seleccionat

Seleccioneu qualsevol text àrab amb el ratolí. Una barra d'eines compacta apareix a prop de la selecció amb dos botons:
- **Altaveu**: llegeix el text seleccionat en veu alta amb ressaltat paraula per paraula a l'estil karaoke
- **Tradueix** — Mostra una bombolla de traducció en línia a sota de la barra d'eines

> **Consell:** Feu clic a la icona de l'extensió a la barra d'eines del navegador per obrir el tauler de configuració i ajustar el mode de desplaçament del cursor, la velocitat de veu, el motor de traducció i molt més.

---

## Pàgina sencera Mode Tashkeel

Quan el mode Tashkeel de pàgina sencera està habilitat, cada paraula àrab de la pàgina s'afegeixen marques de vocals. L'extensió utilitza la detecció intel·ligent per identificar blocs de text àrab i aplica Tashkeel utilitzant el seu diccionari i els algorismes de NLP.

---

## Hover Dictionary

L'extensió inclou un diccionari àrab integrat. Podeu triar entre diversos modes de desplaçament del cursor a la configuració:

| Mode | Comportament |
|------|----------|
| **Diccionari** | Passar el cursor mostra Tashkeel + definicions + arrel + I'rab + botó de pronunciació |
| **Informació eina** | Passar el cursor mostra Tashkeel + botó de pronunciació (sense definicions) |
| **Desactivat** | Sense efecte flotant |

Al **mode de diccionari**, la informació sobre eines mostra:
- La paraula amb vocalització completa (Tashkeel)
- Un botó de pronunciació (feu clic per escoltar)
- Definicions de paraules
- Anàlisi d'arrel (arrel de tres lletres)
- Formes I'rab (cas gramatical) quan estan habilitades

---

## Lector de PDF

Arabic Reader inclou un lector de PDF integrat amb suport RTL complet que us permet llegir documents PDF àrabs amb anotacions Tashkeel.

### Obrint un PDF

**Mètode 1: des de la finestra emergent**  
Feu clic a la icona de l'extensió i, a continuació, feu clic a "Obre el lector de PDF". Arrossegueu i deixeu anar un fitxer PDF o feu clic a "Tria un fitxer" per obrir un PDF local. També podeu enganxar un URL PDF.

**Mètode 2: menú contextual**  
Feu clic amb el botó dret a qualsevol enllaç `.pdf` d'una pàgina web i trieu "Obre PDF amb Arabic Reader".

**Mètode 3: detecció automàtica**  
Quan la "Detecció intel·ligent de PDF" està activada a la configuració, l'extensió redirigeix automàticament els URL `.pdf` al lector integrat.

### Funcions del lector de PDF

- **Tashkeel Anotacions** — Totes les funcions d'anotació funcionen amb text PDF
- **Feu clic al Diccionari**: feu clic a qualsevol paraula per veure'n la definició
- **Barra d'eines de selecció** — Seleccioneu el text per parlar, traduir o copiar
- **Barra lateral** — Esquema de la taula de continguts i miniatures de les pàgines
- **Cerca**: cerca text al PDF
- **Temes**: temes de lectura foscos, clars i sèpia
- **Zoom**: diversos nivells de zoom, inclosos Automàtic, Ajust de pàgina i Amplada de pàgina
- **Disposició RTL**: suport complet de dreta a esquerra

---

## Text a veu

L'extensió utilitza la veu TTS àrab integrada de Chrome (ar-SA) per a la pronunciació.

**Paraula única:** passeu el cursor per sobre d'una paraula i feu clic al botó de l'altaveu a la informació sobre eines.

**Discurs de selecció:** Seleccioneu qualsevol text àrab. Apareix una barra d'eines flotant amb un botó d'altaveu; feu-hi clic per llegir-lo en veu alta amb ressaltat paraula per paraula a l'estil de karaoke.

**Menú de clic amb el botó dret:** Seleccioneu el text, feu clic amb el botó dret del ratolí i trieu "Parla la selecció".

**Drecera de teclat:** Seleccioneu text i premeu `Alt+Shift+S` (Mac: `Ctrl+Shift+S`).

---

## Traducció

Seleccioneu qualsevol text de la pàgina i utilitzeu la funció de traducció per obtenir traduccions instantànies.

**Mètode 1: barra d'eines de selecció**  
Seleccioneu el text i, a continuació, feu clic al botó de traducció de la barra d'eines.

**Mètode 2: menú de clic dret**  
Seleccioneu el text, feu clic amb el botó dret i trieu "Tradueix la selecció".

**Mètode 3: drecera de teclat**  
Seleccioneu el text i premeu `Alt+Shift+T` (Mac: `Ctrl+Shift+T`).

**Motors de traducció:**
- **Bing Translate** (per defecte) — Impulsat per Microsoft Translator
- **Google Translate** — Amb la tecnologia de Google

Tots dos motors admeten **108 idiomes de destinació**.

---

## Dreceres de teclat

| Drecera | Drecera de Mac | Acció |
|----------|-------------|--------|
| `Alt+Shift+A` | `Ctrl+Shift+A` | Activa/desactiva les anotacions Tashkeel |
| `Alt+Shift+S` | `Ctrl+Shift+S` | Pronuncia el text seleccionat |
| `Alt+Shift+T` | `Ctrl+Shift+T` | Tradueix el text seleccionat |

> **Consell:** podeu personalitzar aquestes dreceres a Chrome a `chrome://extensions/shortcuts`.

---

## Guia de configuració

| Configuració | Descripció |
|---------|--------------|
| **Activa Tashkeel** | Interruptor principal per activar o desactivar la funció d'anotació Tashkeel |
| **Pàgina sencera Tashkeel** | Quan està activat, afegeix marques de vocals a totes les paraules àrabs de la pàgina |
| **Mode Hover** | Trieu el comportament de passar el cursor: diccionari (definicions + àudio), informació sobre eines (Tashkeel + àudio) o desactivat |
| **Mostra els formularis I'rab** | Mostra les terminacions de minúscules i minúscules gramaticals per a les paraules aplicables |
| **Taxa de parla** | Ajustar la velocitat de lectura de la frase |
| **Motor de traducció** | Trieu entre Bing Translate i Google Translate |
| **Idioma objectiu** | Estableix l'idioma de destinació de la traducció |
| **PDF Smart Detection** | Quan està activat, redirigeix ​​automàticament els URL PDF al lector integrat |

---

## PMF

**P: Per què no funciona en algunes pàgines?**  
R: Per motius de seguretat, les extensions del navegador no poden executar-se en pàgines especials com `chrome://`, la configuració del navegador o el Chrome Web Store.

**P: No hi ha so del text a veu?**  
R: Comproveu la configuració del volum del vostre sistema i assegureu-vos que els paquets de veu àrab estan instal·lats. El suport de veu varia segons els navegadors i els sistemes operatius.

**P: L'extensió no detecta text àrab.**  
R: L'extensió utilitza la detecció intel·ligent per trobar blocs de text àrab. Si el text es representa com a imatges o utilitza una codificació no estàndard, és possible que no es detecti.

**P: La traducció no funciona?**  
R: La traducció requereix connexió a Internet. Si Bing Translate falla, proveu de canviar a Google Translate a la configuració.

**P: Com puc obrir un PDF amb Arabic Reader?**  
R: Feu clic a "Obre PDF Reader" a la finestra emergent, feu clic amb el botó dret a un enllaç PDF i trieu "Obre PDF amb Arabic Reader", o activeu "PDF Smart Detection" a la configuració.

---

## Enllaços relacionats

- [Política de privadesa](../privacy-policy)
- [Suport i comentaris](../support)

---

---
