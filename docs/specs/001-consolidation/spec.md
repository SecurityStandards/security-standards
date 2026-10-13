# Spec 001: Consolidação de Padrões, Políticas e Governança

## 1. Contexto & Problema
A organização SecurityStandards possuía 5 repositórios separados para normas, governança e avaliação:
- `security-policy-templates` (templates de políticas mapeadas para NIST, HIPAA, PCI DSS, CIS)
- `CTOSecurityChecklist` (checklist para liderança técnica SaaS)
- `DevOpsSecurityChecklist` (checklist de segurança operacional e pipelines)
- `security-page` (template de página pública de segurança)
- `vsaq` (questionário interativo de avaliação de terceiros)

Essa dispersão gerava fragmentação de governança, redundância e dificuldade de consulta.

## 2. Requisitos e Escopo
- **RF01:** Consolidar os 5 repositórios em `security-standards` com arquitetura limpa em Markdown e dados estruturados.
- **RF02:** Preservar o histórico dos repositórios via `git subtree`.
- **RF03:** Unificar e categorizar checklists por papel (CTO, DevOps, AppSec).
- **RF04:** Fornecer templates exportáveis de políticas e página de segurança.
- **RNF01:** Zero dependências pesadas de build para consulta rápida; 100% interoperável com leitores Markdown e agentes de IA.

## 3. Critérios de Aceite
- [ ] Diretórios `policies/`, `checklists/`, `questionnaires/` e `templates/` populados.
- [ ] README.md canônico com índice unificado e guias de uso.
- [ ] Commits assinados e histórico preservado.
