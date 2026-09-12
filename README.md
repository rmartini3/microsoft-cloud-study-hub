# Microsoft Cloud Study Hub

[![Status](https://img.shields.io/badge/Status-Em%20Construção-orange)]()
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

<p align="center">
  <img width="850" alt="Demonstração do Projeto Jira" src="https://github.com/user-attachments/assets/99a5b8c6-fde8-4518-bfc3-cf7a9552d811" />
</p>


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

# Próximos Passos
- Encerrar o ticket HUB-1 e dar início imediato à Sprint 1 (AZ-900).

🔄 Rastreabilidade de Commits
Todas as contribuições seguem a taxonomia de rastreabilidade vinculada aos tickets do Jira via Issue Keys:
HUB-X: [Descrição da entrega técnica]

Autor: Rafael Martiniano (@rmartini3)
