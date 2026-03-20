# Portfolio — Jefferson Azafack Tsafack

Portfolio personnel déployable sur GitHub Pages.

## Déploiement sur GitHub Pages

1. Crée un dépôt GitHub nommé exactement : `ton-username.github.io`
2. Push les fichiers :
   ```bash
   git init
   git add .
   git commit -m "init: portfolio"
   git remote add origin https://github.com/TON_USERNAME/TON_USERNAME.github.io.git
   git push -u origin main
   ```
3. Va dans **Settings → Pages → Source → main / root** et sauvegarde.
4. Ton site sera disponible à `https://TON_USERNAME.github.io` en quelques minutes.

## Mettre à jour le portfolio

| Quoi mettre à jour | Où modifier |
|---|---|
| Nouvelle expérience | `index.html` → section `#experience`, copier un bloc `.timeline-item` |
| Nouveau projet | `index.html` → section `#projects`, copier un bloc `.project-card` |
| Nouvelle compétence | `index.html` → section `#skills`, ajouter un `<span>` dans le bon groupe |
| Nouvelle formation | `index.html` → section `#education`, copier un bloc `.edu-card` |
| Infos de contact | `index.html` → section `#contact` + en-tête `#hero` |

## Structure des fichiers

```
portfolio/
├── index.html       ← contenu principal
├── css/
│   └── style.css    ← tous les styles
├── js/
│   └── main.js      ← animations & interactivité
└── README.md
```
"# potfolio" 
