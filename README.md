# 💰 Blog de Finanças

📸 **Preview do Site**

![Preview do Site](images/preview.png)

---

Este projeto foi desenvolvido como **trabalho da disciplina de Programação Web Front-End** da **Universidade Vila Velha (UVV)**.  
O objetivo era criar uma página web funcional e responsiva utilizando **HTML** e **JavaScript**, aplicando boas práticas de estrutura, estilo e consumo de APIs externas.

---

## 🧠 Assunto

O tema do projeto é **Finanças Pessoais e Investimentos**.  
O blog tem como proposta **educar e informar** o público sobre:

- Organização de orçamento pessoal  
- Conceitos básicos de investimentos  
- Mercado de ações  
- Atualidades e notícias econômicas  

---

## 🧩 Tecnologias Utilizadas

- **HTML5** → Estrutura da página  
- **CSS3** → Estilização e layout responsivo  
- **JavaScript (Vanilla JS)** → Lógica e integração com API externa  

---

## 📰 API Utilizada

O blog exibe uma seção de **“Atualidades”**, onde são carregadas notícias sobre finanças e economia em tempo real.  
Essas informações são obtidas através da **[GNews API](https://gnews.io/)**, uma API pública de notícias.

Para contornar bloqueios de **CORS** durante a hospedagem na **Cloudflare Pages**, foi utilizado um proxy gratuito:

https://api.allorigins.win/get?url=


O endpoint final utilizado no projeto segue o formato:

https://api.allorigins.win/get?url=https://gnews.io/api/v4/top-headlines?lang=pt&topic=business&country=br&token=SEU_TOKEN

---

## ⚙️ Estrutura Principal

- `index.html` → Página inicial com introdução, links e seção de atualidades  
- `style.css` → Arquivo de estilo principal  
- `images/` → Imagens ilustrativas dos conteúdos e preview  
- `script` interno → Consumo da API GNews e renderização dinâmica das notícias  

---

## ☁️ Hospedagem

O site está hospedado gratuitamente na **Cloudflare Pages** e pode ser acessado através do link:

👉 **[https://programacaoweb-frontend-uvv.pages.dev/](https://programacaoweb-frontend-uvv.pages.dev/)**

---

## 👨‍💻 Autores

- **Pedro Prando**  
- **Breno Gabriel Hollunder**

---

📚 *Trabalho acadêmico desenvolvido para a disciplina de Programação Web Front-End – UVV.*
