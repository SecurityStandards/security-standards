# Contrato Canônico de Agentes de IA - SecurityStandards / security-standards

Este documento define os requisitos mandatórios para qualquer agente trabalhando neste repositório.

## 1. Identidade & Assinatura Criptográfica (Inviolável)
- **Autor e Committer:** SEMPRE `Matheus Breguêz <matbrgz@gmail.com>`.
- **Assinatura GPG:** Todos os commits DEVEM ser assinados com a chave `B6FA8458D5176E83`.
- **Proibições:** NUNCA usar `--no-gpg-sign` ou sobrescrever autor.
- **Co-autoria da IA:** Apenas como trailer no rodapé do commit:
  `Co-Authored-By: <Agent Name> <noreply@...>`

## 2. Metodologia: Spec-Driven Development (SDD)
- Toda feature ou reestruturação segue especificações em `docs/specs/<NNN>-<feature>/` com `spec.md`, `plan.md` e `tasks.md`.
- Uma spec por domínio.

## 3. Higiene do Ambiente & Worktrees
- Operações paralelas em worktrees isoladas com limpeza após uso (`git worktree remove` e `git worktree prune`).
