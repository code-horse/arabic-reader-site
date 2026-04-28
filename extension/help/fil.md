---
layout: bare
title: Arabic Reader - Gabay sa Gumagamit
lang: fil
---
# Arabic Reader - Gabay sa Gumagamit

> Bersyon: v1.0.0

## Panimula

Ang Arabic Reader ay isang extension ng browser na idinisenyo para sa mga nag-aaral ng Arabic. Nagdaragdag ito ng Tashkeel (mga vowel mark / حركات) sa mga salitang Arabic sa mga web page at PDF, na nagbibigay ng awtomatikong pag-vocalization, isang hover na diksyunaryo na may root analysis at grammatical form, text-to-speech, at mga feature ng pagsasalin — na tumutulong sa iyong matuto ng Arabic na pagbigkas at grammar nang mas madali.

---

## Pangunahing Mga Tampok

- **Awtomatikong Tashkeel** — Nagdaragdag ng mga marka ng patinig (fathah, kasrah, dammah, sukun, shadda, tanween) sa mga salitang Arabe sa anumang web page
- **Whole Page Mode** — Isang pag-click Tashkeel para sa lahat ng salitang Arabic sa pahina
- **Hover Dictionary** — Mag-hover sa mga salita upang makita ang vocalization, mga kahulugan, root analysis, at I'rab na mga form; pumili sa pagitan ng Dictionary mode, Tooltip mode, o Off
- **I'rab Pagsusuri** — Ipakita ang mga grammatical case endings (nominative, accusative, genitive) para sa mga naaangkop na salita
- **Text-to-Speech** — Arabic TTS na may word-by-word karaoke highlighting (ar-SA voice)
- **Selection Speech** — Pumili ng anumang text, lalabas ang isang compact toolbar na may mga button na magsalita at magsalin
- **Translation** — Pumili ng anumang text, i-click ang translate para makakuha ng agarang pagsasalin sa pamamagitan ng Bing o Google Translate (108 na wika)
- **PDF Reader** — Built-in na RTL PDF viewer na may Tashkeel suporta sa anotasyon
- **Smart Detection** — Awtomatikong Arabic text detection at PDF smart redirect
- **Root Extraction** — Kilalanin ang mga ugat ng salita para sa mas mahusay na pag-unawa sa Arabic morphology
- **Mga Shortcut sa Keyboard** — Mabilis na pag-access sa mga pangunahing tampok
- **Multilingual Interface** — Arabic, English, at Chinese UI

---

## Paano Gamitin

### Hakbang 1: I-install ang Extension

