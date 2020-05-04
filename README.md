<img alt="GoStack" src="https://storage.googleapis.com/golden-wind/bootcamp-gostack/header-desafios.png" />

<h3 align="center">
  🔥 Desafio: Primeiro projeto Node.js 🚀
</h3>

<p align="center">“Para quem fica melhor a cada dia, ficar pronto é utopia”!</blockquote>

---

<p align="center">
  <img alt="GitHub language count" src="https://img.shields.io/github/languages/count/jerp86/gostack-fundamentos-node">

  <img alt="GitHub top language" src="https://img.shields.io/github/languages/top/jerp86/gostack-fundamentos-node?logo=javascript&color=yellow">

  <img alt="GitHub repo size in bytes" src="https://img.shields.io/github/repo-size/jerp86/gostack-fundamentos-node?color=green">

  <br>

  <img alt="Codacy Badge" src="https://api.codacy.com/project/badge/Grade/46bffb8abc1b4de9a992d3adf392eaad">

  <img alt="GitHub code size in bytes" src="https://img.shields.io/github/last-commit/jerp86/gostack-fundamentos-node">

  <a href="https://www.linkedin.com/in/jerp/">
    <img alt="Made by Jerp86" src="https://img.shields.io/badge/made%20by-Jerp86-%2304D361">
  </a>
</p>

---

# Indice

- :rocket: [Sobre o Desafio](rocket-sobre-o-desafio)
- :memo: [Específicação dos testes](#memo-específicação-dos-testes)
- 👨‍💻️ [Tecnogias utilizadas](#%EF%B8%8F-tecnogias-utilizadas)
- 📦️ [Como baixar o projeto](#%EF%B8%8F-como-baixar-o-projeto)
- 🤔️ [Como contribuir](#%EF%B8%8F-como-contribuir)

---

## :rocket: Sobre o Desafio

O projeto **Fundamentos Node.JS** é o primeiro desafio do curso **Bootcamp GoStack** da [Rocketseat](https://rocketseat.com.br/), utilizando a técnica e tendência de [TDD (Test Driven Development)](https://pt.wikipedia.org/wiki/Test-driven_development).

Nesse desafio, foi criado uma aplicação para continuar treinando  do que foi aprendido até o momento no Node.js junto ao TypeScript, utilizando o conceito de models, repositories e services!

Essa aplicação deve armazenar transações financeiras de entrada e saída, que deve permitir o cadastro e a listagem dessas transações.

Foi utilizado o template que está disponível nessa [url](https://github.com/Rocketseat/gostack-template-fundamentos-node) onde haviam 3 (três) testes que deveriam ter sido resolvidos para ganhar a nota total do desafio.

---

## :memo: Específicação dos testes

Em cada teste, tem uma breve descrição no que a aplicação deve cumprir para que o teste passe.

Para esse desafio, foi proposto os seguintes testes:

- **`should be able to create a new transaction`**: Para que esse teste passe, a aplicação deve permitir que uma transação seja criada, e retorne um json com a transação criada.

- **`should be able to list the transactions`**: Para que esse teste passe, a aplicação deve permitir que seja retornado um objeto contendo todas as transações junto ao balanço de income, outcome e total das transações que foram criadas até o momento.

- **`should not be able to create outcome transaction without a valid balance`**: Para que esse teste passe, a aplicação não deve permitir que uma transação do tipo `outcome` extrapole o valor total que o usuário tem em caixa, retornando uma resposta com código HTTP 400 e uma mensagem de erro no seguinte formato: `{ error: string }`

---

## 👨‍💻️ Tecnogias utilizadas

O projeto foi desenvolvido utilizando as seguintes tecnologias:

- [Node.js](https://nodejs.org/)
- [TypeScript](https://www.typescriptlang.org/)
- [Express](https://expressjs.com/)
- [UUIDv4](https://www.npmjs.com/package/uuidv4)
- [Visual Studio Code](https://code.visualstudio.com/)
- [ESLint](https://eslint.org/)
- [Prettier](https://prettier.io/)
- [Editor Config](https://editorconfig.org/)

---

## 📦️ Como baixar o projeto

```bash
  # Clonar o repositório
  ❯ git clone https://github.com/jerp86/gostack-fundamentos-node.git

  # Entrar no diretório
  ❯ cd gostack-fundamentos-node

  # Instalar as dependências
  ❯ yarn
  # ou pode utilizar npm
  ❯ npm install

  # Iniciar o projeto
  ❯ yarn dev:server
  # ou pode utilizar npm
  ❯ npm dev:server

  # Iniciar os testes
  ❯ yarn test
  # ou pode utilizar npm
  ❯ npm test
```

---

<h4 align="center">
  Feito com ❤️ por Jerp86 👋️ <a href="mailto:jerp4@hotmail.com">Entre em contato!</a>
</h4>

<p align="center">
  <a href="https://www.linkedin.com/in/jerp/">
    <img alt="José Eduardo Rodrigues Pinto" src="https://img.shields.io/badge/LinkedIn-jerp-0e76a8?style=flat&logoColor=white&logo=linkedin">
  </a>
  <a href="https://www.facebook.com/jerpbtu">
    <img alt="José Eduardo Rodrigues Pinto" src="https://img.shields.io/badge/Facebook-jerpbtu-1778F2?style=flat&logoColor=white&logo=facebook">
  </a>
  <a href="https://www.instagram.com/jerpbtu/">
    <img alt="José Eduardo Rodrigues Pinto" src="https://img.shields.io/badge/Instagram-@jerpbtu-833AB4?style=flat&logoColor=white&logo=instagram">
  </a>
  <a href="https://www.instagram.com/jerpbtu/">
    <img alt="José Eduardo Rodrigues Pinto" src="https://img.shields.io/twitter/follow/jerpbtu?style=flat&logoColor=white&logo=Twitter">
  </a>
</p>
