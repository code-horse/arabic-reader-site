---
layout: bare
title: Arabic Reader Extension — Guia do usuário
lang: pt
---

# Arabic Reader — Guia do usuário

> Versão: v1.0.0

## Introdução

Arabic Reader é uma extensão de navegador para quem estuda árabe. Adiciona Tashkeel (marcações vocálicas / حركات) às palavras árabes em páginas web e PDFs, com vocalização automática, dicionário ao passar o mouse (análise de raiz e formas gramaticais), texto para fala e tradução — para facilitar a pronúncia e a gramática.

---

## Principais recursos

- **Tashkeel automático** — Marcações vocálicas (fathah, kasrah, dammah, sukun, shadda, tanween) em qualquer página web
- **Modo página inteira** — Tashkeel com um clique para todas as palavras árabes
- **Dicionário ao passar o mouse** — Ao passar o mouse: vocalização, definições, raiz e formas I'rab; modos Dicionário, Tooltip ou Desligado
- **Análise I'rab** — Terminações de caso (nom., acus., gen.) quando aplicável
- **Texto para fala** — TTS em árabe com destaque palavra a palavra (voz ar-SA)
- **Leitura da seleção** — Após selecionar texto, uma barra compacta oferece falar e traduzir
- **Tradução** — Selecione texto e clique em Traduzir para tradução instantânea via Bing ou Google Tradutor (108 idiomas)
- **Leitor PDF** — Visualizador PDF RTL integrado com suporte a Tashkeel
- **Deteção inteligente** — Deteção automática de árabe e redirecionamento de PDF
- **Extração de raízes** — Para compreender a morfologia árabe
- **Atalhos de teclado**
- **Interface multilíngue** — Árabe, inglês e chinês

---

## Como usar

### Passo 1: Instalar a extensão

Instale **Arabic Reader** na [Chrome Web Store](https://chromewebstore.google.com/), ou carregue localmente no modo desenvolvedor.

### Passo 2: Abrir uma página web

Visite uma página com conteúdo em árabe.

### Passo 3: Ativar o Tashkeel

Clique no ícone da extensão. Ative «Ativar Tashkeel» e «Tashkeel em toda a página».

### Passo 4: Ver anotações

Passe o mouse sobre as palavras para ver tooltips com Tashkeel. Clique no ícone do altifalante para ouvir.

### Passo 5: Falar e traduzir a seleção

Selecione texto árabe. Uma barra compacta aparece com:
- **Altifalante** — Lê a seleção com destaque palavra a palavra
- **Traduzir** — Mostra uma bolha de tradução abaixo da barra

> **Dica:** clique no ícone da extensão para abrir definições (modo hover, velocidade da fala, motor de tradução, etc.).

---

## Modo Tashkeel em toda a página

Com este modo, cada palavra árabe recebe vogais. A extensão deteta blocos de texto árabe e aplica Tashkeel com dicionário e PLN integrados.

---

## Dicionário ao passar o mouse

Dicionário árabe integrado. Escolha o modo nas definições:

| Modo | Comportamento |
|------|-----------------|
| **Dicionário** | Ao passar o mouse: Tashkeel + definições + raiz + I'rab + botão de pronúncia |
| **Tooltip** | Tashkeel + botão de pronúncia (sem definições) |
| **Desligado** | Sem efeito |

No modo **Dicionário**, o tooltip mostra a palavra vocalizada (Tashkeel), botão de áudio, definições, raiz trilítera e I'rab quando ativado.

---

## Leitor PDF

Leitor PDF integrado com suporte RTL completo para documentos árabes com Tashkeel.

### Abrir um PDF

**1 — Popup:** ícone → «Abrir leitor PDF», arrastar ficheiro ou «Escolher ficheiro», ou colar URL do PDF.

**2 — Menu de contexto:** clique direito no link `.pdf` → «Abrir PDF com Arabic Reader».

**3 — Deteção automática:** com «Deteção inteligente de PDF», os URLs `.pdf` são redirecionados para o leitor integrado.

### Recursos do leitor PDF

- **Anotações Tashkeel** — No texto do PDF
- **Dicionário ao clicar**
- **Barra de seleção** — Falar, traduzir ou copiar
- **Barra lateral** — Índice e miniaturas
- **Pesquisa**
- **Temas** — Escuro, claro e sépia
- **Zoom** — Automático, página, largura
- **Layout RTL**

---

## Texto para fala

Voz TTS árabe integrada no Chrome (ar-SA).

**Palavra:** passe o mouse e clique no altifalante no tooltip.

**Seleção:** barra flutuante com altifalante e destaque.

**Menu de contexto:** «Ler seleção».

**Atalho:** `Alt+Shift+S` (Mac: `Ctrl+Shift+S`).

---

## Tradução

Selecione texto para tradução instantânea.

**1:** barra de seleção → Traduzir.

**2:** menu de contexto → «Traduzir seleção».

**3:** `Alt+Shift+T` (Mac: `Ctrl+Shift+T`).

**Motores:** **Bing Tradutor** (predefinição), **Google Tradutor**. Ambos suportam **108 idiomas de destino**.

---

## Atalhos de teclado

| Atalho | Mac | Ação |
|--------|-----|------|
| `Alt+Shift+A` | `Ctrl+Shift+A` | Ligar/desligar Tashkeel |
| `Alt+Shift+S` | `Ctrl+Shift+S` | Ler seleção |
| `Alt+Shift+T` | `Ctrl+Shift+T` | Traduzir seleção |

> **Dica:** personalize em `chrome://extensions/shortcuts`.

---

## Definições

| Definição | Descrição |
|-----------|-----------|
| **Ativar Tashkeel** | Interruptor principal |
| **Tashkeel em toda a página** | Vogais em todas as palavras árabes |
| **Modo hover** | Dicionário, Tooltip ou Desligado |
| **Mostrar formas I'rab** | Casos gramaticais |
| **Velocidade da fala** | Velocidade de leitura |
| **Motor de tradução** | Bing ou Google |
| **Idioma de destino** | Idioma da tradução |
| **Deteção inteligente de PDF** | Redireciona URLs PDF para o leitor integrado |

---

## Perguntas frequentes

**Porque não funciona em algumas páginas?**  
Por segurança, as extensões não correm em `chrome://`, definições do navegador nem Chrome Web Store.

**Sem som no TTS?**  
Verifique o volume e pacotes de voz árabe. O suporte varia.

**Não deteta árabe.**  
Texto em imagem ou codificação não padrão pode falhar.

**Tradução não funciona?**  
É necessária ligação à Internet. Se o Bing falhar, mude para Google nas definições.

**Como abrir PDF com Arabic Reader?**  
«Abrir leitor PDF», menu de contexto no link, ou ative «Deteção inteligente de PDF».

---

## Ligações

- [Política de privacidade](../privacy-policy)
- [Suporte e feedback](../support)

---
