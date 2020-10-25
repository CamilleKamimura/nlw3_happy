<h1 align="center">
  <img alt="NextLevelWeek" title="#NextLevelWeek" src="./assets/logo.svg" />
</h1>

<p align="center">
 <a href="#sobre">Sobre</a> •
 <a href="#tecnologias">Tecnologias</a> • 
 <a href="#pré-requisitos">Pré-requisitos</a> • 
  <a href="#getting-started">Getting Started</a> • 
 <a href="#licenc-a">Licença</a> •
</p>


### Sobre 🚀

O Happy é um projeto que visa facilitar visitas aos orfanatos próximos a você 💜

Este é um projeto desenvolvido durante a Next Level Week, realizada pela @Rocketseat durante os dias 12 a 18 de Outubro de 2020.

### Tecnologias ⚒️

As seguintes ferramentas foram usadas na construção do projeto:

- [Expo](https://expo.io/)
- [Node.js](https://nodejs.org/en/)
- [React](https://pt-br.reactjs.org/)
- [React Native](https://reactnative.dev/)
- [TypeScript](https://www.typescriptlang.org/)

### Pré-requisitos ⚠️

Antes de começar, você vai precisar ter instalado em sua máquina as seguintes ferramentas:
[Git](https://git-scm.com), [Node.js](https://nodejs.org/en/). 

Além disto é bom ter um editor para trabalhar com o código como [VSCode](https://code.visualstudio.com/)


### Getting Started 🎬

#### Rodando o Back End (servidor) ⚙️

```bash
# Clone este repositório
$ git clone <https://github.com/CamilleKamimura/nlw3_happy.git>

# Acesse a pasta do projeto no terminal/cmd
$ cd nlw3_happy

# Vá para a pasta backend
$ cd backend

# Instale as dependências
$ yarn or npm install

# Use o seguinte comando para executar as migrations
$ yarn typeorm migration:run

# Execute o serviço da api 
$ yarn dev or npm dev

```

#### Rodando o Front End (web) 🖥️

Obs.: Before to continue, be sure to have the API running

```bash
# Certifique-se que o arquivo 'src/services/api.ts' possui o mesmo IP de sua API

# Vá para a pasta web
$ cd web

# Instale as dependências
$ yarn or npm install

# Execute a aplicação em modo de desenvolvimento
$ yarn start or npm start

```

#### Rodando o Front End (mobile) 📱

Obs.: Before to continue, be sure to have the API running

```bash
# Certifique-se que o arquivo 'src/services/api.ts' possui o mesmo IP de sua API

# Vá para a pasta mobile
$ cd mobile

# Instale as dependências
$ yarn or npm install

# Execute a aplicação em modo de desenvolvimento
$ yarn start or npm start

```

### Licença 🔐
Esse projeto está sob a licença MIT. Veja o arquivo [LICENSE](https://github.com/CamilleKamimura/nlw3_happy/blob/feature/Atualiza_README/LICENSE.md "LICENSE.md") para mais detalhes.
