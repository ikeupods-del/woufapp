# Wouf — https://woufapp.fr

Carnet de santé, éducation et balades pour chiens et chats (application web installable).

Ce dépôt **publie** seulement le site. Le code source et les tests sont dans
[ikeupods-del/Quentools](https://github.com/ikeupods-del/Quentools) (dossier `wouf/`).
Le workflow `.github/workflows/publier.yml` récupère la dernière version validée, relance les tests
et publie sur GitHub Pages avec le domaine `woufapp.fr` (toutes les 3 heures, ou à la main : Actions → « Publier Wouf » → Run workflow).
