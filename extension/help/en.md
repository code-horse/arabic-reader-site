---
layout: bare
title: Arabic Reader Extension - User Guide
lang: en
---

# Arabic Reader - User Guide

> Version: v1.0.0

## Introduction

Arabic Reader is a browser extension designed for Arabic learners. It adds Tashkeel (vowel marks / حركات) to Arabic words on web pages and PDFs, providing automatic vocalization, a hover dictionary with root analysis and grammatical forms, text-to-speech, and translation features — helping you learn Arabic pronunciation and grammar more easily.

---

## Main Features

- **Automatic Tashkeel** — Adds vowel marks (fathah, kasrah, dammah, sukun, shadda, tanween) to Arabic words on any web page
- **Whole Page Mode** — One-click Tashkeel for all Arabic words on the page
- **Hover Dictionary** — Hover over words to see vocalization, definitions, root analysis, and I'rab forms; choose between Dictionary mode, Tooltip mode, or Off
- **I'rab Analysis** — Display grammatical case endings (nominative, accusative, genitive) for applicable words
- **Text-to-Speech** — Arabic TTS with word-by-word karaoke highlighting (ar-SA voice)
- **Selection Speech** — Select any text, a compact toolbar appears with speak and translate buttons
- **Translation** — Select any text, click translate to get instant translation via Bing or Google Translate (108 languages)
- **PDF Reader** — Built-in RTL PDF viewer with Tashkeel annotation support
- **Smart Detection** — Automatic Arabic text detection and PDF smart redirect
- **Root Extraction** — Identify word roots for better understanding of Arabic morphology
- **Keyboard Shortcuts** — Quick access to core features
- **Multilingual Interface** — Arabic, English, and Chinese UI

---

## How to Use

### Step 1: Install the Extension

