
<p align="center">
  <img alt="GitHub language count" src="https://img.shields.io/github/languages/count/username/repositoryprojectname?color=%2304D361">

  <img alt="Repository size" src="https://img.shields.io/github/repo-size/username/repositoryprojectname">
  
  <a href="https://github.com/tgmarinho/README-ecoleta/commits/master">
    <img alt="GitHub last commit" src="https://img.shields.io/github/last-commit/username/repositoryprojectname">
  </a>
    
   <img alt="License" src="https://img.shields.io/badge/license-MIT-brightgreen">
   <a href="https://github.com/username/repositoryprojectname/stargazers">
    <img alt="Stargazers" src="https://img.shields.io/github/stars/username/repositoryprojectname?style=social">
  </a>
  
 
</p>
<h1 align="center">
    <img alt="NextLevelWeek" title="#NextLevelWeek" src="./assets/banner.png" />
</h1>

<h4 align="center"> 
	🚧  AppName ♻️ Concluído 🚀 🚧
</h4>

<p align="center">
 <a href="#-about">About</a> •
 <a href="#-functionalities">Functionalities</a> •
 <a href="#-layout">Layout</a> • 
 <a href="#-executing">Executing</a> • 
 <a href="#-tools">Tools</a> • 
 <a href="#-author">Author</a> • 
 <a href="#-license">License</a>
</p>


## 💻 About

💰 DT Money - A ideia do projeto é um controle financeiro, com entradas e com saídas e um cálculo de total. Também é possível cadastrar novas entradas, novas saídas e fazer buscas 

Consumo de apis
Requisições frontend x backend
Ferramentas para medir performance

Projeto desenvolvido durante o curso Ignite oferecido pela [Rocketseat](https://blog.rocketseat.com.br).

---

## ⚙️ Functionalities

- [x] Empresas ou entidades podem se cadastrar na plataforma web enviando:
  - [x] uma imagem do ponto de coleta
  - [x] nome da entidade, email e whatsapp
  - [x] e o endereço para que ele possa aparecer no mapa
  - [x] além de selecionar um ou mais ítens de coleta: 
    - lâmpadas
    - pilhas e baterias
    - papéis e papelão
    - resíduos eletrônicos
    - resíduos orgânicos
    - óleo de cozinha

- [x] Os usuários tem acesso ao aplicativo móvel, onde podem:
  - [x] navegar pelo mapa para ver as instituições cadastradas
  - [x] entrar em contato com a entidade através do E-mail ou do WhatsApp

---

## 🎨 Layout

O layout da aplicação está disponível no Figma:

<a href="https://www.figma.com/file/c5BA5gCabL1WqGYZFm9qL3/DT-Money-(Community)?type=design&node-id=0-1&t=NqHrQgwGUZotPnRS-0">
  <img alt="Made by ..." src="https://img.shields.io/badge/Acessar%20Layout%20-Figma-%2304D361">
</a>


### Mobile

<p align="center">
  <img alt="NextLevelWeek" title="#NextLevelWeek" src="./assets/home-mobile.png" width="200px">

  <img alt="NextLevelWeek" title="#NextLevelWeek" src="./assets/detalhes-mobile.svg" width="200px">
</p>

### Web

<p align="center" style="display: flex; align-items: flex-start; justify-content: center;">
  <img alt="NextLevelWeek" title="#NextLevelWeek" src="./assets/web.svg" width="400px">

  <img alt="NextLevelWeek" title="#NextLevelWeek" src="./assets/sucesso-web.svg" width="400px">
</p>

---

## 🚀 Executing

Este projeto é divido em duas partes:
1. Backend (pasta server) 
2. Frontend (pasta web)

### Pre-requirements

[Git](https://git-scm.com)
[Node.js](https://nodejs.org/en/). 
[VSCode](https://code.visualstudio.com/)


#### 🧭 Running the web application (frontend) + json-server (server)

```bash

# clone this repository
$ git clone git@github.com:username/repositoryprojectname.git

# open the directory of the project in a terminal
$ cd repositoryprojectname

# install the dependecies
$ npm install

# run in development mode
$ npm run dev

# the app will opne at the port:5173 - access http://localhost:5173

```

#### 🎲 Rodando o json-server/server.json (servidor)

```bash

# in the package.json file in "scripts" add this line:
# "dev:server": "json-server server.json -p 3333 -w -d 500",
$ npm run dev:server
# the server will initiate at the port:3333 - you can access http://localhost:3333 

```

---

## 🛠 Tools

As seguintes ferramentas foram usadas na construção do projeto:

#### **Website**  ([React](https://reactjs.org/)  +  [TypeScript](https://www.typescriptlang.org/))

-   **[Phosphor Icons](https://phosphoricons.com/)**
-   **[radix-ui](https://www.radix-ui.com/)**
-   **[Axios](https://github.com/axios/axios)**
-   **[styled-components](https://styled-components.com/)**
-   **[react-hook-form](https://www.react-hook-form.com/)**
-   **[zod](https://zod.dev/)**
-   **[use-context-selector](https://github.com/dai-shi/use-context-selector)**

> Veja o arquivo  [package.json](https://github.com/ruanwagner/dt-money-rocketseat/blob/master/web/package.json)

#### **Utilitários**

-   **[json-server](https://github.com/typicode/json-server)**
-   **[ESLint](https://github.com/eslint/eslint)**

---

## 🦸 Author

<a href="#">
 <img style="border-radius: 50%;" src="https://avatars.githubusercontent.com/u/46347114?v=4" width="100px;" alt=""/>
 <br />
 <sub><b>Ruan Wagner</b></sub></a> 
 <br />

[Entre em contato!]()

<br />

[![Linkedin Badge](https://img.shields.io/badge/-Ruan-blue?style=flat-square&logo=Linkedin&logoColor=white&link=https://www.linkedin.com/in/ruanwagner/)](https://www.linkedin.com/in/ruanwagner/) 
[![Gmail Badge](https://img.shields.io/badge/-ruan.wagner@universo.univates.br-c14438?style=flat-square&logo=Gmail&logoColor=white&link=mailto:ruan.wagner@universo.univates.br)](mailto:ruan.wagner@universo.univates.br)

---

## 📝 License

Este projeto esta sobe a licença [MIT](./LICENSE).

Feito com ❤️ por Ruan Wagner 👋🏽 

---