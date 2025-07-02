# Demoblaze Cypress Tests

<h2 align="center">Hi 👋! Meu nome e Hugo criador desse projeto.</h2>

###

<div align="left">
</div>

###

<br clear="both">

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/Hugogome2/Hugogome2/output/pacman-contribution-graph-dark.svg">
  <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/Hugogome2/Hugogome2/output/pacman-contribution-graph.svg">
  <img alt="pacman contribution graph" src="https://raw.githubusercontent.com/Hugogome2/Hugogome2/output/pacman-contribution-graph.svg">
</picture>

###

![Node.js](https://img.shields.io/badge/Node.js-%3E%3D14.x-43853C) ![JavaScript](https://img.shields.io/badge/JavaScript-ES6-yellow) ![Cypress](https://img.shields.io/badge/Cypress-latest-04D361) ![GitHub Actions](https://img.shields.io/badge/GitHub%20Actions-CI-blue)

## Descrição do Projeto

Este repositório contém uma suíte de testes end-to-end desenvolvida com **Cypress** para automação da interface web do site Demoblaze, um e-commerce de exemplo. O objetivo é demonstrar boas práticas de QA em testes de UI, incluindo:

* Verificação de fluxos de compra (sucesso e falhas).
* Interações com elementos dinâmicos.
* Uso de fixtures para dados de teste.
* Comandos customizados.
* Integração contínua via GitHub Actions.

## Stack de Ferramentas e Linguagens

* **Node.js** (>=14.x): ambiente de execução JavaScript no servidor.
* **npm**: gerenciador de pacotes.
* **JavaScript (ES6+)**: linguagem de programação utilizada nos testes.
* **Cypress**: framework de automação de testes E2E.
* **GitHub Actions**: CI para execução automática de testes.

## Badges

As badges indicam as versões das ferramentas e o status do CI.

## Pré-requisitos

* Node.js (>=14.x)
* npm (>=6.x)

## Instalação

1. Clone este repositório:

   ```bash
   git clone https://github.com/SEU_USUARIO/demoblaze-cypress-tests.git
   cd demoblaze-cypress-tests
   ```
2. Instale as dependências:

   ```bash
   npm install
   ```

## Executando os Testes

* Modo interativo:

  ```bash
  npx cypress open
  ```
* Modo headless (CI):

  ```bash
  npx cypress run
  ```

## Estrutura de Pastas

```text
demoblaze-cypress-tests/
├── cypress/
│   ├── fixtures/         # Dados de teste (JSON)
│   ├── integration/      # Specs de teste
│   ├── support/          # Comandos customizados e configurações
│   └── plugins/          # Plugins do Cypress
├── .github/
│   └── workflows/        # Configuração do GitHub Actions
├── node_modules/
├── cypress.json          # Configuração principal do Cypress
├── package.json
└── README.md
```

## Contribuição

Sinta-se à vontade para abrir issues e pull requests. Qualquer feedback é bem-vindo!

## Licença

Este projeto está licenciado sob a licença [MIT](LICENSE).
