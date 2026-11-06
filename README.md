# 👩🏻‍💻 Maisa Amaral | Full Stack Developer

### Transformando ideias em experiências digitais modernas, funcionais e intuitivas.

Olá! Sou **Maisa Amaral**, desenvolvedora web com foco em **Frontend, Full Stack e UX/UI Design**.

Tenho interesse em criar soluções que vão além de simplesmente funcionar: aplicações bem estruturadas, interfaces intuitivas, experiências responsivas e código organizado.

Este repositório reúne o desenvolvimento do meu **portfólio pessoal**, uma aplicação Full Stack criada para apresentar meus projetos, habilidades e minha evolução como desenvolvedora.

---

## ✨ Sobre o projeto

Este portfólio está sendo desenvolvido como uma aplicação web completa, unindo uma interface moderna a uma API própria e um banco de dados relacional.

Mais do que uma página de apresentação, o objetivo é demonstrar na prática conhecimentos de:

- Desenvolvimento de interfaces com Angular e TypeScript
- Design responsivo e experiência do usuário
- Construção de APIs REST com NestJS
- Integração entre frontend e backend
- Persistência de dados com PostgreSQL e Prisma
- Organização e manutenção de projetos Full Stack

**Status:** 🚧 Em desenvolvimento — melhorias visuais, novas funcionalidades e integrações estão sendo implementadas progressivamente.

---

## 🛠️ Tecnologias utilizadas

### Frontend

![Angular](https://img.shields.io/badge/Angular-DD0031?style=for-the-badge&logo=angular&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white)
![Tailwind CSS](https://img.shields.io/badge/Tailwind_CSS-06B6D4?style=for-the-badge&logo=tailwindcss&logoColor=white)
![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css&logoColor=white)

### Backend e banco de dados

![NestJS](https://img.shields.io/badge/NestJS-E0234E?style=for-the-badge&logo=nestjs&logoColor=white)
![Node.js](https://img.shields.io/badge/Node.js-5FA04E?style=for-the-badge&logo=nodedotjs&logoColor=white)
![Prisma](https://img.shields.io/badge/Prisma-2D3748?style=for-the-badge&logo=prisma&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=for-the-badge&logo=postgresql&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)

### Ferramentas

![Git](https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white)
![GitHub](https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white)
![VS Code](https://img.shields.io/badge/VS_Code-007ACC?style=for-the-badge&logo=visualstudiocode&logoColor=white)
![Figma](https://img.shields.io/badge/Figma-F24E1E?style=for-the-badge&logo=figma&logoColor=white)

---

## 🚀 Funcionalidades

### Implementadas ou em desenvolvimento

- Interface inicial do portfólio em Angular
- API REST desenvolvida com NestJS
- Endpoint `POST /contacts` para recebimento de mensagens
- Validação de dados enviados à API
- Banco PostgreSQL executado com Docker
- Integração do backend com Prisma ORM
- Persistência das mensagens de contato no banco de dados

### Próximas evoluções

- Reformulação visual completa do frontend
- Animações e interações personalizadas
- Apresentação dinâmica de projetos
- Integração do formulário visual com a API
- Dashboard administrativo para gerenciamento de mensagens
- Melhorias de acessibilidade e responsividade
- Publicação da aplicação

---

## 🏗️ Arquitetura da aplicação

O projeto utiliza uma arquitetura separada por responsabilidades:

```text
portfolio-maisa/
│
├── frontend/             # Aplicação Angular
│   ├── src/
│   └── package.json
│
├── backend/              # API NestJS
│   ├── prisma/           # Schema e migrations
│   ├── src/
│   │   ├── modules/      # Módulos da aplicação
│   │   ├── prisma/       # Integração com o banco
│   │   └── main.ts
│   └── package.json
│
├── docker-compose.yml    # Ambiente PostgreSQL
├── .gitignore
└── README.md
```

### Fluxo de comunicação

```text
        Usuário
           │
           ▼
    Angular Frontend
           │
           │ HTTP / REST
           ▼
       NestJS API
           │
           ▼
       Prisma ORM
           │
           ▼
       PostgreSQL
       (Docker)
```

Essa separação facilita a manutenção, a evolução das funcionalidades e a organização do código.

---

## 💻 Executando o projeto localmente

### Pré-requisitos

- Node.js e npm
- Docker Desktop
- Git

### 1. Clonar o repositório

```bash
git clone <URL_DO_REPOSITORIO>
cd maisa-portfolio
```

### 2. Configurar o banco de dados

Configure as variáveis de ambiente conforme o `docker-compose.yml` e o arquivo `prisma.config.ts`.

**Importante:** utilize credenciais próprias de desenvolvimento. Não publique arquivos `.env` com senhas reais.

Inicie o PostgreSQL:

```bash
docker compose up -d
```

### 3. Iniciar o backend

```bash
cd backend
npm install
npx prisma generate
npx prisma migrate deploy
npm run start:dev
```

A API estará disponível, por padrão, em:

`http://localhost:3000`

### 4. Iniciar o frontend

Em outro terminal:

```bash
cd frontend
npm install
npm start
```

Acesse o endereço local informado pelo Angular no terminal, normalmente `http://localhost:4200`.

---

## 🎯 Objetivo profissional

Meu objetivo é atuar no desenvolvimento de soluções digitais, contribuindo com criatividade, organização, colaboração e aprendizado contínuo.

Tenho interesse especial em oportunidades relacionadas a:

**Frontend Development • Full Stack Development • Web Development • UX/UI Design**

Busco projetos e ambientes nos quais possa transformar desafios reais em soluções práticas e de qualidade.

---

## 📬 Vamos conversar?

Estou aberta a oportunidades profissionais, projetos e conexões com pessoas da área de tecnologia.

- **LinkedIn:** [https://www.linkedin.com/in/maisaamaral/)
- **GitHub:** [https://github.com/maisamarall)
- **Portfólio online:** Em desenvolvimento

---

### 💜 Código, criatividade e experiência do usuário.

*Desenvolvido por Maisa Amaral.*

**Se este projeto chamou sua atenção, fique à vontade para explorar o código e acompanhar sua evolução!** 
