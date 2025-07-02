# 🚀 Demoblaze Cypress Tests

<h2 align="center">Hi 👋! Meu nome é Hugo, criador desse projeto.</h2>

<div align="center">
</div>

---

<div align="center">
  ![JavaScript](https://img.shields.io/badge/javascript-%23323330.svg?style=flat&logo=javascript&logoColor=%23F7DF1E)
  ![cypress](https://img.shields.io/badge/-cypress-%23E5E5E5?style=flat&logo=cypress&logoColor=058a5e)
  ![NodeJS](https://img.shields.io/badge/node.js-6DA55F?style=flat&logo=node.js&logoColor=white)
  ![NPM](https://img.shields.io/badge/NPM-%23CB3837.svg?style=flat&logo=npm&logoColor=white)
</div>

---

## 📝 Descrição do Projeto

Este repositório contém uma suíte de testes end-to-end desenvolvida com **Cypress** para automação da interface web do site **Demoblaze**, um e-commerce de exemplo. O objetivo é demonstrar boas práticas de QA em testes de UI, incluindo:

* ✅ Verificação de fluxos de compra (sucesso e falhas).
* 🔄 Interações com elementos dinâmicos.
* 📁 Uso de fixtures para dados de teste.
* 🧩 Comandos customizados.
* ⚙️ Integração contínua via GitHub Actions.

## 🛠️ Stack de Ferramentas e Linguagens

* **Node.js** (>=14.x): ambiente de execução JavaScript no servidor.
* **npm**: gerenciador de pacotes.
* **JavaScript (ES6+)**: linguagem de programação utilizada nos testes.
* **Cypress**: framework de automação de testes E2E.
## 🚦 Pré-requisitos

* Node.js (>=14.x)
* npm (>=6.x)

## 💻 Instalação

1. Clone este repositório:

   ```bash
   git clone https://github.com/SEU_USUARIO/demoblaze-cypress-tests.git
   cd demoblaze-cypress-tests
   ```

2. Instale as dependências:

   ```bash
   npm install
   ```

## ▶️ Executando os Testes

* **Modo interativo:**

  ```bash
  npx cypress open
  ```

* **Modo headless (CI):**

  ```bash
  npx cypress run
  ```

## 📁 Estrutura de Pastas

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

## 🤝 Contribuição

Sinta-se à vontade para abrir issues e pull requests. Qualquer feedback é bem-vindo!

## 📄 Licença

Este projeto está licenciado sob a licença [MIT](LICENSE).
