---
layout: bare
title: Arabic Reader Extension — Guide d'utilisation
lang: fr
---

# Arabic Reader — Guide d'utilisation

> Version : v1.0.0

## Introduction

Arabic Reader est une extension de navigateur conçue pour les apprenants de l'arabe. Elle ajoute le Tashkeel (signes voyelles / حركات) aux mots arabes sur les pages Web et dans les fichiers PDF, avec vocalisation automatique, un dictionnaire au survol (analyse des racines et formes grammaticales), synthèse vocale et traduction — pour faciliter l'apprentissage de la prononciation et de la grammaire arabes.

---

## Fonctionnalités principales

- **Tashkeel automatique** — Ajoute les voyelles (fathah, kasrah, dammah, sukun, shadda, tanween) aux mots arabes sur toute page Web
- **Mode page entière** — Tashkeel en un clic pour tous les mots arabes de la page
- **Dictionnaire au survol** — Au survol d'un mot : vocalisation, définitions, analyse de la racine et formes I'rab ; modes Dictionnaire, Info-bulle ou Désactivé
- **Analyse I'rab** — Affiche les marques de cas (nomination, accusation, génitif) pour les mots concernés
- **Synthèse vocale** — TTS arabe avec surlignage mot à mot façon karaoké (voix ar-SA)
- **Lecture de la sélection** — Après sélection du texte, une barre compacte propose lecture et traduction
- **Traduction** — Sélectionnez du texte, cliquez sur Traduire pour une traduction instantanée via Bing ou Google Translate (108 langues)
- **Lecteur PDF** — Visionneuse PDF intégrée en RTL avec prise en charge du Tashkeel
- **Détection intelligente** — Détection automatique du texte arabe et redirection PDF
- **Extraction des racines** — Identification des racines pour mieux comprendre la morphologie arabe
- **Raccourcis clavier** — Accès rapide aux fonctions essentielles
- **Interface multilingue** — Interface en arabe, anglais et chinois

---

## Utilisation

### Étape 1 : installer l'extension

