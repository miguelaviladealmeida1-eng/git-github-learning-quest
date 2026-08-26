# Referência de comandos Git

## Identidade

```bash
git config --global user.name "Seu Nome"
git config --global user.email "seu@email.com"
```

## Ciclo básico

```bash
git status
git add .
git commit -m "feat: minha alteração"
git log --oneline --graph --decorate
git diff
```

## Branches

```bash
git branch
git switch -c feature/nova-funcionalidade
git switch develop
git merge feature/nova-funcionalidade
git branch -d feature/nova-funcionalidade
```

## Remoto

```bash
git remote -v
git fetch origin
git pull --rebase origin develop
git push -u origin minha-branch
```

## Histórico

```bash
git log --oneline
git show <commit>
git revert <commit>
git reset --soft HEAD~1
```

> ⚠️ `reset --hard` pode apagar alterações locais. Use somente quando entender o impacto.

## Inspeção

```bash
git status --short
git diff --staged
git reflog
git branch -vv
git remote -v
```
