# Formations GitHub & IA — Débutants

Ce petit site présente des modules pour débuter avec GitHub et l'IA.

## Ouvrir et visualiser dans VS Code

1. Ouvrez le dossier du projet dans VS Code (`Cours IA`).
2. Pour servir le site localement :

```powershell
# depuis le dossier du projet
python -m http.server 8000
```

3. Ou utilisez la tâche VS Code : `Terminal` → `Run Task...` → `Serve site (Python 3)`.
4. Ouvrez ensuite dans un navigateur : `http://localhost:8000`.

## Aperçu dans VS Code (extension)

- Vous pouvez installer l'extension Live Server et cliquer sur `Go Live`.

## Fichiers importants

- [index.html](index.html)
- [styles.css](styles.css)
- [script.js](script.js)
- [.vscode/tasks.json](.vscode/tasks.json)

## Déployer sur GitHub Pages

Le site est déjà publié sur :

https://maxenceytb01.github.io/formations-github-ia-debutants/

### Ouvrir le site localement

1. Ouvrir le dossier du projet dans VS Code.
2. Exécuter `Tasks: Run Task`.
3. Choisir `Open index.html (fallback)` pour ouvrir le site directement dans le navigateur.

Si tu as Python installé :

```powershell
cd "c:\Users\jean\OneDrive\Documents\Cours IA"
python -m http.server 8000
```
Puis ouvre `http://localhost:8000`.

### Mise à jour

- Si tu changes `index.html`, `styles.css` ou `script.js`, il suffit de pousser les fichiers sur GitHub.
- GitHub Pages mettra automatiquement à jour le site en ligne.
