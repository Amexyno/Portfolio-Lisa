# Portfolio — Lisa-Marie Roques Monardes Pizarro

Site statique (HTML/CSS/JS, sans dépendances) présentant le parcours de Lisa-Marie vers la diplomatie.

## Aperçu local

Ouvrir `index.html` dans un navigateur, ou lancer un petit serveur local :

```bash
python3 -m http.server 8000
```

puis ouvrir http://localhost:8000

## À personnaliser

- **Photo de portrait** : déposer un fichier à `assets/images/portrait.jpg` (un cadre s'affiche automatiquement tant qu'il n'y a pas de photo).
- **Couvertures de livres** : déposer les fichiers à
  - `assets/images/books/un-diplomate-mange-et-boit.jpg`
  - `assets/images/books/le-prince.jpg`
- **E-mail de contact** : remplacer `contact@example.com` dans la section Contact (`index.html`).
- **Dates de stage** : préciser les dates exactes du stage à l'Assemblée nationale et du futur stage à l'ambassade du Chili.
- **Analyses de livres** : le lien "Voir mon analyse du livre" pointe vers `pages/a-venir.html` (page "pas encore configurée"). Créer une vraie page par livre quand le contenu sera prêt, puis mettre à jour le `href` correspondant dans `index.html`.
- **MUN / éloquence** : ajouter les noms des conférences MUN et concours d'éloquence auxquels elle a participé.

## Déploiement gratuit

- **GitHub Pages** : pousser ce dossier sur un repo GitHub, activer Pages sur la branche `main`.
- **Netlify / Vercel** : glisser-déposer le dossier, aucun build nécessaire.
