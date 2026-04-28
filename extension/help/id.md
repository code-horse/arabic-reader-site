---
layout: bare
title: Arabic Reader - Panduan Pengguna
lang: id
---
# Arabic Reader - Panduan Pengguna

> Versi: v1.0.0

## Pendahuluan

Arabic Reader adalah ekstensi browser yang dirancang untuk pelajar bahasa Arab. Ia menambahkan Tashkeel (tanda vokal / حركات) ke kata-kata Arab di halaman web dan PDF, menyediakan vokalisasi otomatis, kamus hover dengan analisis akar kata dan bentuk tata bahasa, text-to-speech, dan fitur terjemahan — membantu Anda mempelajari pengucapan dan tata bahasa Arab dengan lebih mudah.

---

## Fitur Utama

- **Otomatis Tashkeel** — Menambahkan tanda vokal (fathah, kasrah, dammah, sukun, shadda, tanween) ke kata-kata Arab di halaman web mana pun
- **Mode Seluruh Halaman** — Sekali klik Tashkeel untuk semua kata Arab di halaman
- **Hover Dictionary** — Arahkan kursor ke kata untuk melihat vokalisasi, definisi, analisis akar kata, dan bentuk I'rab; pilih antara mode Kamus, mode Tooltip, atau Mati
- **I'rab Analisis** — Menampilkan akhiran kasus tata bahasa (nominatif, akusatif, genitif) untuk kata-kata yang dapat diterapkan
- **Text-to-Speech** — TTS Arab dengan highlight karaoke kata demi kata (suara ar-SA)
- **Pilihan Pidato** — Pilih teks apa pun, bilah alat ringkas muncul dengan tombol bicara dan terjemahkan
- **Terjemahan** — Pilih teks apa saja, klik terjemahkan untuk mendapatkan terjemahan instan melalui Bing atau Google Translate (108 bahasa)
- **Pembaca PDF** — Penampil PDF RTL bawaan dengan dukungan anotasi Tashkeel
- **Deteksi Cerdas** — Deteksi teks Arab otomatis dan pengalihan cerdas PDF
- **Ekstraksi Akar** — Identifikasi akar kata untuk pemahaman yang lebih baik tentang morfologi bahasa Arab
- **Pintasan Keyboard** — Akses cepat ke fitur inti
- **Antarmuka Multibahasa** — UI Arab, Inggris, dan Mandarin

---

## Cara Menggunakan

### Langkah 1: Instal Ekstensi

