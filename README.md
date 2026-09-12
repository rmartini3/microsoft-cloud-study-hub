# Microsoft Cloud Study Hub

[![Jira](https://img.shields.io/badge/Jira-Central%20Governance-blue)](https://stlabrm.atlassian.net)
[![GitHub](https://img.shields.io/badge/GitHub-Public%20Repo-181717)](https://github.com/rmartini3/microsoft-cloud-study-hub)
[![Azure DevOps](https://img.shields.io/badge/Azure%20DevOps-Boards%20%26%20ALM-0078D4)](https://dev.azure.com/stlabrm)

## 🎯 Sobre o Projeto
O **Microsoft Cloud Study Hub** é um ecossistema prático de aprendizado e governança focado no domínio técnico das certificações **AZ-900**, **SC-900** e **AZ-104**. 
O projeto simula uma esteira corporativa de engenharia de software e operações em nuvem (ALM) integrando ferramentas de mercado sob rígidos padrões de governança.

## 🛠️ Arquitetura de Governança (ALM & DevSecOps)
- **Jira Software Cloud:** Hub central de orquestração do backlog, Epics, User Stories e Sprints.
- **GitHub:** Versionamento de código, scripts de infraestrutura (IaC) e artefatos de laboratório.
- **Azure DevOps Services:** Gestão de Work Items e rastreabilidade de entregas técnicas via protocolo OAuth. (Em construção)
- **Confluence:** Base de conhecimento e documentação oficial dos fichamentos técnicos. (Em construção)

<img width="1432" height="738" alt="Projeto" src="https://github.com/user-attachments/assets/99a5b8c6-fde8-4518-bfc3-cf7a9552d811" />


## 📂 Estrutura do Repositório
```text
.
├── .gitignore
├── README.md
├── SECURITY.md
├── sprint-0-setup/      # Setup do ambiente, governança e conectores
├── az-900/              # Microsoft Azure Fundamentals
├── sc-900/              # Microsoft Security, Compliance, and Identity Fundamentals
└── az-104/              # Microsoft Azure Administrator

# Resumo
Ajuste do arquivo `README.md` para inclusão do status visual "Em Construção" e finalização dos artefatos da raiz do repositório para encerramento da Sprint 0.

# Certificação
**AZ-900 / SC-900 / AZ-104** (Sprint 0 — Documentação e Governança)

# Sprint
**Sprint 0 - Setup do Ambiente**

# Epic
- `AZ9-EPIC-01: Conceitos de Nuvem`
- `SC9-EPIC-01: Conceitos de Segurança, Compliance e Identidade`
- `AZ104-EPIC-01: Identidades e Governança`

# Story
* **HUB-1:** Implantação da Governança e Estrutura do Microsoft Cloud Study Hub *(Status: Em andamento)*

# Tasks
* **HUB-1.4:** Atualizar `README.md` com status de construção e realizar o `git push` final da Sprint 0.

# Subtasks
* **HUB-1.1:** Criar as colunas oficiais no Quadro Jira *(Status: Feito)*
* **HUB-1.2:** Criar projeto no Azure DevOps com colunas *(Status: Feito)*
* **HUB-1.3:** Integrar Jira com Azure DevOps via App Oficial *(Status: Feito)*
* **HUB-1.4:** Criar repositório GitHub, adicionar README/SECURITY e efetuar push *(Status: Fazendo)*

# Azure DevOps Work Items - (Em construção)
- **Epic ID 1:** Setup e Governança do Hub
  - **Feature ID 2:** Infraestrutura ALM
    - **User Story ID 3:** Publicação da Capa do Repositório em Construção *(State: Closed)*

# Template Confluence

```markdown
# Objetivo
Registrar a atualização da documentação de capa (README.md) do repositório com o marcador de status de evolução do projeto.
(Em construção)

# Referência Microsoft Learn / GitHub
- https://docs.github.com/pt/repositories/managing-your-repositorys-settings-and-features/customizing-your-repository/about-readmes

# Pré-Requisitos
- Repositório rmartini3/microsoft-cloud-study-hub ativo.

# Ambiente
- GitHub Cloud (rmartini3/microsoft-cloud-study-hub)

# Implementação
1. Adição do badge "Status: Em Construção".
2. Inclusão da nota explicativa de evolução contínua alinhada ao backlog do Jira.
3. Commit e Push das alterações contendo a tag HUB-1.

# Evidências
- README.md exibindo o badge laranja de projeto em construção no GitHub.

# Problemas Encontrados
- N/A

# Soluções
- N/A

# Lições Aprendidas
- Explicitar o estado de maturidade do projeto (WIP - Work in Progress) evita interpretações equivocadas de que o repositório está abandonado ou incompleto ao ser visualizado por terceiros.

# Próximos Passos
- Encerrar o ticket HUB-1 e dar início imediato à Sprint 1 (AZ-900).

🔄 Rastreabilidade de Commits
Todas as contribuições seguem a taxonomia de rastreabilidade vinculada aos tickets do Jira via Issue Keys:
HUB-X: [Descrição da entrega técnica]

Autor: Rafael Martiniano (@rmartini3)