Install **Arabic Reader** from the [Chrome Web Store](https://chromewebstore.google.com/), or load it locally in developer mode.

### Step 2: Open Any Web Page

Visit any web page containing Arabic content.

### Step 3: Enable Tashkeel

Click the extension icon in your browser toolbar. Toggle "Enable Tashkeel" on, then toggle "Whole Page Tashkeel" to annotate all Arabic words on the page.

### Step 4: View Annotations

Hover over words to see Tashkeel tooltips with vocalization, definitions, and pronunciation. Click the speaker icon to hear the word.

### Step 5: Speak and Translate Selected Text

Select any Arabic text with your mouse. A compact toolbar appears near the selection with two buttons:
- **Speaker** — Reads the selected text aloud with karaoke-style word-by-word highlighting
- **Translate** — Shows an inline translation bubble below the toolbar

> **Tip:** Click the extension icon in your browser toolbar to open the settings panel and adjust hover mode, speech rate, translation engine, and more.

---

## Whole Page Tashkeel Mode

When whole page Tashkeel mode is enabled, every Arabic word on the page gets vowel marks added. The extension uses smart detection to identify Arabic text blocks and applies Tashkeel using its bundled dictionary and NLP algorithms.

---

## Hover Dictionary

The extension includes a built-in Arabic dictionary. You can choose from multiple hover modes in the settings:

| Mode | Behavior |
|------|----------|
| **Dictionary** | Hover shows Tashkeel + definitions + root + I'rab + pronunciation button |
| **Tooltip** | Hover shows Tashkeel + pronunciation button (no definitions) |
| **Off** | No hover effect |

In **Dictionary mode**, the tooltip displays:
- The word with full vocalization (Tashkeel)
- A pronunciation button (click to hear)
- Word definitions
- Root analysis (three-letter root)
- I'rab (grammatical case) forms when enabled

---

## PDF Reader

Arabic Reader includes a built-in PDF reader with full RTL support that allows you to read Arabic PDF documents with Tashkeel annotations.

### Opening a PDF

**Method 1: From the Popup**  
Click the extension icon, then click "Open PDF Reader". Drag & drop a PDF file or click "Choose File" to open a local PDF. You can also paste a PDF URL.

**Method 2: Context Menu**  
Right-click any `.pdf` link on a web page and choose "Open PDF with Arabic Reader".

**Method 3: Automatic Detection**  
When "PDF Smart Detection" is enabled in settings, the extension automatically redirects `.pdf` URLs to the built-in reader.

### PDF Reader Features

- **Tashkeel Annotations** — All annotation features work on PDF text
- **Click Dictionary** — Click on any word to see its definition
- **Selection Toolbar** — Select text to speak, translate, or copy
- **Sidebar** — Table of contents outline and page thumbnails
- **Search** — Search for text in the PDF
- **Themes** — Dark, Light, and Sepia reading themes
- **Zoom** — Multiple zoom levels including Auto, Page Fit, and Page Width
- **RTL Layout** — Full right-to-left support

---

## Text-to-Speech

The extension uses Chrome's built-in Arabic TTS voice (ar-SA) for pronunciation.

**Single Word:** Hover over a word and click the speaker button in the tooltip.

**Selection Speech:** Select any Arabic text. A floating toolbar appears with a speaker button — click it to read aloud with karaoke-style word-by-word highlighting.

**Right-Click Menu:** Select text, right-click and choose "Speak Selection".

**Keyboard Shortcut:** Select text and press `Alt+Shift+S` (Mac: `Ctrl+Shift+S`).

---

## Translation

Select any text on the page and use the translation feature to get instant translations.

**Method 1: Selection Toolbar**  
Select text, then click the translate button in the toolbar.

**Method 2: Right-Click Menu**  
Select text, right-click and choose "Translate Selection".

**Method 3: Keyboard Shortcut**  
Select text and press `Alt+Shift+T` (Mac: `Ctrl+Shift+T`).

**Translation Engines:**
- **Bing Translate** (default) — Powered by Microsoft Translator
- **Google Translate** — Powered by Google

Both engines support **108 target languages**.

---

## Keyboard Shortcuts

| Shortcut | Mac Shortcut | Action |
|----------|-------------|--------|
| `Alt+Shift+A` | `Ctrl+Shift+A` | Toggle Tashkeel annotations on/off |
| `Alt+Shift+S` | `Ctrl+Shift+S` | Speak selected text |
| `Alt+Shift+T` | `Ctrl+Shift+T` | Translate selected text |

> **Tip:** You can customize these shortcuts in Chrome at `chrome://extensions/shortcuts`.

---

## Settings Guide

| Setting | Description |
|---------|-------------|
| **Enable Tashkeel** | Master switch to enable or disable the Tashkeel annotation feature |
| **Whole Page Tashkeel** | When enabled, adds vowel marks to all Arabic words on the page |
| **Hover Mode** | Choose hover behavior: Dictionary (definitions + audio), Tooltip (Tashkeel + audio), or Off |
| **Show I'rab Forms** | Display grammatical case endings for applicable words |
| **Speech Rate** | Adjust the speed of sentence reading |
| **Translation Engine** | Choose between Bing Translate and Google Translate |
| **Target Language** | Set the translation target language |
| **PDF Smart Detection** | When enabled, automatically redirects PDF URLs to the built-in reader |

---

## FAQ

**Q: Why doesn't it work on some pages?**  
A: For security reasons, browser extensions cannot run on special pages like `chrome://`, browser settings, or the Chrome Web Store.

**Q: No sound from text-to-speech?**  
A: Please check your system volume settings and ensure Arabic voice packs are installed. Speech support varies across browsers and operating systems.

**Q: The extension doesn't detect Arabic text.**  
A: The extension uses smart detection to find Arabic text blocks. If the text is rendered as images or uses non-standard encoding, it may not be detected.

**Q: Translation not working?**  
A: Translation requires an internet connection. If Bing Translate fails, try switching to Google Translate in the settings.

**Q: How do I open a PDF with Arabic Reader?**  
A: Click "Open PDF Reader" in the popup, right-click a PDF link and choose "Open PDF with Arabic Reader", or enable "PDF Smart Detection" in settings.

---

## Related Links

- [Privacy Policy](../privacy-policy)
- [Support & Feedback](../support)

---
