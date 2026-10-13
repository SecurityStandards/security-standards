# Plano de Implementação: Arquitetura Domain-Based

## 1. Estrutura de Domínios no Repositório

```text
security-standards/
├── policies/             # Domínio: Políticas de Segurança da Informação (Markdown puro)
├── procedures/           # Domínio: Procedimentos de Controle e Auditoria
├── standards/            # Domínio: Mapeamentos Regulatórios (NIST, HIPAA, PCI, CIS)
├── checklists/           # Domínio: Checklists de Engenharia e Liderança (CTO & DevOps)
│   ├── cto-security/
│   └── devops-security/
├── questionnaires/       # Domínio: Avaliação de Terceiros e Riscos (Google VSAQ)
├── templates/            # Domínio: Templates Institucionais (Security Page)
│   └── security-page/
├── docs/specs/
│   └── domain-consolidation/
├── AGENTS.md
└── README.md
```

## 2. Decisões Técnicas
- **Spec-Driven Domain-Based:** Substituição do modelo `<NNN>-<feature>/` por `<domain>/`. Cada domínio tem escopo atômico, seu próprio `spec.md`, `plan.md` e `tasks.md`.
- **Pure Markdown:** Eliminação de templates com tags Mustache/Handlebars não compiladas em favor de Markdown limpo e auditável.
