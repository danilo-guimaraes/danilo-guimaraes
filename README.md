<h1 align="center">Olá, eu sou o Danilo 👋</h1>
<h3 align="center">Fullstack Developer em formação | TypeScript · Node.js · PostgreSQL · React</h3>

<p align="center">
  <a href="https://www.linkedin.com/in/daniloguimaraes-it/"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=flat&logo=linkedin&logoColor=white" alt="LinkedIn" /></a>
  <a href="mailto:d.guimaraes.dev@gmail.com"><img src="https://img.shields.io/badge/Email-D14836?style=flat&logo=gmail&logoColor=white" alt="Email" /></a>
</p>

---

### Sobre mim

Desenvolvedor construindo aplicações reais de ponta a ponta — frontend, backend e deploy em produção. Estudo diariamente com foco prático: cada projeto abaixo nasceu de escrever, quebrar e corrigir código de verdade, não apenas acompanhar um tutorial. Atualmente aprofundando TypeScript, Node.js e arquitetura de APIs, com React entrando agora na rotina.

---

### 🎯 Foco atual

| Em prática agora | Próximos passos |
|---|---|
| **React.js** — componentização, hooks (`useState`, `useEffect`), tipagem de props (Origamid) | Projeto Fullstack (React + Node + MySQL) |
| **TypeScript & Node.js** — Express, ORM (Prisma), validação de schema (Zod), arquitetura REST (Rocketseat) | Autenticação e autorização (JWT, hash de senhas, middlewares de segurança) |
| **Deploy & CI/CD** — GitHub Actions, deploy de APIs Node.js no Render, Prisma/PostgreSQL em produção | DevOps — objetivo de longo prazo |

---

### 🚀 Experiência recente: troubleshooting de verdade

Não é só escrever código — é entender por que ele quebra em produção.

**Deploy da Rocketlog API (Node.js + TypeScript + Prisma) no Render**
- Diagnostiquei e corrigi um erro de configuração do datasource do Prisma (`DATABASE_URL` ausente no schema)
- Investiguei uma falha de migration em produção (`P3018`), causada por inconsistência entre um enum do PostgreSQL e o valor default da coluna
- Corrigi a migration SQL, versionei via Git e planejei a reaplicação segura no banco do Render

**Deploy do Adivinhe (React + Vite) no GitHub Pages**
- Identifiquei que o Pages servia o `index.html` fonte (apontando para um `.tsx` não compilado) por falta de um passo de build automatizado
- Configurei um workflow de GitHub Actions para buildar com Vite e publicar apenas o artefato de produção (`dist/`)
- Corrigi um segundo bug de caminho de assets: caminhos absolutos gerados pelo Vite não respeitavam o subdiretório do projeto no Pages — resolvido com `base` relativo

Esse tipo de troubleshooting end-to-end — do sintoma no navegador ou no log até a causa raiz — é o que mais busco praticar.

---

### 🛠️ Tecnologias

