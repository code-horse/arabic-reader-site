---
layout: bare
title: Arabic Reader Extension — Kullanım kılavuzu
lang: tr
---

# Arabic Reader — Kullanım kılavuzu

> Sürüm: v1.0.0

## Giriş

Arabic Reader, Arapça öğrenenler için bir tarayıcı uzantısıdır. Web sayfalarındaki ve PDF’lerdeki Arapça kelimelere Tashkeel (hareke / حركات) ekler; otomatik vokalleştirme, üzerine gelince sözlük (kök ve dilbilgisi biçimleri), metinden konuşma ve çeviri sunar — telaffuzu ve dilbilgisini kolaylaştırmak için.

---

## Ana özellikler

- **Otomatik Tashkeel** — Her web sayfasında Arapça kelimelere ünlü işaretleri (fathah, kasrah, dammah, sukun, shadda, tanwin)
- **Tüm sayfa modu** — Tek tıklamayla sayfadaki tüm Arapça kelimeler
- **Üzerine gelince sözlük** — Vokalleştirme, tanımlar, kök ve I'rab biçimleri; Sözlük, İpucu veya Kapalı
- **I'rab analizi** — Uygun kelimeler için iyelik / belirtme vb. ekler
- **Metinden konuşma** — Arapça TTS, kelime kelime vurgu (ar-SA ses)
- **Seçim okuma** — Metin seçildikten sonra okuma ve çeviri için kompakt araç çubuğu
- **Çeviri** — Metni seçip Çevir’e tıklayın; Bing veya Google ile anında çeviri (108 dil)
- **PDF okuyucu** — Tashkeel destekli yerleşik RTL PDF görüntüleyici
- **Akıllı algılama** — Otomatik Arapça algılama ve PDF yönlendirmesi
- **Kök çıkarma** — Morfoloji için
- **Klavye kısayolları**
- **Çok dilli arayüz** — Arapça, İngilizce, Çince

---

## Kullanım

### Adım 1: Uzantıyı yükleyin

**Arabic Reader**’ı [Chrome Web Mağazası](https://chromewebstore.google.com/)’ndan yükleyin veya geliştirici modunda yerel olarak ekleyin.

### Adım 2: Bir sayfa açın

Arapça içeren bir siteye gidin.

### Adım 3: Tashkeel’i açın

Uzantı simgesine tıklayın. «Tashkeel’i etkinleştir» ve «Tüm sayfa Tashkeel» seçeneklerini açın.

### Adım 4: İpuçlarını görün

Kelimenin üzerine gelin; Tashkeel ipuçları ve hoparlör simgesi görünür.

### Adım 5: Seçimi okuyun ve çevirin

Arapça metin seçin. Kompakt bir çubuk görünür:
- **Hoparlör** — Seçimi kelime kelime vurgulayarak okur
- **Çevir** — Çubuğun altında satır içi çeviri balonu

> **İpucu:** Simgeye tıklayarak üzerine gelme modunu, konuşma hızını, çeviri motorunu ayarlayın.

---

## Tüm sayfa Tashkeel modu

Açıkken her Arapça kelime ünlü alır. Uzantı metin bloklarını bulur ve sözlük + NLP ile Tashkeel uygular.

---

## Üzerine gelince sözlük

Yerleşik Arapça sözlük. Ayarlardan mod seçin:

| Mod | Davranış |
|-----|----------|
| **Sözlük** | Üzerine gelince Tashkeel + tanımlar + kök + I'rab + ses düğmesi |
| **İpucu** | Tashkeel + ses (tanım yok) |
| **Kapalı** | Etki yok |

**Sözlük** modunda ipucu tam vokalleştirilmiş kelime, ses düğmesi, tanımlar, üç harfli kök ve isteğe bağlı I'rab gösterir.

---

## PDF okuyucu

Tashkeel ile Arapça PDF’ler için tam RTL yerleşik okuyucu.

### PDF açma

**1 — Açılır pencere:** Simge → «PDF okuyucuyu aç»; dosyayı sürükleyin veya «Dosya seçin»; PDF URL’si yapıştırın.

**2 — Bağlam menüsü:** `.pdf` bağlantısına sağ tıklayın → «Arabic Reader ile PDF aç».

**3 — Otomatik:** «PDF akıllı algılama» açıksa `.pdf` URL’leri yerleşik okuyucuya yönlendirilir.

### PDF özellikleri

- **Tashkeel notları** — PDF metninde de geçerli
- **Tıklayınca sözlük**
- **Seçim çubuğu** — Okuma, çeviri, kopyalama
- **Kenar çubuğu** — İçindekiler ve küçük resimler
- **Arama**
- **Temalar** — Koyu, açık, sepia
- **Yakınlaştırma** — Otomatik, sayfa, genişlik
- **RTL düzeni**

---

## Metinden konuşma

Chrome’un yerleşik Arapça TTS sesi (ar-SA) kullanılır.

**Kelime:** Üzerine gelin, ipucundaki hoparlöre tıklayın.

**Seçim:** Yüzen çubuk ve kelime vurgusu.

**Bağlam menüsü:** «Seçimi oku».

**Kısayol:** `Alt+Shift+S` (Mac: `Ctrl+Shift+S`).

---

## Çeviri

Metin seçerek anında çeviri alın.

**1:** Seçim çubuğunda Çevir.

**2:** Bağlam menüsü → «Seçimi çevir».

**3:** `Alt+Shift+T` (Mac: `Ctrl+Shift+T`).

**Motorlar:** **Bing Çevir** (varsayılan), **Google Çeviri**. İkisi de **108 hedef dili** destekler.

---

## Klavye kısayolları

| Kısayol | Mac | Eylem |
|---------|-----|-------|
| `Alt+Shift+A` | `Ctrl+Shift+A` | Tashkeel aç/kapa |
| `Alt+Shift+S` | `Ctrl+Shift+S` | Seçimi oku |
| `Alt+Shift+T` | `Ctrl+Shift+T` | Seçimi çevir |

> **İpucu:** `chrome://extensions/shortcuts` üzerinden özelleştirin.

---

## Ayarlar

| Ayar | Açıklama |
|------|----------|
| **Tashkeel’i etkinleştir** | Ana anahtar |
| **Tüm sayfa Tashkeel** | Tüm Arapça kelimelere hareke |
| **Üzerine gelme modu** | Sözlük, İpucu veya Kapalı |
| **I'rab biçimlerini göster** | Dilbilgisi ekleri |
| **Konuşma hızı** | Cümle okuma hızı |
| **Çeviri motoru** | Bing veya Google |
| **Hedef dil** | Çeviri dili |
| **PDF akıllı algılama** | PDF URL’lerini yerleşik okuyucuya yönlendir |

---

## SSS

**Bazı sayfalarda neden çalışmıyor?**  
Güvenlik nedeniyle uzantılar `chrome://`, tarayıcı ayarları ve Chrome Web Mağazası’nda çalışmaz.

**TTS sesi yok mu?**  
Sistem sesini ve Arapça ses paketlerini kontrol edin. Destek tarayıcıya ve işletim sistemine göre değişir.

**Arapça algılanmıyor.**  
Görüntü olarak metin veya standart dışı kodlama algılanmayabilir.

**Çeviri çalışmıyor mu?**  
İnternet gerekir. Bing başarısız olursa ayarlardan Google’a geçin.

**Arabic Reader ile PDF nasıl açılır?**  
«PDF okuyucuyu aç», bağlam menüsü veya «PDF akıllı algılama».

---

## Bağlantılar

- [Gizlilik politikası](../privacy-policy)
- [Destek ve geri bildirim](../support)

---
