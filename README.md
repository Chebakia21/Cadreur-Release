# Cadreur — versions publiées

Ce dépôt est le « cloud » de **Cadreur Hub** : le Hub y lit `catalog.json` et télécharge les mises à jour.
Il ne contient que les versions de l'application, pas son code.

| Application | Version | Publiée le |
|---|---|---|
| Cadreur | 0.6.1 | 23/10/2026 |
| Cadreur Hub | 1.0.0 | 22/10/2026 |

## Installer Cadreur Hub

Le Hub installe Cadreur puis le tient à jour tout seul.

## Nouveautés de Cadreur 0.6.1

- Correction : la création des sous-titres échouait sur certains clips avec le message « frameOffset out of range ». L'extraction du son a été refaite et fonctionne quels que soient le début et la fin du clip.
- Si un clip dépasse la fin du son de la vidéo, un message clair l'indique au lieu d'une erreur technique.
