# Spec: Consolidação Baseada em Domínio (`domain-consolidation`)

## 1. Contexto & Motivação
A organização SecurityStandards unifica seus 5 repositórios de padrões em [`security-standards`](https://github.com/SecurityStandards/security-standards). Em vez de adotar indexação numérica sequencial de specs (`<NNN>-<feature>`), a governança deste repositório e da organização passa a operar no formato **Domain-Based**: cada especificação é nomeada diretamente pelo seu domínio de atuação e escopo de negócio (`docs/specs/<domain>/`).

## 2. Requisitos & Escopo

### Requisitos Funcionais (RF)
* **RF01:** Estruturar o repositório como uma base 100% canônica em Markdown legível diretamente pelo GitHub e por agentes de IA.
* **RF02:** Transformar templates `.md.tmpl` em arquivos Markdown puros (`policies/` e `procedures/`).
* **RF03:** Transformar mapeamentos de normas (`standards/*.json`) em documentação estruturada Markdown (`standards/*.md`).
* **RF04:** Extrair os checklists interativos do CTO e DevOps em listas Markdown com checkboxes (`checklists/`).
* **RF05:** Converter os questionários de avaliação de risco do Google VSAQ em questionários Markdown (`questionnaires/`).
* **RF06:** Centralizar o template de página pública de segurança em `templates/security-page/`.

### Requisitos Não-Funcionais (RNF)
* **RNF01:** Zero necessidade de runtime de compilação ou build pesado para ler o repositório.
* **RNF02:** Compatibilidade total com Spec-Driven Development orientada a domínio.

## 3. Critérios de Aceite
- [x] Políticas disponíveis em Markdown legível em `policies/`.
- [x] Procedimentos de controle documentados em `procedures/`.
- [x] Mapeamentos de normas normativas (NIST CSF, HIPAA, PCI DSS, CIS, FedRAMP) em `standards/`.
- [x] Checklists acionáveis com checkboxes em `checklists/`.
- [x] Questionários VSAQ em Markdown em `questionnaires/`.
- [x] Template de página pública em `templates/security-page/README.md`.
- [x] `AGENTS.md` e regras atualizadas para padrão **Domain-Based** (`docs/specs/<domain>/`).
