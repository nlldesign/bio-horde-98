# 🎮 BIO-HORDE 98 // ZONA LESTE PSX

> **Protótipo de FPS Retrô Estilo PS1 criado 100% com Inteligência Artificial para exibição em portfólio.**

![Status](https://img.shields.io/badge/Status-Jog%C3%A1vel-brightgreen)
![Three.js](https://img.shields.io/badge/Three.js-r128-black)
![Audio](https://img.shields.io/badge/Audio-Web_Audio_API-orange)
![Licença](https://img.shields.io/badge/License-MIT-blue)

---

## 🌆 Sobre o Projeto

**BIO-HORDE 98** é um jogo de sobrevivência a hordas em primeira pessoa com estética nostálgica de PlayStation 1, ambientado na Zona Leste de São Paulo durante uma noite chuvosa de outubro de 1998.

Este projeto foi concebido e codificado através de **Engenharia de Prompts e Inteligência Artificial**, explorando os limites de geração procedural de código para jogos 3D no navegador em um arquivo único (*single-file architecture*), sem a necessidade de assets externos pesados.

---

## ✨ Destaques Técnicos

* **Visual PS1 Autêntico:** Renderização nativa em resolução ultra-baixa (320x240) esticada com filtro pixelado (`image-rendering: pixelated`), neblina de curta distância (*fog*), scanlines CRT e iluminação noturna com giroflex policial.
* **Texturas 100% Procedurais:** Asfalto, tijolos, cerâmica dos comércios, letreiros luminosos (*Bar do Pedro*, *Farmácia ZL*, *Retro Games*) e a bandeira do Brasil desenhados em tempo real via Canvas 2D.
* **Sintetizador de Áudio Retrô (Web Audio API):** Tiros de pistola, metralhadora M60 e escopeta calibre 12, sirenes de viatura, bips de rádio policial COPOM e passos gerados puramente por ondas sonoras e ruído branco matemático — zero arquivos `.mp3` ou `.wav` externos.
* **Mapa Explorável & Lojas Entráveis:** Quarteirão com becos, estacionamento, barricadas e lojas com portas abertas e caixas de suprimento para coleta.
* **Cutscene de Introdução em Tempo Real:** Câmera cinematográfica com barras pretas (*letterbox* animado), legendas da transmissão de emergência e opção de pular direto para a ação.
* **Radar Tático / Minimapa:** Canvas 2D dinâmico mostrando blocos, suprimentos e aproximação dos infectados.

---

## 🕹️ Controles

| Tecla / Ação | Função |
| :--- | :--- |
| **W, A, S, D** | Movimentação pelo cenário e exploração de lojas |
| **Mouse** | Mirar (utiliza a API de Pointer Lock) |
| **Clique Esquerdo** | Atirar (automático na M60 com clique pressionado) |
| **1, 2, 3** ou **Scroll** | Alternar armas (Pistola 9mm, M60-ZL, Escopeta 12) |
| **R** | Recarregar munição |
| **Shift** | Correr |
| **Espaço / Enter** | Pular cutscene de introdução |

---

## 🚀 Como Executar Localmente

Como o projeto é construído em um único arquivo estático, não requer nenhuma instalação de dependências ou Node.js:

1. Clone o repositório:
   ```bash
   git clone https://github.com/nlldesign/bio-horde-98.git
   ```
2. Abra o arquivo `index.html` em qualquer navegador moderno (Chrome, Edge, Firefox, Brave, Safari).

---

## 👨‍💻 Autor & Portfólio

Projeto desenvolvido por **Lucas Nellucci** como demonstração prática de prototipagem acelerada, criatividade e desenvolvimento auxiliado por IA.

* **GitHub:** [@nlldesign](https://github.com/nlldesign)
* **Email:** nellucci.design@gmail.com
