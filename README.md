# Premier dépôt – Initiation à Git et GitHub

Mon tout premier dépôt, créé pendant le cours d'initiation à Git à l'EFREI Paris. Il m'a servi à pratiquer le cycle de travail de base de Git sur une petite page web statique.

![HTML5](https://img.shields.io/badge/HTML5-E34F26?logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?logo=css3&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?logo=git&logoColor=white)

## Ce que j'ai pratiqué

- Créer un dépôt local et le relier à un dépôt distant GitHub
- Suivre des fichiers et des dossiers avec `git add` / `git commit`
- Publier les modifications avec `git push`
- Exclure des fichiers du suivi avec un `.gitignore`
- Ajouter une licence et un README à un projet

## Contenu

```
.
├── index.html       # Page web
├── style.css        # Mise en forme
├── images/          # Image utilisée sur la page
├── .gitignore       # Fichiers ignorés par Git
└── LICENSE          # Licence MIT
```

## Voir la page

Cloner le dépôt puis ouvrir `index.html` dans un navigateur :

```bash
git clone https://github.com/CorentinGervais/premier.git
cd premier
```

## Commandes Git utiles

| Commande | Rôle |
|---|---|
| `git status` | Voir l'état des fichiers |
| `git add <fichier>` | Préparer un fichier pour le prochain commit |
| `git commit -m "message"` | Enregistrer les modifications |
| `git push` | Envoyer les commits sur GitHub |
| `git pull` | Récupérer les modifications distantes |
| `git log --oneline` | Afficher l'historique |

## Licence

Le code est distribué sous licence [MIT](LICENSE). L'image du dossier `images/` n'est pas couverte par cette licence.

## Auteur

**Corentin Gervais** – Master Cybersécurité, EFREI Paris
