# Política de Segurança — Microsoft Cloud Study Hub

## 🔒 Princípios de DevSecOps e Zero Trust
O **Microsoft Cloud Study Hub** adota rigorosamente as diretrizes de segurança, compliance e governança alinhadas às certificações **SC-900** e **AZ-104**.
A integridade deste repositório baseia-se nos pilares do modelo **Zero Trust** (*Nunca confie, sempre verifique*):

- **Sanitização do Código:** É terminantemente proibido realizar commits contendo credenciais ativas, chaves de API, *connection strings*, tokens OAuth, senhas ou certificados privados de ambientes do Microsoft Azure ou Entra ID.
- **Proteção de Artefatos:** Uso ativo do arquivo `.gitignore` para impedir o envio acidental de arquivos locais de ambiente (`.env`), caches de compilação, bancos de dados temporários e diretórios de IDEs (`.vs/`).
- **Anonimização de Evidências:** Todas as capturas de tela, logs de execução e arquivos de documentação utilizam identidades sintéticas, domínios de teste (`@onmicrosoft.com` / `@outlook.com`) e subredes privadas reservadas para estudo.

---

## 🚨 Reporte Responsável de Vulnerabilidades
Se você identificar qualquer credencial exposta, falha de configuração ou vulnerabilidade de segurança neste repositório.

1. **NÃO** abra uma *Issue* pública no GitHub.
2. Notifique diretamente o mantenedor do projeto enviando os detalhes do achado para o perfil oficial do proprietário.
3. As medidas de sanitização, revogação de tokens e purge do histórico do Git (caso necessário) serão aplicadas imediatamente.

---

## 📋 Conformidade do Repositório
- **Histórico Rastreável:** Todas as alterações de código e documentação são vinculadas aos tickets de governança via Issue Keys do Jira (`HUB-X`).
- **Data de Inicialização:** 01/09/2026
- **Primeiro Commit Registrado:** 11/09/2026 (`feat(HUB-1): Inicialização da estrutura base do repositório no GitHub`)

---
**Criado por:** Rafael Martiniano ([@rmartini3](https://github.com/rmartini3))