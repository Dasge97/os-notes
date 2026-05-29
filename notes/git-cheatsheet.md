# Git cheat sheet

## Básicos
```bash
git status                 # estado del working tree
git add -p                 # añadir cambios por partes
git commit -m "mensaje"    # crear commit
git log --oneline --graph  # historial compacto
```

## Ramas
```bash
git switch -c nueva-rama   # crear y cambiar de rama
git branch -d rama         # borrar rama fusionada
git merge rama             # fusionar en la actual
```

## Deshacer
```bash
git restore archivo        # descartar cambios locales
git revert <sha>           # revertir un commit (seguro)
git reset --soft HEAD~1    # deshacer último commit, conservar cambios
```
