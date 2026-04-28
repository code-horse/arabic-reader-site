---
layout: bare
title: Arabic Reader Extension — Guía del usuario
lang: es
---

# Arabic Reader — Guía del usuario

> Versión: v1.0.0

## Introducción

Arabic Reader es una extensión del navegador para quienes aprenden árabe. Añade Tashkeel (marcas vocálicas / حركات) a las palabras árabes en páginas web y PDF, con vocalización automática, un diccionario al pasar el cursor (raíces y formas gramaticales), texto a voz y traducción, para facilitar la pronunciación y la gramática.

---

## Funciones principales

- **Tashkeel automático** — Añade signos vocálicos (fathah, kasrah, dammah, sukun, shadda, tanwin) en cualquier página web
- **Modo página completa** — Tashkeel con un clic para todas las palabras árabes
- **Diccionario al pasar el cursor** — Al pasar el cursor: vocalización, definiciones, análisis de raíz e formas I'rab; modos Diccionario, Tooltip o Desactivado
- **Análisis I'rab** — Terminaciones casuales (nom., acus., gen.) cuando aplique
- **Texto a voz** — TTS en árabe con resaltado palabra a palabra (voz ar-SA)
- **Lectura de selección** — Tras seleccionar texto, una barra compacta ofrece hablar y traducir
- **Traducción** — Seleccione texto y pulse Traducir para obtener traducción instantánea con Bing o Google Translate (108 idiomas)
- **Lector PDF** — Visor PDF integrado RTL con soporte de Tashkeel
- **Detección inteligente** — Detección automática de árabe y redirección de PDF
- **Extracción de raíces** — Identificación de raíces para la morfología árabe
- **Atajos de teclado** — Acceso rápido a las funciones principales
- **Interfaz multilingüe** — Árabe, inglés y chino

---

## Uso

### Paso 1: Instalar la extensión

Instale **Arabic Reader** desde [Chrome Web Store](https://chromewebstore.google.com/), o cargue la extensión en modo desarrollador.

### Paso 2: Abrir una página web

Visite una página que contenga texto en árabe.

### Paso 3: Activar Tashkeel

Pulse el icono de la extensión. Active «Activar Tashkeel» y «Tashkeel en toda la página».

### Paso 4: Ver anotaciones

Pase el cursor sobre las palabras para ver tooltips con Tashkeel, definiciones y pronunciación. Pulse el altavoz para escuchar la palabra.

### Paso 5: Hablar y traducir la selección

Seleccione texto árabe. Aparece una barra con:
- **Altavoz** — Lee la selección con resaltado palabra a palabra
- **Traducir** — Muestra una burbuja de traducción bajo la barra

> **Consejo:** pulse el icono de la extensión para abrir ajustes (modo hover, velocidad del habla, motor de traducción, etc.).

---

## Modo Tashkeel en toda la página

Con este modo activo, todas las palabras árabes reciben vocales. La extensión detecta bloques de texto árabe y aplica Tashkeel mediante su diccionario y NLP.

---

## Diccionario al pasar el cursor

La extensión incluye un diccionario árabe. Elija el modo en ajustes:

| Modo | Comportamiento |
|------|----------------|
| **Diccionario** | Hover: Tashkeel + definiciones + raíz + I'rab + botón de pronunciación |
| **Tooltip** | Hover: Tashkeel + pronunciación (sin definiciones) |
| **Desactivado** | Sin efecto al pasar el cursor |

En modo **Diccionario**, el tooltip muestra la palabra vocalizada (Tashkeel), botón de audio, definiciones, raíz triliteral e I'rab si está habilitado.

---

## Lector PDF

Arabic Reader incluye un lector PDF con RTL completo para documentos árabes con Tashkeel.

### Abrir un PDF

**1 — Desde el popup:** icono → «Abrir lector PDF», arrastrar un archivo o «Elegir archivo», o pegar una URL PDF.

**2 — Menú contextual:** clic derecho en un enlace `.pdf` → «Abrir PDF con Arabic Reader».

**3 — Detección automática:** si «Detección inteligente de PDF» está activa, las URL PDF se redirigen al lector integrado.

### Funciones del lector PDF

- **Anotaciones Tashkeel** — En el texto PDF
- **Diccionario al hacer clic**
- **Barra de selección** — Hablar, traducir o copiar
- **Barra lateral** — Esquema y miniaturas
- **Buscar**
- **Temas** — Oscuro, claro y sepia
- **Zoom** — Auto, página, ancho
- **Diseño RTL**

---

## Texto a voz

La extensión usa la voz TTS árabe de Chrome (ar-SA).

**Palabra:** pase el cursor y pulse el altavoz en el tooltip.

**Selección:** seleccione texto; barra flotante con altavoz y resaltado.

**Menú contextual:** «Hablar selección».

**Atajo:** selección + `Alt+Mayús+S` (Mac: `Ctrl+Mayús+S`).

---

## Traducción

Seleccione texto para traducir al instante.

**1:** barra de selección → Traducir.

**2:** menú contextual → «Traducir selección».

**3:** atajo — `Alt+Mayús+T` (Mac: `Ctrl+Mayús+T`).

**Motores:** **Bing Translate** (predeterminado), **Google Translate**. Ambos admiten **108 idiomas de destino**.

---

## Atajos de teclado

| Atajo | Mac | Acción |
|-------|-----|--------|
| `Alt+Shift+A` | `Ctrl+Shift+A` | Activar/desactivar Tashkeel |
| `Alt+Shift+S` | `Ctrl+Shift+S` | Hablar selección |
| `Alt+Shift+T` | `Ctrl+Shift+T` | Traducir selección |

> **Consejo:** personalice en `chrome://extensions/shortcuts`.

---

## Ajustes

| Ajuste | Descripción |
|--------|---------------|
| **Activar Tashkeel** | Interruptor principal |
| **Tashkeel en toda la página** | Vocales en todas las palabras árabes |
| **Modo hover** | Diccionario, Tooltip o Desactivado |
| **Mostrar formas I'rab** | Casos gramaticales |
| **Velocidad del habla** | Velocidad de lectura |
| **Motor de traducción** | Bing o Google |
| **Idioma de destino** | Idioma de la traducción |
| **Detección inteligente de PDF** | Redirige URL PDF al lector integrado |

---

## Preguntas frecuentes

**¿Por qué no funciona en algunas páginas?**  
Por seguridad, las extensiones no se ejecutan en `chrome://`, ajustes del navegador ni Chrome Web Store.

**¿Sin sonido en TTS?**  
Compruebe el volumen y las voces árabes instaladas. La compatibilidad varía.

**No detecta árabe.**  
Si el texto es imagen o codificación no estándar, puede fallar.

**¿Traducción no funciona?**  
Requiere Internet. Si falla Bing, pruebe Google en ajustes.

**¿Cómo abrir un PDF?**  
«Abrir lector PDF», menú contextual en el enlace, o active «Detección inteligente de PDF».

---

## Enlaces

- [Política de privacidad](../privacy-policy)
- [Soporte y comentarios](../support)

---