![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat&logo=typescript&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat&logo=javascript&logoColor=black)
![React](https://img.shields.io/badge/React-61DAFB?style=flat&logo=react&logoColor=black)
![Node.js](https://img.shields.io/badge/Node.js-339933?style=flat&logo=nodedotjs&logoColor=white)
![Vite](https://img.shields.io/badge/Vite-646CFF?style=flat&logo=vite&logoColor=white)
![Prisma](https://img.shields.io/badge/Prisma-2D3748?style=flat&logo=prisma&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat&logo=postgresql&logoColor=white)
![MySQL](https://img.shields.io/badge/MySQL-005C84?style=flat&logo=mysql&logoColor=white)
![TailwindCSS](https://img.shields.io/badge/Tailwind_CSS-06B6D4?style=flat&logo=tailwindcss&logoColor=white)
![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=flat&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=flat&logo=css3&logoColor=white)
![Render](https://img.shields.io/badge/Render-46E3B7?style=flat&logo=render&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=flat&logo=git&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?style=flat&logo=githubactions&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white)
![Figma](https://img.shields.io/badge/Figma-F24E1E?style=flat&logo=figma&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=flat&logo=linux&logoColor=black)

---

### 📌 Projetos em destaque

| Projeto | Descrição | Stack | Acesso |
| :--- | :--- | :--- | :--- |
| **Rocketlog API** | API REST de rastreamento de encomendas com autenticação por perfil, ORM Prisma e banco PostgreSQL, com deploy em produção no Render. | TypeScript · Node.js · Prisma · PostgreSQL · Render | [📦 GitHub](https://github.com/danilo-guimaraes/rocketlog-delvery-API) |
| **Adivinhe** | Jogo de adivinhação de palavras (estilo forca) em React, com estado de partida via hooks, tipagem em TypeScript, CSS Modules responsivo e deploy automatizado via GitHub Actions. | React · TypeScript · Vite · CSS Modules | [📦 GitHub](https://github.com/danilo-guimaraes/adivinhe-react) · [▶ Jogar](https://danilo-guimaraes.github.io/adivinhe-react/) |
| **API REST** | API REST robusta construída do zero com Node.js e TypeScript, contendo arquitetura de rotas, controllers customizados, tratamento de erros e tipagem rigorosa. | TypeScript · Node.js · Express | [📦 GitHub](https://github.com/danilo-guimaraes/api-rest) |
| **API de Ticket** | API de serviço de tickets para backend estruturada com TypeScript e Express, focada em validação de requisições e manipulação de rotas CRUD. | TypeScript · Node.js · Express | [📦 GitHub](https://github.com/danilo-guimaraes/api-de-ticket) |

<details>
<summary><strong>Outros projetos e exercícios de fundamentos</strong> (JavaScript puro, DOM, CSS avançado)</summary>
<br>

| Projeto | Descrição | Stack | Acesso |
| :--- | :--- | :--- | :--- |
| **Animais Fantásticos** | Interface estruturada inteiramente com JavaScript orientado a objetos (Classes), MutationObserver, integração com Fetch API e debounce. | HTML5 · Tailwind v4 · JS (Classes/ES6) | [▶ Ver projeto](https://danilo-guimaraes.github.io/animais-fantasticos/) |
| **Multi-step Form** | Formulário dinâmico em etapas, com controle de fluxo, alternância de cobrança (mensal/anual) e prevenção de propagação de eventos. | HTML5 · Tailwind v4 · JavaScript | [▶ Ver projeto](https://danilo-guimaraes.github.io/multi-step-form/) |
| **Refund App** | Sistema de solicitação de reembolso com validação de formulários, máscara de dados em tempo real e cálculo automático de totais. | HTML5 · CSS3 · JavaScript (ES6) | [▶ Ver projeto](https://danilo-guimaraes.github.io/refund-template-rocktseat/) |
| **Convert App** | Conversor de moedas (USD/EUR/GBP) com tratamento de erros, máscara via Regex e sugestões rápidas por delegação de eventos. | HTML5 · CSS3 · JavaScript (ES6) | [▶ Ver projeto](https://danilo-guimaraes.github.io/convert-template/) |
| **Sorteador de Números** | Sorteio com intervalo personalizado, controle de repetição e prevenção de duplicadas. | HTML5 · CSS3 · JavaScript (ES6) | [▶ Ver projeto](https://danilo-guimaraes.github.io/sorteador-de-numeros/) |
| **Shopping List** | Lista de compras interativa com manipulação de DOM e renderização dinâmica (`createElement`/`appendChild`). | HTML5 · CSS3 · JavaScript (ES6) | [▶ Ver projeto](https://danilo-guimaraes.github.io/compras-da-semana-rockectseat/) |
| **Theme Calculator** | Calculadora funcional com 3 temas visuais dinâmicos e tratamento de operações matemáticas complexas. | HTML5 · Tailwind v4 · JavaScript | [▶ Ver projeto](https://danilo-guimaraes.github.io/calculator-app-main/) |
| **Interactive Rating Component** | Componente de avaliação com captura de estado de cliques e tela de agradecimento dinâmica. | HTML5 · Tailwind v4 · JavaScript | [▶ Ver projeto](https://danilo-guimaraes.github.io/interactive-rating-component/) |
| **Bento Grid Dashboard** | Recriação de layout em Bento Grid, com posicionamento e responsividade em CSS avançado. | HTML5 · CSS Grid | [▶ Ver projeto](https://danilo-guimaraes.github.io/bento-grid-main/) |

</details>

---

### 📊 Progresso do roadmap

| Marco | Status |
|---|---|
| HTML5 + CSS3 (Flexbox, Grid, responsivo) | ✅ Concluído |
| JavaScript ES6+ (DOM, UX & POO) | ✅ Concluído |
| Python — Mundos 1 a 4 | ✅ Certificado |
| MySQL — Módulo 00 (40h) | ✅ Certificado |
| Tailwind CSS v4 | ✅ Concluído |
| TypeScript + Node.js + Express + ORM (Prisma) | ✅ Concluído |
| Autenticação e autorização (JWT) | ✅ Concluído |
| Deploy em produção (Render + PostgreSQL) | ✅ Concluído |
| CI/CD com GitHub Actions | ✅ Concluído |
| React.js | ⏳ Em andamento — 1º projeto no ar |
| Projeto fullstack (React + Node + MySQL) | 🔜 Planejado |
| DevOps | 🎯 Objetivo de longo prazo |

---

### 📫 Vamos nos conectar?

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=flat&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/daniloguimaraes-it/)
