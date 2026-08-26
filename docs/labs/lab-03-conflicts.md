# Laboratório 03 — Resolução de conflitos

## Objetivo

Aprender a identificar e resolver um conflito de merge com segurança.

## Cenário

Duas branches alteraram o mesmo trecho de um arquivo.

## Processo

```bash
git switch develop
git pull --rebase origin develop
git switch feature/minha-alteracao
git merge develop
```

Quando houver conflito:

1. Execute `git status`.
2. Abra os arquivos marcados.
3. Escolha conscientemente a versão correta.
4. Remova os marcadores `<<<<<<<`, `=======` e `>>>>>>>`.
5. Execute `git add`.
6. Finalize o merge.

```bash
git add .
git commit
```

## Regra de ouro

Nunca resolva conflitos no automático sem entender qual comportamento deve permanecer.
