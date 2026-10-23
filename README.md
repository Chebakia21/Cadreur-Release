# Cadreur — versions publiées

Ce dépôt est le « cloud » de **Cadreur Hub** : le Hub y lit `catalog.json` et télécharge les mises à jour.
Il ne contient que les versions de l'application, pas son code.

| Application | Version | Publiée le |
|---|---|---|
| Cadreur | 0.6.0 | 23/10/2026 |
| Cadreur Hub | 1.0.0 | 22/10/2026 |

## Installer Cadreur Hub

Le Hub installe Cadreur puis le tient à jour tout seul.

## Nouveautés de Cadreur 0.6.0

- Nouvel onglet Suivi : « Suivre un visage » (cliquez le visage dans le moniteur) ou « Suivre un objet ou une personne » (dessinez un cadre autour).
- Le suivi tient compte des changements de plan, reconnaît le sujet quand il revient, et marque en rouge les moments où il est perdu au lieu d'inventer une position.
- Correction à la main : déplacez ou redimensionnez le cadre du sujet dans le moniteur, puis « Reprendre le suivi d'ici ».
- « Cadrer dessus » et « Zoomer dessus » : le plan suit le sujet tout seul (images clés de position et d'échelle, mouvements doux, sans bord noir).
- Recadrage automatique pour les vidéos verticales : sujet principal, groupe ou cadrage fixe, avec coupes nettes aux changements de plan et retour au centre quand personne n'est visible.
- Masques : flou, mosaïque, garder seulement l'intérieur ou le retirer, en ellipse ou rectangle, bord adouci, animables — et « Flouter » / « Mosaïque » qui suivent un visage.
- Nouvel effet Détourage : garde la personne au premier plan et retire le fond, à l'aperçu comme à l'export.
- Tout fonctionne hors ligne : les modèles d'analyse d'image sont inclus dans l'application.
- Si la carte graphique refuse l'analyse d'image, Cadreur passe tout seul au processeur (aussi pour le cadrage automatique de l'espace Clips).
