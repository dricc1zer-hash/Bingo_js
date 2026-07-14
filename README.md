# Bingo

Jeu de bingo pour jeux vidéos . utilisable egalement pour les réunions/marathons ...

## Lancer le jeu

Le jeu est une application web statique. Pour un test local fiable, lancez un petit serveur dans ce dossier puis ouvrez `index.html`. Sur GitHub, il peut être publié directement avec GitHub Pages.

## Fonctionnalités portées

- pour le mode Bingo Grille 5 x 5 générée depuis la liste de propositions.
- pour le mode Conquete Grille 7 x 7 générée depuis la liste de propositions.
- Mode `Normal` et mode `Facile` avec région affichée.
- Filtre par longueur minimum et maximum.
- Chronomètre avec limite de temps.
- Quatre joueurs/couleurs : vert, rouge, bleu, jaune.
- Cases multi-couleurs.
- Calcul des scores du mode Bingo : cases validées + bonus par ligne, colonne ou diagonale complète.
- Calcul des scores du mode Conquete : cases validées.

## Fonctionnalités ajoutées
- Français/anglais
- Gestion de graines

## Fichiers utiles

- `index.html` : page du jeu.
- `styles.css` : mise en page.
- `app.js` : logique JavaScript.
...
  
## Publication GitHub

Les dossiers de build Python sont ignorés par `.gitignore` afin de garder un dépôt léger.
