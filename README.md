
# QA Cypress Framework

Framework de automação de testes End-to-End desenvolvido com **Cypress** e **JavaScript**, seguindo boas práticas de automação para aplicações Web.

![Cypress](https://img.shields.io/badge/Cypress-Testing-brightgreen)

![JavaScript](https://img.shields.io/badge/JavaScript-ES6-yellow)

![Node](https://img.shields.io/badge/Node.js-18-green)

<img width="1904" height="947" alt="Captura de tela 2026-07-25 131437" src="https://github.com/user-attachments/assets/8d7aabbe-64df-4db9-b210-e5a54ffd7f9b" />

---

## Objetivo

Este projeto foi criado para automatizar cenários críticos de aplicações Web, utilizando Cypress como framework principal de testes.

O objetivo é demonstrar a organização de um projeto de automação, reutilização de código e boas práticas utilizadas em ambientes corporativos.

---

## Tecnologias

- Cypress
- JavaScript
- Node.js
- npm

---

## Estrutura do projeto

```text
projeto-cypress/
└── cypress/
    ├── fixtures/
    │   ├── example.json
    │   └── usuarios.json
    ├── integration/
    │   └── 3-ALURAPIC/
    │       ├── alura-busca.spec.js
    │       ├── alurapic.spec.js
    │       ├── api-alurapic.spec.js
    │       ├── cadastro.spec.js
    │       └── login.spec.js
    ├── plugins/
    ├── report/
    └── support/
```

---

## Cenários automatizados

### Testes de interface

- Validação da tela inicial
- Login com usuário válido
- Login com usuário inválido
- Cadastro de usuários
- Validação de campos obrigatórios
- Validação de e-mail inválido
- Validação de senha com tamanho mínimo
- Busca de cursos

### Testes de API

- Consulta de fotos via requisição GET
- Validação do status da resposta
- Validação do corpo da resposta
- Validação do tempo de resposta
- Autenticação via requisição POST

### Recursos utilizados

- Fixtures para massa de dados
- Custom commands
- Hooks com `beforeEach`
- Interceptação de requisições com `cy.intercept()`
- Relatórios com Mochawesome
---

## Como executar

Instalar as dependências:

```bash
npm install
```

Executar em modo gráfico:

```bash
npx cypress open
```

Executar via terminal:

```bash
npx cypress run
```

---

## Melhorias futuras

- Atualização para uma versão mais recente do Cypress
- Integração com GitHub Actions
- Implementação de Page Object Model
- Uso de variáveis de ambiente protegidas
- Inclusão de evidências de execução

---

## Autora

**Luana do Amaral Bastos**

QA Sênior | Automação de Testes | Cypress | Playwright | Appium | APIs | Azure DevOps