Installez **Arabic Reader** depuis le [Chrome Web Store](https://chromewebstore.google.com/), ou chargez-la localement en mode développeur.

### Étape 2 : ouvrir une page Web

Visitez une page contenant du texte arabe.

### Étape 3 : activer le Tashkeel

Cliquez sur l'icône de l'extension dans la barre d'outils. Activez « Activer le Tashkeel », puis « Tashkeel pour toute la page » pour annoter tous les mots arabes.

### Étape 4 : consulter les annotations

Survolez les mots pour voir les info-bulles Tashkeel (vocalisation, définitions, prononciation). Cliquez sur l'icône haut-parleur pour écouter le mot.

### Étape 5 : lire et traduire une sélection

Sélectionnez du texte arabe : une barre compacte apparaît avec :
- **Haut-parleur** — Lit la sélection à haute voix avec surlignage mot à mot
- **Traduire** — Affiche une bulle de traduction sous la barre

> **Astuce :** cliquez sur l'icône de l'extension pour ouvrir les réglages (mode de survol, débit vocal, moteur de traduction, etc.).

---

## Mode Tashkeel page entière

Lorsque le mode page entière est activé, chaque mot arabe reçoit des voyelles. L'extension détecte les blocs de texte arabe et applique le Tashkeel via son dictionnaire intégré et ses algorithmes de TAL.

---

## Dictionnaire au survol

L'extension inclut un dictionnaire arabe intégré. Plusieurs modes de survol sont disponibles dans les paramètres :

| Mode | Comportement |
|------|--------------|
| **Dictionnaire** | Survol : Tashkeel + définitions + racine + I'rab + bouton de prononciation |
| **Info-bulle** | Survol : Tashkeel + bouton de prononciation (sans définitions) |
| **Désactivé** | Aucun effet au survol |

En mode **Dictionnaire**, l'info-bulle affiche :
- le mot entièrement vocalisé (Tashkeel)
- un bouton de prononciation
- les définitions
- l'analyse de la racine (trilitère)
- les formes I'rab lorsque l'option est activée

---

## Lecteur PDF

Arabic Reader inclut un lecteur PDF intégré avec prise en charge RTL complète pour lire des documents PDF arabe avec annotations Tashkeel.

### Ouvrir un PDF

**Méthode 1 : depuis la fenêtre contextuelle**  
Cliquez sur l'icône de l'extension, puis sur « Ouvrir le lecteur PDF ». Glissez-déposez un fichier ou cliquez sur « Choisir un fichier ». Vous pouvez aussi coller une URL de PDF.

**Méthode 2 : menu contextuel**  
Clic droit sur un lien `.pdf`, puis « Ouvrir le PDF avec Arabic Reader ».

**Méthode 3 : détection automatique**  
Si « Détection intelligente des PDF » est activée, les URL se terminant par `.pdf` sont redirigées vers le lecteur intégré.

### Fonctionnalités du lecteur PDF

- **Annotations Tashkeel** — Toutes les fonctions d'annotation s'appliquent au texte du PDF
- **Dictionnaire au clic** — Clic sur un mot pour voir sa définition
- **Barre de sélection** — Sélection pour lire, traduire ou copier
- **Barre latérale** — Plan et vignettes des pages
- **Recherche** — Recherche de texte dans le PDF
- **Thèmes** — Sombre, clair et sépia
- **Zoom** — Niveaux dont Auto, Page entière et Largeur de page
- **Mise en page RTL** — Prise en charge complète droite-gauche

---

## Synthèse vocale

L'extension utilise la voix TTS arabe intégrée à Chrome (ar-SA).

**Mot isolé :** survolez un mot et cliquez sur le haut-parleur dans l'info-bulle.

**Sélection :** sélectionnez du texte arabe ; une barre flottante propose la lecture avec surlignage mot à mot.

**Menu contextuel :** sélectionnez du texte, clic droit, « Lire la sélection ».

**Raccourci :** sélectionnez du texte et appuyez sur `Alt+Maj+S` (Mac : `Ctrl+Maj+S`).

---

## Traduction

Sélectionnez du texte pour obtenir une traduction instantanée.

**Méthode 1 :** barre de sélection — cliquez sur Traduire.

**Méthode 2 :** menu contextuel — « Traduire la sélection ».

**Méthode 3 :** raccourci — `Alt+Maj+T` (Mac : `Ctrl+Maj+T`).

**Moteurs :**
- **Bing Translate** (par défaut) — Microsoft Translator
- **Google Translate** — Google

Les deux prennent en charge **108 langues cibles**.

---

## Raccourcis clavier

| Raccourci | Mac | Action |
|-----------|-----|--------|
| `Alt+Shift+A` | `Ctrl+Shift+A` | Activer / désactiver le Tashkeel |
| `Alt+Shift+S` | `Ctrl+Shift+S` | Lire la sélection |
| `Alt+Shift+T` | `Ctrl+Shift+T` | Traduire la sélection |

> **Astuce :** personnalisez les raccourcis dans Chrome à l'adresse `chrome://extensions/shortcuts`.

---

## Paramètres

| Paramètre | Description |
|-----------|-------------|
| **Activer le Tashkeel** | Interrupteur principal des annotations Tashkeel |
| **Tashkeel page entière** | Ajoute les voyelles à tous les mots arabes de la page |
| **Mode de survol** | Dictionnaire (définitions + audio), Info-bulle (Tashkeel + audio) ou Désactivé |
| **Afficher les formes I'rab** | Affiche les marques de cas pour les mots concernés |
| **Débit vocal** | Vitesse de lecture des phrases |
| **Moteur de traduction** | Bing Translate ou Google Translate |
| **Langue cible** | Langue de traduction |
| **Détection intelligente des PDF** | Redirige automatiquement les URL PDF vers le lecteur intégré |

---

## FAQ

**Pourquoi cela ne fonctionne pas sur certaines pages ?**  
Pour des raisons de sécurité, les extensions ne s'exécutent pas sur `chrome://`, les paramètres du navigateur ni le Chrome Web Store.

**Pas de son pour la synthèse vocale ?**  
Vérifiez le volume système et l'installation des voix arabes. La prise en charge varie selon le navigateur et l'OS.

**L'extension ne détecte pas l'arabe.**  
La détection repose sur des blocs de texte. Si le texte est en image ou encodé de façon non standard, il peut être ignoré.

**La traduction ne marche pas ?**  
Une connexion Internet est nécessaire. En cas d'échec de Bing, passez à Google dans les paramètres.

**Comment ouvrir un PDF avec Arabic Reader ?**  
Utilisez « Ouvrir le lecteur PDF » dans la fenêtre contextuelle, le menu contextuel sur un lien PDF, ou activez « Détection intelligente des PDF ».

---

## Liens utiles

- [Politique de confidentialité](../privacy-policy)
- [Assistance et commentaires](../support)

---