Instal **Arabic Reader** dari [Chrome Web Store](https://chromewebstore.google.com/), atau muat secara lokal dalam mode pengembang.

### Langkah 2: Buka Halaman Web Apa Pun

Kunjungi halaman web mana pun yang berisi konten berbahasa Arab.

### Langkah 3: Aktifkan Tashkeel

Klik ikon ekstensi di toolbar browser Anda. Aktifkan "Aktifkan Tashkeel", lalu aktifkan "Seluruh Halaman Tashkeel" untuk memberi anotasi pada semua kata Arab di halaman.

### Langkah 4: Lihat Anotasi

Arahkan kursor ke kata untuk melihat Tashkeel tooltips dengan vokalisasi, definisi, dan pengucapan. Klik ikon speaker untuk mendengar kata tersebut.

### Langkah 5: Ucapkan dan Terjemahkan Teks yang Dipilih

Pilih teks Arab apa pun dengan mouse Anda. Toolbar ringkas muncul di dekat pilihan dengan dua tombol:
- **Speaker** — Membaca teks yang dipilih dengan lantang dengan penyorotan kata demi kata bergaya karaoke
- **Terjemahkan** — Menampilkan gelembung terjemahan sebaris di bawah toolbar

> **Tips:** Klik ikon ekstensi di toolbar browser Anda untuk membuka panel pengaturan dan menyesuaikan mode hover, kecepatan bicara, mesin terjemahan, dan banyak lagi.

---

## Seluruh Halaman Tashkeel Mode

Ketika mode Tashkeel seluruh halaman diaktifkan, setiap kata Arab di halaman akan ditambahkan tanda vokal. Ekstensi ini menggunakan deteksi cerdas untuk mengidentifikasi blok teks Arab dan menerapkan Tashkeel menggunakan kamus yang disertakan dan algoritme NLP.

---

## Arahkan Kamus

Ekstensi ini mencakup kamus bahasa Arab bawaan. Anda dapat memilih dari beberapa mode hover di pengaturan:

| Modus | Perilaku |
|------|----------|
| **Kamus** | Arahkan kursor ke Tashkeel + definisi + root + I'rab + tombol pengucapan |
| **Keterangan alat** | Arahkan kursor menunjukkan Tashkeel + tombol pengucapan (tidak ada definisi) |
| **Mati** | Tidak ada efek hover |

Dalam **Mode Kamus**, tooltip menampilkan:
- Kata dengan vokalisasi penuh (Tashkeel)
- Tombol pengucapan (klik untuk mendengar)
- Definisi kata
- Analisis akar (akar tiga huruf)
- Bentuk I'rab (huruf tata bahasa) saat diaktifkan

---

## Pembaca PDF

Arabic Reader menyertakan pembaca PDF internal dengan dukungan RTL penuh yang memungkinkan Anda membaca dokumen PDF berbahasa Arab dengan anotasi Tashkeel.

### Membuka PDF

**Metode 1: Dari Popup**  
Klik ikon ekstensi, lalu klik "Buka PDF Reader". Seret & letakkan file PDF atau klik "Pilih File" untuk membuka PDF lokal. Anda juga dapat menempelkan URL PDF.

**Metode 2: Menu Konteks**  
Klik kanan link `.pdf` mana pun di halaman web dan pilih "Buka PDF dengan Arabic Reader".

**Metode 3: Deteksi Otomatis**  
Ketika "Deteksi Cerdas PDF" diaktifkan di pengaturan, ekstensi secara otomatis mengalihkan URL `.pdf` ke pembaca internal.

### Fitur Pembaca PDF

- **Tashkeel Anotasi** — Semua fitur anotasi berfungsi pada teks PDF
- **Klik Kamus** — Klik kata mana saja untuk melihat definisinya
- **Seleksi Toolbar** — Pilih teks untuk diucapkan, diterjemahkan, atau disalin
- **Bilah Samping** — Garis besar daftar isi dan thumbnail halaman
- **Pencarian** — Mencari teks dalam PDF
- **Tema** — Tema bacaan Gelap, Terang, dan Sepia
- **Zoom** — Beberapa tingkat zoom termasuk Otomatis, Kesesuaian Halaman, dan Lebar Halaman
- **RTL Layout** — Dukungan penuh dari kanan ke kiri

---

## Teks-ke-Ucapan

Ekstensi ini menggunakan suara TTS Arab (ar-SA) bawaan Chrome untuk pengucapan.

**Satu Kata:** Arahkan kursor ke sebuah kata dan klik tombol speaker di tooltip.

**Pilihan Pidato:** Pilih teks Arab apa saja. Bilah alat mengambang muncul dengan tombol pengeras suara — klik untuk membacakan dengan lantang dengan penyorotan kata demi kata bergaya karaoke.

**Menu Klik Kanan:** Pilih teks, klik kanan dan pilih "Ucapkan Pilihan".

**Pintasan Keyboard:** Pilih teks dan tekan `Alt+Shift+S` (Mac: `Ctrl+Shift+S`).

---

## Terjemahan

Pilih teks apa pun di halaman dan gunakan fitur terjemahan untuk mendapatkan terjemahan instan.

**Metode 1: Bilah Alat Seleksi**  
Pilih teks, lalu klik tombol terjemahkan di toolbar.

**Metode 2: Menu Klik Kanan**  
Pilih teks, klik kanan dan pilih "Terjemahkan Pilihan".

**Metode 3: Pintasan Keyboard**  
Pilih teks dan tekan `Alt+Shift+T` (Mac: `Ctrl+Shift+T`).

**Mesin Terjemahan:**
- **Bing Translate** (default) — Didukung oleh Microsoft Translator
- **Google Translate** — Didukung oleh Google

Kedua mesin mendukung **108 bahasa target**.

---

## Pintasan Papan Ketik

| Pintasan | Pintasan Mac | Aksi |
|----------|-------------|--------|
| `Alt+Shift+A` | `Ctrl+Shift+A` | Aktifkan/nonaktifkan Tashkeel anotasi |
| `Alt+Shift+S` | `Ctrl+Shift+S` | Ucapkan teks yang dipilih |
| `Alt+Shift+T` | `Ctrl+Shift+T` | Terjemahkan teks yang dipilih |

> **Tips:** Anda dapat menyesuaikan pintasan ini di Chrome di `chrome://extensions/shortcuts`.

---

## Panduan Pengaturan

| Pengaturan | Deskripsi |
|---------|-------------|
| **Aktifkan Tashkeel** | Master switch untuk mengaktifkan atau menonaktifkan fitur anotasi Tashkeel |
| **Seluruh Halaman Tashkeel** | Jika diaktifkan, menambahkan tanda vokal ke semua kata Arab di halaman |
| **Mode Melayang** | Pilih perilaku hover: Kamus (definisi + audio), Tooltip (Tashkeel + audio), atau Nonaktif |
| **Tampilkan I'rab Formulir** | Menampilkan akhiran kasus tata bahasa untuk kata-kata yang berlaku |
| **Kecepatan Bicara** | Menyesuaikan kecepatan membaca kalimat |
| **Mesin Terjemahan** | Pilih antara Bing Translate dan Google Translate |
| **Bahasa Sasaran** | Tetapkan bahasa target terjemahan |
| **Deteksi Cerdas PDF** | Saat diaktifkan, secara otomatis mengalihkan URL PDF ke pembaca bawaan |

---

## Pertanyaan Umum

**T: Mengapa tidak berfungsi di beberapa halaman?**  
J: Demi alasan keamanan, ekstensi browser tidak dapat berjalan di halaman khusus seperti `chrome://`, pengaturan browser, atau Chrome Web Store.

**Q: Tidak ada suara dari text-to-speech?**  
J: Silakan periksa pengaturan volume sistem Anda dan pastikan paket suara Arab telah diinstal. Dukungan ucapan bervariasi antar browser dan sistem operasi.

**T: Ekstensi tidak mendeteksi teks Arab.**  
J: Ekstensi ini menggunakan deteksi cerdas untuk menemukan blok teks Arab. Jika teks ditampilkan sebagai gambar atau menggunakan pengkodean non-standar, teks tersebut mungkin tidak terdeteksi.

**Q: Terjemahan tidak berfungsi?**  
A: Penerjemahan memerlukan koneksi internet. Jika Bing Translate gagal, coba beralih ke Google Translate di pengaturan.

**T: Bagaimana cara membuka PDF dengan Arabic Reader?**  
J: Klik "Buka Pembaca PDF" di popup, klik kanan tautan PDF dan pilih "Buka PDF dengan Arabic Reader", atau aktifkan "Deteksi Cerdas PDF" di pengaturan.

---

## Tautan Terkait

- [Kebijakan Privasi](../kebijakan privasi)
- [Dukungan & Masukan](../support)

---

---
