# OneClip (anciennement Cadreur) — versions publiées

Ce dépôt est le « cloud » de **OneClip Hub** : le Hub y lit `catalog.json` et télécharge les mises à jour.
Il ne contient que les versions de l'application, pas son code.

| Application | Version | Publiée le |
|---|---|---|
| OneClip | 0.7.0 | 24/10/2026 |
| OneFile | 1.2.1 | 27/10/2026 |
| OneMirror | 1.0.0 | 25/10/2026 |
| Billythebot | 1.0.1 | 26/10/2026 |
| OneClip Hub | 1.4.0 | 26/10/2026 |

## Installer OneClip Hub

Le Hub installe OneClip, OneFile, OneMirror et Billythebot puis les tient à jour tout seul.

## Nouveautés de OneClip 0.7.0

- Cadreur devient OneClip : nouveau nom, nouveau logo et nouvelle icône (translucide en grand, unie en petit). Vos projets, réglages et raccourcis sont conservés.
- Nouvelles couleurs : interface bleu nuit et crème, avec un bleu d'accent réservé aux actions principales.
- Panneaux redimensionnables (poignées entre les panneaux et au-dessus de la timeline) et repliables (boutons en haut à droite) ; votre disposition est gardée d'un lancement à l'autre.
- Sur un petit écran, les panneaux rétrécissent puis se replient d'eux-mêmes pour laisser la place à l'aperçu ; sur un grand écran, ils s'élargissent.
- Propriétés du montage rangées en catégories repliables : Transformation, Animation, Vitesse, Audio, Couleur, Effets, Masques, Suivi, Fondus, Sous-titres, Informations du média.
- Avec plusieurs plans sélectionnés, chaque catégorie indique si elle modifie tous les plans ou seulement le plan actif.
- Champs numériques plus précis : flèches ↑ ↓ au clavier, saisie au clavier vérifiée avec un message si la valeur n'est pas reconnue.
- Toutes les fenêtres restent centrées et entièrement visibles quand vous redimensionnez Cadreur ; le focus va au bon endroit et revient d'où vous veniez ; Échap ferme.
- Le menu du clic droit ne sort plus de l'écran et se pilote au clavier.
- Nouveau menu Cadreur (le logo) : accueil, nouveau montage, créer des clips, enregistrer, réglages, raccourcis et « À propos » avec la version et ce dont Cadreur a besoin sur l'ordinateur.
- Le graphique d'intensité des moments est plus grand, avec un axe des temps et la valeur exacte au survol.
- Moniteurs : avance image par image et état de chargement dans le moniteur source, message clair si un fichier ne se lit pas, image toujours au bon ratio quelle que soit la qualité d'aperçu.
- Timeline : vignettes le long des plans vidéo (calculées en arrière-plan et gardées), confirmation avant de supprimer une piste qui contient des plans.
- Cadreur se rouvre à la même taille et au même endroit, et revient sur l'écran si celui-ci a été débranché.
- Les projets récents signalent les vidéos introuvables, et le Cadreur Hub peut ouvrir un projet ou démarrer un montage directement.
- Nouveau réglage « Réduire les animations », zones de clic agrandies et textes plus lisibles partout.

## Nouveautés de OneFile 1.2.1

- Les vidéos YouTube sont acceptées dans l’onglet « Depuis un lien » : colle le lien, OneFile affiche le titre, la chaîne, la durée et la miniature.
- Choix de la qualité (de 360p jusqu’à 4K, 1080p par défaut) et du format : MP4 tel quel, ou converti en WebM, MKV, MOV, GIF, MP3, M4A ou WAV. Pour un son, seul le son est téléchargé.
- Un lien YouTube collé dans l’onglet Vidéos ou Sons ajoute directement la vidéo (ou le son) à la liste.
- Au premier usage, OneFile installe son outil YouTube (environ 18 Mo, une seule fois) et le tient à jour tout seul chaque jour.
- Playlists, chaînes, directs en cours et vidéos privées ou réservées aux adultes sont expliqués clairement au lieu d’échouer.

## Nouveautés de OneMirror 1.0.0

- Première version de OneMirror : l’écran de ton téléphone Android sur le PC, gratuit, sans publicité et sans limite de temps.
- Par câble USB pour la meilleure image, ou en Wi-Fi : « Passer en Wi-Fi » en un clic, ou association sans câble avec un code (Android 11+).
- Le son du téléphone sort du PC, et tu utilises le téléphone à la souris et au clavier (clic droit = retour).
- Pensé pour OBS : fenêtre « OneMirror » au titre fixe, préréglages Stream (1080p 60 i/s), Qualité max et Économie, fenêtre sans bordure.
- Manette du PC pour les jeux mobiles, écran du téléphone éteint pendant l’affichage, caméra du téléphone comme webcam.
- Captures d’écran (Images\OneMirror) et enregistrement vidéo (Vidéos\OneMirror) en un clic.
- Guide pas à pas pour activer le débogage USB, et messages clairs si le téléphone n’est pas autorisé ou se déconnecte.

## Nouveautés de Billythebot 1.0.1

- Correction : la construction ne s’arrête plus à l’étape « Catégories et salons » (Discord refusait de ranger plusieurs salons d’un coup). Clique sur « Réessayer » : Billy reprend là où il s’était arrêté, sans rien créer en double.
