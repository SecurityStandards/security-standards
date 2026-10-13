# Plano de Implementação: Consolidação `security-standards`

## 1. Estrutura Canônica de Diretórios

```text
security-standards/
├── policies/              # Templates de políticas (origem: security-policy-templates)
│   ├── templates/         # Políticas completas (Access Control, Incident Response, etc.)
│   └── mappings/          # Mapeamento para frameworks (NIST, HIPAA, PCI DSS, CIS)
├── checklists/            # Checklists consolidados
│   ├── cto-security/      # Checklist de segurança para lideranças técnicas
│   └── devops-security/   # Checklist de segurança para DevOps/Infra
├── questionnaires/        # Questionários de terceiros
│   └── vsaq/              # Vendor Security Assessment Questionnaire (Google VSAQ)
├── templates/             # Componentes e páginas públicas
│   └── security-page/     # Template para página de segurança pública e disclosure
├── docs/specs/
│   └── 001-consolidation/
├── AGENTS.md
└── README.md
```

## 2. Decisões Técnicas
- **Abordagem Git:** Estruturação direta dos conteúdos com documentação de procedência e links aos upstreams canônicos.
- **Portabilidade:** Todo o conteúdo é Markdown padrão compatível com GitHub Flavored Markdown e ferramentas de RAG / LLM.
