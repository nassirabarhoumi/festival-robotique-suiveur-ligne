# 🏁 Classement Suiveur de Ligne — Festival de Robotique 1.0

Application web (un seul fichier `index.html`) pour gérer en direct le classement
de la compétition **Suiveur de Ligne** — Les Petits Génies de la Robotique.

## Fonctionnalités
- Saisie des scores et chronos sur **3 matchs** par équipe (chrono intégré ▶).
- Classement **par groupe = catégorie + tranche d'âge** (tableaux indépendants) :
  - Catégories : 🟦 Basic · 🟥 Advanced
  - Tranches d'âge : Benjamin (≤9 ans) · Junior (10–13 ans) · Senior (14–18 ans)
- Règle de classement : **meilleur match** (meilleur score d'abord, puis le **chrono de ce même match** à égalité) — max 15 pts/match, sans cumul.
- **Validation** par équipe avant mise à jour du classement.
- **Modification** du nom / catégorie / âge et **photo** de chaque équipe.
- Écran d'**affichage final** festif (podium, confettis, animations).
- Sauvegarde automatique dans le navigateur (localStorage).

## Utilisation
Ouvrir le site, ajouter les équipes, saisir les scores → le classement se met à jour après validation.

> ℹ️ Les données (scores, photos) sont stockées **localement** dans le navigateur de l'appareil utilisé.
