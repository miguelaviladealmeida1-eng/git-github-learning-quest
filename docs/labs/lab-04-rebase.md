# Laboratório 04 — Rebase interativo

## Objetivo

Organizar commits locais antes de abrir um Pull Request.

```bash
git switch feature/minha-feature
git rebase -i HEAD~3
```

No editor, pratique `pick`, `reword`, `squash` e `fixup`.

## Regras

- Nunca reescreva histórico compartilhado sem saber o impacto.
- Depois de um rebase publicado, pode ser necessário `git push --force-with-lease`.
- Prefira `--force-with-lease` a `--force`.

## Desafio

Crie três commits pequenos, reorganize-os em um histórico limpo e explique o resultado no Pull Request.
