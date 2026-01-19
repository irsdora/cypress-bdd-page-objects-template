# 🌐 Automação Web E2E: Cypress + Page Objects + Cucumber (BDD) 

⌨️ Em desenvolvimento por Isadora Silva [ linkedin.com/in/isadorarsilva/ ]

![Build Status](https://img.shields.io/github/actions/workflow/status/irsdora/cypress-bdd-page-objects-template/main.yml?branch=main)
![Cypress Version](https://img.shields.io/badge/cypress-13.0.0-brightgreen)
![JavaScript](https://img.shields.io/badge/javascript-ES6+-yellow)

## 📋 Sobre o Projeto
Este repositório contém a automação de testes de interface (UI) para o site ****. 
O objetivo é garantir a qualidade dos fluxos críticos de negócio, como login, busca de produtos e checkout.

O projeto foi estruturado utilizando as melhores práticas de mercado:
- **Page Objects Model (POM):** Para facilitar a manutenção dos seletores.
- **BDD (Behavior Driven Development):** Escrita de cenários em Gherkin para aproximação com o negócio.
- **Clean Code:** Código limpo e modularizado.

---

## 🛠️ Tecnologias e Ferramentas
- **Framework:** [Cypress](https://www.cypress.io/)
- **Linguagem:** JavaScript / Node.js
- **BDD:** Cypress Cucumber Preprocessor
- **Relatórios:** Mochawesome Reports
- **CI/CD:** GitHub Actions

## 🌐 Como Rodar o Projeto


- 📋 Instalação
- 📋 Execução dos Testes
- 📋 Evidências e Relatórios


 ## 🏗️ Estrutura do Projeto
```text
├── cypress
│   ├── e2e
│   │   ├── features         # Arquivos .feature (Gherkin)
│   │   └── step_definitions # Implementação dos passos
│   ├── pages                # Classes Page Objects (Seletores e Ações)
│   ├── support              # Comandos customizados e configurações
│   └── fixtures             # Massas de dados (JSON)
├── cypress.config.js        # Configurações do Cypress
└── package.json             # Dependências e scripts

