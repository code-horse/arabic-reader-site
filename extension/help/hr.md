---
layout: bare
title: Arabic Reader - Korisnički priručnik
lang: hr
---
# Arabic Reader - Korisnički priručnik

> Verzija: v1.0.0

## Uvod

Arabic Reader je proširenje preglednika dizajnirano za učenike arapskog jezika. Dodaje Tashkeel (oznake samoglasnika / حركات) arapskim riječima na web-stranicama i PDF-ovima, pružajući automatsku vokalizaciju, lebdeći rječnik s analizom korijena i gramatičkim oblicima, pretvaranje teksta u govor i značajke prijevoda — što vam pomaže da lakše naučite arapski izgovor i gramatiku.

---

## Glavne značajke

- **Automatski Tashkeel** — Dodaje oznake samoglasnika (fathah, kasrah, dammah, sukun, shadda, tanween) arapskim riječima na bilo kojoj web stranici
- **Način cijele stranice** — Jednim klikom Tashkeel za sve arapske riječi na stranici
- **Hover Dictionary** — Zadržite pokazivač iznad riječi da biste vidjeli vokalizaciju, definicije, analizu korijena i I'rab oblike; odaberite između Rječnika, Tooltip načina ili Isključeno
- **I'rab Analiza** — Prikažite gramatičke padežne nastavke (nominativ, akuzativ, genitiv) za primjenjive riječi
- **Text-to-Speech** — arapski TTS s karaoke isticanjem riječi (ar-SA glas)
- **Odabir govora** — Odaberite bilo koji tekst, pojavljuje se kompaktna alatna traka s gumbima za govor i prijevod
- **Prijevod** — Odaberite bilo koji tekst, kliknite prevedi da dobijete trenutni prijevod putem usluge Bing ili Google Translate (108 jezika)
- **PDF Reader** — Ugrađeni RTL PDF preglednik s podrškom za komentare Tashkeel
- **Pametno otkrivanje** — Automatsko otkrivanje arapskog teksta i pametno preusmjeravanje PDF-a
- **Izdvajanje korijena** — Identificirajte korijene riječi za bolje razumijevanje arapske morfologije
- **Tipkovnički prečaci** — Brzi pristup osnovnim značajkama
- **Višejezično sučelje** — korisničko sučelje na arapskom, engleskom i kineskom

---

## Kako koristiti

### Korak 1: Instalirajte ekstenziju

