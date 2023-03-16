<h1 align="center">
     :computer: <a href="#" alt="site do projeto"> NomeProjeto </a>
</h1>

<h3 align="center">
   Breve comentário sobre o projeto.
</h3>

<p align="center">
  <img alt="GitHub language count" src="https://img.shields.io/github/languages/count/Felix566/Template_Readme?color=%2304D361">

  <img alt="Repository size" src="https://img.shields.io/github/repo-size/Felix566/Template_Readme">
  
  <a href="https://github.com/Felix566/Template_Readme/commits/master">
    <img alt="GitHub last commit" src="https://img.shields.io/github/last-commit/Felix566/Template_Readme">
  </a>
    
   <img alt="License" src="https://img.shields.io/badge/license-MIT-brightgreen">
   <a href="https://github.com/Felix566/Template_Readme/stargazers">
    <img alt="Stargazers" src="https://img.shields.io/github/stars/Felix566/Template_Readme?style=social">
  </a>
</p>

<h4 align="center">
	:construction: Status do projeto :construction:
</h4>

<p align="center">
 <a href="#-sobre-o-projeto">Sobre</a> •
 <a href="#-funcionalidades">Funcionalidades</a> •
 <a href="#-layout">Layout</a> • 
 <a href="#-como-executar-o-projeto">Como executar</a> • 
 <a href="#-tecnologias">Tecnologias</a> • 
 <a href="#-contribuidores">Contribuidores</a> • 
 <a href="#-autor">Autor</a> • 
 <a href="#user-content--licença">Licença</a>
</p>

## :computer: Sobre o projeto
Descrição do que se trata o projeto.
---

## :gear: Funcionalidades
Descrever as funcionalidades oferecidas pelo projeto.
- [x] Empresas ou entidades podem se cadastrar na plataforma web enviando:
  - [x] nome da entidade, email e whatsapp
  - [x] e o endereço para que ele possa aparecer no mapa
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

## :art: Layout
Caso tenha disponível no figma colocar o link:

O layout da aplicação está disponível no Figma:

<a href="link do figma">
  <img alt="Made by Felix566" src="https://img.shields.io/badge/Acessar%20Layout%20-Figma-%2304D361">
</a>

### Mobile
adicionar telas caso tenha telas mobile:

<p align="center">
  <img alt="" title="" src="./assets/home-mobile.png" width="200px">

  <img alt="" title="" src="./assets/detalhes-mobile.svg" width="200px">
</p>

### Web
adicionar telas da versão web:
<p align="center" style="display: flex; align-items: flex-start; justify-content: center;">
  <img alt="" title="" src="./assets/web.svg" width="400px">

  <img alt="" title="" src="./assets/sucesso-web.svg" width="400px">
</p>


## :rocket: Como executar o projeto
Este projeto é divido em três partes:
1. Backend (pasta server) 
2. Frontend (pasta web)
3. Mobile (pasta mobile)

:bulb:Tanto o Frontend quanto o Mobile precisam que o Backend esteja sendo executado para funcionar.

### Pré-requisitos

Antes de começar, você vai precisar ter instalado em sua máquina as seguintes ferramentas:
[Git](https://git-scm.com), [Node.js](https://nodejs.org/en/). 
Além disto é bom ter um editor para trabalhar com o código como [VSCode](https://code.visualstudio.com/)

#### :game_die: Rodando o Backend (servidor)

```bash
# Clone este repositório
$ git clone git@github.com:Felix566/Template_Readme.git
# Acesse a pasta do projeto no terminal/cmd
$ cd Template_Readme
# Vá para a pasta server
$ cd server
# Instale as dependências
$ npm install
# Execute a aplicação em modo de desenvolvimento
$ npm run dev:server
# O servidor inciará na porta:3333 - acesse http://localhost:3333 
```

#### :dart: Rodando a aplicação web (Frontend)

```bash
# Clone este repositório
$ git clone git@github.com:Felix566/Template_Readme.git
# Acesse a pasta do projeto no seu terminal/cmd
$ cd Template_Readme
# Vá para a pasta da aplicação Front End
$ cd web
# Instale as dependências
$ npm install
# Execute a aplicação em modo de desenvolvimento
$ npm run start
# A aplicação será aberta na porta:3000 - acesse http://localhost:3000
```
---

## :hammer_and_pick: Tecnologias

As seguintes ferramentas foram usadas na construção do projeto:

Listar as tecnologias utilizadas no desenvolvimento:
#### **Website**  ([React](https://reactjs.org/)  +  [TypeScript](https://www.typescriptlang.org/))

-   **[React Router Dom](https://github.com/ReactTraining/react-router/tree/master/packages/react-router-dom)**
-   **[React Icons](https://react-icons.github.io/react-icons/)**

> Veja o arquivo  [package.json](https://github.com/Felix566/Template_Readme/blob/master/web/package.json)

#### **Server**  ([NodeJS](https://nodejs.org/en/)  +  [TypeScript](https://www.typescriptlang.org/))

-   **[Express](https://expressjs.com/)**
-   **[CORS](https://expressjs.com/en/resources/middleware/cors.html)**

> Veja o arquivo  [package.json](https://github.com/Felix566/Template_Readme/blob/master/server/package.json)

#### **Mobile**  ([React Native](http://www.reactnative.com/)  +  [TypeScript](https://www.typescriptlang.org/))

-   **[Expo](https://expo.io/)**
-   **[Expo Google Fonts](https://github.com/expo/google-fonts)**
-   **[React Navigation](https://reactnavigation.org/)**

> Veja o arquivo  [package.json](https://github.com/Felix566/Template_Readme/blob/master/mobile/package.json)

## :muscle: Como contribuir no projeto

1. Faça um **fork** do projeto.
2. Crie uma nova branch com as suas alterações: `git checkout -b my-feature`
3. Salve as alterações e crie uma mensagem de commit contando o que você fez: `git commit -m "feature: My new feature"`
4. Envie as suas alterações: `git push origin my-feature`
> Caso tenha alguma dúvida confira este [guia de como contribuir no GitHub](./CONTRIBUTING.md)

---