I-install ang **Arabic Reader** mula sa [Chrome Web Store](https://chromewebstore.google.com/), o i-load ito nang lokal sa developer mode.

### Hakbang 2: Buksan ang Anumang Web Page

Bisitahin ang anumang web page na naglalaman ng Arabic na nilalaman.

### Hakbang 3: Paganahin ang Tashkeel

I-click ang icon ng extension sa toolbar ng iyong browser. I-toggle ang "Paganahin ang Tashkeel" sa, pagkatapos ay i-toggle ang "Buong Pahina Tashkeel" upang i-annotate ang lahat ng salitang Arabic sa pahina.

### Hakbang 4: Tingnan ang Mga Anotasyon

Mag-hover sa mga salita upang makita ang Tashkeel mga tooltip na may vocalization, mga kahulugan, at pagbigkas. I-click ang icon ng speaker para marinig ang salita.

### Hakbang 5: Magsalita at Magsalin ng Napiling Teksto

Pumili ng anumang Arabic text gamit ang iyong mouse. Lumilitaw ang isang compact toolbar malapit sa pagpili na may dalawang button:
- **Speaker** — Binabasa nang malakas ang napiling text gamit ang karaoke-style na word-by-word na pag-highlight
- **Translate** — Nagpapakita ng inline na bula ng pagsasalin sa ibaba ng toolbar

> **Tip:** I-click ang icon ng extension sa iyong browser toolbar upang buksan ang panel ng mga setting at isaayos ang hover mode, speech rate, translation engine, at higit pa.

---

## Buong Pahina Tashkeel Mode

Kapag naka-enable ang buong page Tashkeel mode, bawat salitang Arabic sa page ay madaragdagan ng mga patinig. Gumagamit ang extension ng smart detection para matukoy ang mga Arabic text block at inilalapat ang Tashkeel gamit ang naka-bundle na diksyunaryo at NLP algorithm nito.

---

## Hover Dictionary

Kasama sa extension ang isang built-in na diksyunaryo ng Arabic. Maaari kang pumili mula sa maraming hover mode sa mga setting:

| Mode | Pag-uugali |
|------|----------|
| **Diksyunaryo** | Ipinapakita ng hover ang Tashkeel + mga kahulugan + ugat + I'rab + button ng pagbigkas |
| **Tooltip** | Ipinapakita ng hover ang Tashkeel + button ng pagbigkas (walang mga kahulugan) |
| **Naka-off** | Walang hover effect |

Sa **Dictionary mode**, ipinapakita ng tooltip ang:
- Ang salitang may buong vocalization (Tashkeel)
- Isang pindutan ng pagbigkas (i-click upang marinig)
- Mga kahulugan ng salita
- Root analysis (tatlong titik na ugat)
- I'rab (grammatical case) form kapag pinagana

---

## PDF Reader

Ang Arabic Reader ay may kasamang built-in na PDF reader na may ganap na suporta sa RTL na nagbibigay-daan sa iyong magbasa ng mga Arabic PDF na dokumento na may Tashkeel na mga anotasyon.

### Pagbubukas ng PDF

**Paraan 1: Mula sa Popup**  
I-click ang icon ng extension, pagkatapos ay i-click ang "Buksan ang PDF Reader". I-drag at i-drop ang isang PDF file o i-click ang "Pumili ng File" upang magbukas ng lokal na PDF. Maaari ka ring mag-paste ng PDF URL.

**Paraan 2: Menu ng Konteksto**  
I-right-click ang anumang link na `.pdf` sa isang web page at piliin ang "Buksan ang PDF gamit ang Arabic Reader".

**Paraan 3: Awtomatikong Detection**  
Kapag pinagana ang "PDF Smart Detection" sa mga setting, awtomatikong nire-redirect ng extension ang mga `.pdf` na URL sa built-in na reader.

### Mga Tampok ng PDF Reader

- **Tashkeel Mga Anotasyon** — Gumagana ang lahat ng feature ng anotasyon sa tekstong PDF
- **Click Dictionary** — Mag-click sa anumang salita upang makita ang kahulugan nito
- **Selection Toolbar** — Pumili ng text na sasabihin, isasalin, o kokopyahin
- **Sidebar** — Outline ng talaan ng nilalaman at mga thumbnail ng pahina
- **Paghahanap** — Maghanap ng teksto sa PDF
- **Tema** — Madilim, Maliwanag, at Sepia na mga tema sa pagbabasa
- **Zoom** — Maramihang mga antas ng zoom kabilang ang Auto, Page Fit, at Page Width
- **RTL Layout** — Buong kanan-papuntang-kaliwang suporta

---

## Text-to-Speech

Ginagamit ng extension ang built-in na Arabic TTS voice (ar-SA) ng Chrome para sa pagbigkas.

**Single Word:** Mag-hover sa isang salita at i-click ang speaker button sa tooltip.

**Selection Speech:** Pumili ng anumang Arabic text. Lumilitaw ang isang lumulutang na toolbar na may speaker button — i-click ito upang basahin nang malakas gamit ang karaoke-style na word-by-word na pag-highlight.

**Right-Click Menu:** Pumili ng text, i-right click at piliin ang "Speak Selection".

**Keyboard Shortcut:** Pumili ng text at pindutin ang `Alt+Shift+S` (Mac: `Ctrl+Shift+S`).

---

## Pagsasalin

Pumili ng anumang teksto sa pahina at gamitin ang tampok na pagsasalin upang makakuha ng mga agarang pagsasalin.

**Paraan 1: Selection Toolbar**  
Pumili ng text, pagkatapos ay i-click ang button na isalin sa toolbar.

**Paraan 2: Right-Click Menu**  
Pumili ng text, i-right click at piliin ang "Translate Selection".

**Paraan 3: Keyboard Shortcut**  
Pumili ng text at pindutin ang `Alt+Shift+T` (Mac: `Ctrl+Shift+T`).

**Translation Engines:**
- **Bing Translate** (default) — Pinapatakbo ng Microsoft Translator
- **Google Translate** — Pinapatakbo ng Google

Parehong engine ang sumusuporta sa **108 target na wika**.

---

## Mga Shortcut sa Keyboard

| Shortcut | Mac Shortcut | Aksyon |
|----------|-------------|--------|
| `Alt+Shift+A` | `Ctrl+Shift+A` | I-toggle ang Tashkeel na mga anotasyon sa on/off |
| `Alt+Shift+S` | `Ctrl+Shift+S` | Sabihin ang piniling teksto |
| `Alt+Shift+T` | `Ctrl+Shift+T` | Isalin ang napiling teksto |

> **Tip:** Maaari mong i-customize ang mga shortcut na ito sa Chrome sa `chrome://extensions/shortcuts`.

---

## Gabay sa Mga Setting

| Setting | Paglalarawan |
|---------|-------------|
| **Paganahin ang Tashkeel** | Master switch para paganahin o huwag paganahin ang Tashkeel tampok na anotasyon |
| **Buong Pahina Tashkeel** | Kapag pinagana, nagdaragdag ng mga marka ng patinig sa lahat ng salitang Arabic sa pahina |
| **Hover Mode** | Pumili ng gawi sa pag-hover: Diksyunaryo (mga kahulugan + audio), Tooltip (Tashkeel + audio), o Naka-off |
| **Ipakita ang I'rab Mga Form** | Ipakita ang mga grammatical case ending para sa mga naaangkop na salita |
| **Speech Rate** | Ayusin ang bilis ng pagbabasa ng pangungusap |
| **Translation Engine** | Pumili sa pagitan ng Bing Translate at Google Translate |
| **Target na Wika** | Itakda ang target na wika ng pagsasalin |
| **PDF Smart Detection** | Kapag pinagana, awtomatikong nire-redirect ang mga PDF URL sa built-in na reader |

---

## FAQ

**T: Bakit hindi ito gumagana sa ilang page?**  
A: Para sa mga kadahilanang panseguridad, hindi maaaring tumakbo ang mga extension ng browser sa mga espesyal na pahina tulad ng `chrome://`, mga setting ng browser, o ang Chrome Web Store.

**T: Walang tunog mula sa text-to-speech?**  
A: Pakisuri ang mga setting ng volume ng iyong system at tiyaking naka-install ang mga Arabic voice pack. Ang suporta sa pagsasalita ay nag-iiba-iba sa mga browser at operating system.

**Q: Ang extension ay hindi nakakakita ng Arabic na text.**  
A: Gumagamit ang extension ng smart detection para maghanap ng mga Arabic text block. Kung ang teksto ay nai-render bilang mga imahe o gumagamit ng hindi karaniwang pag-encode, maaaring hindi ito matukoy.

**T: Hindi gumagana ang pagsasalin?**  
A: Ang pagsasalin ay nangangailangan ng koneksyon sa internet. Kung nabigo ang Bing Translate, subukang lumipat sa Google Translate sa mga setting.

**T: Paano ako magbubukas ng PDF gamit ang Arabic Reader?**  
A: I-click ang "Open PDF Reader" sa popup, i-right click ang isang PDF link at piliin ang "Open PDF with Arabic Reader", o paganahin ang "PDF Smart Detection" sa mga setting.

---

## Mga Kaugnay na Link

- [Patakaran sa Privacy](../privacy-policy)
- [Suporta at Feedback](../support)

---

---
