# Carnet de muscu

App iPhone de renforcement musculaire à la maison, aux élastiques et au poids du corps.

- **Séance guidée** : 7 exercices en duos (A1 + A2, B1 + B2…), série par série, avec compteur géant, chrono pour le gainage et minuteur de repos.
- **28 exercices** répartis en 7 groupes musculaires, tous faisables chez soi : élastiques, chaise, canapé, serviette, sac à dos.
- **Mélange** : nouvelle combinaison d'un geste, toujours équilibrée (un exercice par groupe).
- **Progression automatique** : une répétition de plus à chaque séance ; quand le haut de la fourchette est atteint sur toutes les séries, l'app passe au niveau suivant.
- **Semaine** : objectifs de l'OMS (150 min d'endurance, 2 jours de renforcement), course et foot comptent double.
- **Progrès** : tour de taille, records par exercice, historique des séances.

## Installer sur iPhone

1. Ouvrir https://badreljazouli.github.io/app-muscu/ dans Safari.
2. Toucher Partager, puis « Sur l'écran d'accueil ».

L'app s'ouvre ensuite en plein écran et fonctionne hors connexion.

## Données

Tout reste sur le téléphone (stockage local du navigateur). Rien n'est envoyé nulle part.
Pour ne rien perdre en changeant de téléphone : Réglages, puis « Copier la sauvegarde » ou « Envoyer la sauvegarde ».

## Fichiers

- `index.html` : toute l'app (HTML, CSS, JavaScript), sans dépendance
- `sw.js` : service worker pour le mode hors connexion
- `manifest.webmanifest`, `apple-touch-icon.png`, `icon-192.png`, `icon-512.png` : installation sur l'écran d'accueil