Instalirajte **Arabic Reader** iz [Chrome Web Store](https://chromewebstore.google.com/) ili ga učitajte lokalno u načinu rada za razvojne programere.

### Korak 2: Otvorite bilo koju web stranicu

Posjetite bilo koju web stranicu sa sadržajem na arapskom.

### Korak 3: Omogućite Tashkeel

Kliknite ikonu proširenja na alatnoj traci preglednika. Uključite "Omogući Tashkeel", a zatim uključite "Cijela stranica Tashkeel" da označite sve arapske riječi na stranici.

### Korak 4: Pregledajte komentare

Zadržite pokazivač iznad riječi da biste vidjeli Tashkeel opise alata s vokalizacijom, definicijama i izgovorom. Pritisnite ikonu zvučnika da čujete riječ.

### Korak 5: Izgovorite i prevedite odabrani tekst

Odaberite bilo koji arapski tekst pomoću miša. Pokraj odabira pojavljuje se kompaktna alatna traka s dva gumba:
- **Govornik** — Čita odabrani tekst naglas uz isticanje riječi u stilu karaoka
- **Prevedi** — Prikazuje oblačić ugrađenog prijevoda ispod alatne trake

> **Savjet:** Kliknite ikonu proširenja na alatnoj traci preglednika da biste otvorili ploču postavki i prilagodili način lebdenja, brzinu govora, mehanizam za prevođenje i još mnogo toga.

---

## Način cijele stranice Tashkeel

Kada je uključen mod Tashkeel cijele stranice, svaka arapska riječ na stranici dobiva oznake samoglasnika. Proširenje koristi pametno otkrivanje za prepoznavanje arapskih tekstnih blokova i primjenjuje Tashkeel koristeći svoj rječnik i NLP algoritme u paketu.

---

## Rječnik pri lebdenju

Proširenje uključuje ugrađeni arapski rječnik. Možete birati između više načina lebdenja u postavkama:

| Način | Ponašanje |
|------|----------|
| **Rječnik** | Hover prikazuje Tashkeel + definicije + korijen + I'rab + gumb za izgovor |
| **Opis alata** | Lebdeći pokazivač prikazuje Tashkeel + gumb za izgovor (bez definicija) |
| **Isključeno** | Nema efekta lebdenja |

U **Rječničkom načinu rada**, alatni opis prikazuje:
- Riječ s punom vokalizacijom (Tashkeel)
- Gumb za izgovor (kliknite da čujete)
- Definicije riječi
- Analiza korijena (korijen od tri slova)
- I'rab (gramatički slučaj) oblici kada je omogućen

---

## PDF čitač

Arabic Reader uključuje ugrađeni PDF čitač s potpunom podrškom za RTL koji vam omogućuje čitanje arapskih PDF dokumenata s Tashkeel komentarima.

### Otvaranje PDF-a

**Metoda 1: iz skočnog prozora**  
Pritisnite ikonu proširenja, a zatim kliknite "Otvori PDF čitač". Povucite i ispustite PDF datoteku ili kliknite "Odaberi datoteku" da otvorite lokalni PDF. Također možete zalijepiti PDF URL.

**Metoda 2: Kontekstni izbornik**  
Desnom tipkom miša kliknite bilo koju vezu `.pdf` na web stranici i odaberite "Otvori PDF s Arabic Reader".

**Metoda 3: Automatsko otkrivanje**  
Kada je "PDF Smart Detection" omogućeno u postavkama, proširenje automatski preusmjerava `.pdf` URL-ove na ugrađeni čitač.

### Značajke PDF čitača

- **Tashkeel Napomene** — Sve značajke napomena rade na PDF tekstu
- **Klikni rječnik** — Kliknite bilo koju riječ da biste vidjeli njezinu definiciju
- **Alatna traka za odabir** — Odaberite tekst za izgovor, prijevod ili kopiranje
- **Bočna traka** — pregled sadržaja i sličice stranica
- **Traži** — Tražite tekst u PDF-u
- **Teme** — tamne, svijetle i sepia teme za čitanje
- **Zumiranje** — Višestruke razine zumiranja uključujući Auto, Page Fit i Page Width
- **RTL raspored** — Potpuna podrška zdesna nalijevo

---

## Pretvaranje teksta u govor

Proširenje koristi Chromeov ugrađeni arapski TTS glas (ar-SA) za izgovor.

**Jedna riječ:** Zadržite pokazivač iznad riječi i kliknite gumb zvučnika u opisu alata.

**Odabir govora:** Odaberite bilo koji arapski tekst. Pojavljuje se plutajuća alatna traka s gumbom zvučnika — kliknite je za čitanje naglas uz isticanje riječi u stilu karaoka.

**Izbornik desnom tipkom miša:** Odaberite tekst, kliknite desnom tipkom miša i odaberite "Izgovori odabir".

**Tipkovnički prečac:** Odaberite tekst i pritisnite `Alt+Shift+S` (Mac: `Ctrl+Shift+S`).

---

## Prijevod

Odaberite bilo koji tekst na stranici i upotrijebite značajku prijevoda da biste dobili trenutne prijevode.

**Metoda 1: Alatna traka za odabir**  
Odaberite tekst, zatim kliknite gumb za prijevod na alatnoj traci.

**Metoda 2: Izbornik desnom tipkom miša**  
Odaberite tekst, kliknite desnom tipkom miša i odaberite "Prevedi odabir".

**Metoda 3: Tipkovnički prečac**  
Odaberite tekst i pritisnite `Alt+Shift+T` (Mac: `Ctrl+Shift+T`).

**Mehanizmi za prevođenje:**
- **Bing Translate** (zadano) — Powered by Microsoft Translator
- **Google Translate** — Pokreće Google

Oba motora podržavaju **108 ciljanih jezika**.

---

## Tipkovnički prečaci

| Prečac | Mac prečac | Radnja |
|----------|-------------|--------|
| `Alt+Shift+A` | `Ctrl+Shift+A` | Uključi/isključi komentare Tashkeel |
| `Alt+Shift+S` | `Ctrl+Shift+S` | Izgovori odabrani tekst |
| `Alt+Shift+T` | `Ctrl+Shift+T` | Prevedi odabrani tekst |

> **Savjet:** Možete prilagoditi ove prečace u Chromeu na `chrome://extensions/shortcuts`.

---

## Vodič za postavke

| Postavka | Opis |
|---------|-------------|
| **Omogući Tashkeel** | Glavni prekidač za omogućavanje ili onemogućavanje značajke zabilješke Tashkeel |
| **Cijela stranica Tashkeel** | Kada je omogućeno, dodaje oznake samoglasnika svim arapskim riječima na stranici |
| **Način lebdenja** | Odaberite ponašanje pri lebdenju: Rječnik (definicije + audio), Tooltip (Tashkeel + audio) ili Isključeno |
| **Prikaži I'rab obrasce** | Prikaži gramatičke nastavke velikih i malih slova za primjenjive riječi |
| **Brzina govora** | Podesite brzinu čitanja rečenice |
| **Translation Engine** | Odaberite Bing Translate i Google Translate |
| **Ciljni jezik** | Postavite ciljni jezik prijevoda |
| **Pametno otkrivanje PDF-a** | Kada je omogućeno, automatski preusmjerava PDF URL-ove na ugrađeni čitač |

---

## FAQ

**P: Zašto ne radi na nekim stranicama?**  
O: Iz sigurnosnih razloga, proširenja preglednika ne mogu se izvoditi na posebnim stranicama kao što su `chrome://`, postavke preglednika ili Chrome Web Store.

**P: Nema zvuka iz teksta u govor?**  
O: Provjerite postavke glasnoće vašeg sustava i provjerite jesu li instalirani arapski glasovni paketi. Govorna podrška razlikuje se ovisno o pregledniku i operativnom sustavu.

**P: Proširenje ne prepoznaje arapski tekst.**  
O: Proširenje koristi pametno otkrivanje za pronalaženje blokova arapskog teksta. Ako je tekst prikazan kao slike ili koristi nestandardno kodiranje, možda neće biti otkriven.

**P: Prijevod ne radi?**  
O: Za prijevod je potrebna internetska veza. Ako Bing Translate ne uspije, pokušajte se prebaciti na Google Translate u postavkama.

**P: Kako mogu otvoriti PDF s Arabic Reader?**  
O: Kliknite "Otvori PDF čitač" u skočnom prozoru, desnom tipkom miša kliknite PDF vezu i odaberite "Otvori PDF s Arabic Reader" ili omogućite "PDF Smart Detection" u postavkama.

---

## Povezane veze

- [Pravila o privatnosti](../privacy-policy)
- [Podrška i povratne informacije](../support)

---

---
