# Portfolio

Mon portfolio de développeur, construit à partir de mes données GitHub.

Un seul fichier, `index.html`, sans étape de build. À chaque visite, la page charge
en direct mon profil, mes dépôts publics et mes contributions depuis l'API GitHub.
Une copie des données est intégrée au fichier et prend le relais si l'API ne répond pas.

## Modifier le contenu

En haut du script de `index.html` :

- `HERO_BIO` et `HERO_ROLE` : la présentation sous mon nom
- `EXTRA_LINKS` : LinkedIn, Behance, WhatsApp…
- `PRIVATE_PROJECTS` : les projets privés, invisibles pour l'API publique

## Déployer

Importer le dépôt sur Vercel (preset « Other », aucune commande de build),
ou activer GitHub Pages sur la branche `main`.
