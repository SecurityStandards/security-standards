# Contrato Canônico de Agentes de IA - SecurityStandards / security-standards

Este documento define os requisitos mandatórios para qualquer agente trabalhando neste repositório.

## 1. Identidade & Assinatura Criptográfica (Inviolável)
- **Autor e Committer:** SEMPRE `Matheus Breguêz <matbrgz@gmail.com>`.
- **Assinatura GPG:** Todos os commits DEVEM ser assinados com a chave `B6FA8458D5176E83`.
- **Proibições:** NUNCA usar `--no-gpg-sign` ou sobrescrever autor.
- **Co-autoria da IA:** Apenas como trailer no rodapé do commit:
  `Co-Authored-By: <Agent Name> <noreply@...>`

## 2. Metodologia: Domain-Based Spec-Driven Development (SDD)
- Toda feature, refatoração ou consolidação estrutural deve ser guiada por especificações organizadas por **domínio**:
  - Padrão de diretório: `docs/specs/<domain>/` (ex.: `docs/specs/policies/`, `docs/specs/domain-consolidation/`).
  - Cada spec contém:
    - `spec.md` (o quê e por quê: escopo delimitado, requisitos e critérios de aceite).
    - `plan.md` (como: contratos, arquitetura e decisões técnicas).
    - `tasks.md` (tarefas de implementação incrementais e verificáveis).
- **Uma spec = um domínio**. Nunca misturar múltiplos domínios não correlatos em uma única spec.

## 3. Repositório Focado em Markdown & Conteúdo Canônico
- Todo o conteúdo deve ser apresentado diretamente em Markdown claro e legível nativamente no GitHub.
- Sem dependência obrigatória de compiladores ou runtimes proprietários para consulta ou consumo por agentes de IA.

## 4. Higiene do Ambiente & Worktrees
- Operações paralelas operam em worktrees isoladas com limpeza após uso (`git worktree remove` e `git worktree prune`).
