# Git Workflow

## Start a task

```bash
git checkout main
git pull origin main
git checkout -b feature/project-cards
```

Choose the prefix that matches your work: `feature/`, `fix/`, `style/`, or `docs/`.

## Save and share work

```bash
git status
git add .
git commit -m "feat: add project cards"
git push -u origin feature/project-cards
```

Stage deliberately: check `git status` before committing and avoid including unrelated files.

## Keep your branch current

Before opening or updating a Pull Request, bring in the latest `main` using the approach your team lead prefers (merge or rebase). Resolve conflicts carefully, test again, then push the updated branch.

## Protect main

Never commit directly to `main`. Changes enter `main` through an approved Pull Request only.
