# OneCloud

**Un seul programme à installer : OneCloud.** Il installe OneClip, OneFile et OneMirror, les ouvre, et les tient à jour tout seul.

## ⬇️ [Télécharger OneCloud](https://raw.githubusercontent.com/Chebakia21/Cadreur-Release/main/installer/OneCloud-Setup.exe)

Pour Windows 10 et 11 (64 bits).

1. Clique sur le lien ci-dessus : le fichier **OneCloud-Setup.exe** se télécharge.
2. Ouvre-le. Si Windows affiche « Windows a protégé votre ordinateur », clique sur **Informations complémentaires**, puis sur **Exécuter quand même** (OneCloud n'est pas signé par un éditeur connu, c'est normal).
3. OneCloud s'ouvre tout seul. Clique sur **Installer** à côté du logiciel que tu veux.

Ensuite, plus rien à faire : chaque nouvelle version arrive toute seule dans OneCloud.

## Ce que contient OneCloud

| Logiciel | À quoi il sert | Version | Mise à jour |
|---|---|---|---|
| **OneClip** | Montage vidéo et clips : timeline multipiste, moments forts, cadrage, sous-titres, export. | 0.7.0 | 24/10/2026 |
| **OneFile** | Convertisseur de fichiers : images, vidéos, sons, PDF et archives, par lots, 100 % en local. | 1.4.0 | 31/10/2026 |
| **OneMirror** | L’écran de ton téléphone Android sur le PC, en USB ou en Wi-Fi, avec le son : prêt pour OBS. | 1.2.0 | 30/10/2026 |
| **OneCloud** | Installe et met à jour les trois logiciels. | 1.5.2 | 30/10/2026 |

## Nouveautés

### OneClip 0.7.0

- Nouveau nom, OneClip, avec un nouveau logo et nouvelle icône (translucide en grand, unie en petit). Vos projets, réglages et raccourcis sont conservés.
- Nouvelles couleurs : interface bleu nuit et crème, avec un bleu d'accent réservé aux actions principales.
- Panneaux redimensionnables (poignées entre les panneaux et au-dessus de la timeline) et repliables (boutons en haut à droite) ; votre disposition est gardée d'un lancement à l'autre.
- Sur un petit écran, les panneaux rétrécissent puis se replient d'eux-mêmes pour laisser la place à l'aperçu ; sur un grand écran, ils s'élargissent.
- Propriétés du montage rangées en catégories repliables : Transformation, Animation, Vitesse, Audio, Couleur, Effets, Masques, Suivi, Fondus, Sous-titres, Informations du média.
- Avec plusieurs plans sélectionnés, chaque catégorie indique si elle modifie tous les plans ou seulement le plan actif.
- Champs numériques plus précis : flèches ↑ ↓ au clavier, saisie au clavier vérifiée avec un message si la valeur n'est pas reconnue.
- Toutes les fenêtres restent centrées et entièrement visibles quand vous redimensionnez OneClip ; le focus va au bon endroit et revient d'où vous veniez ; Échap ferme.
- Le menu du clic droit ne sort plus de l'écran et se pilote au clavier.
- Nouveau menu OneClip (le logo) : accueil, nouveau montage, créer des clips, enregistrer, réglages, raccourcis et « À propos » avec la version et ce dont OneClip a besoin sur l'ordinateur.
- Le graphique d'intensité des moments est plus grand, avec un axe des temps et la valeur exacte au survol.
- Moniteurs : avance image par image et état de chargement dans le moniteur source, message clair si un fichier ne se lit pas, image toujours au bon ratio quelle que soit la qualité d'aperçu.
- Timeline : vignettes le long des plans vidéo (calculées en arrière-plan et gardées), confirmation avant de supprimer une piste qui contient des plans.
- OneClip se rouvre à la même taille et au même endroit, et revient sur l'écran si celui-ci a été débranché.
- Les projets récents signalent les vidéos introuvables, et OneCloud peut ouvrir un projet ou démarrer un montage directement.
- Nouveau réglage « Réduire les animations », zones de clic agrandies et textes plus lisibles partout.

### OneFile 1.4.0

- Nouvelle action pour les images : « Changer les dimensions ». Choisis une taille toute prête ou entre la tienne, et chaque image sort exactement à cette taille, à côté de l’original (« photo (1920x1080).jpg »).
- Plus de 40 tailles prêtes : écran (Full HD, 4K, vertical…), Twitch (photo de profil, bannière, écran hors ligne, panneau, emote, badge d’abonné, icône de points de chaîne), YouTube (miniature, bannière, filigrane, Short…), Instagram, TikTok, X, Discord, Facebook, LinkedIn et impression A4.
- Emotes, badges et icônes de points de chaîne Twitch : toutes les tailles demandées par Twitch d’un coup (par exemple 112, 56 et 28 px), en PNG transparent, dans un dossier.
- Quand les proportions ne sont pas les mêmes : « Remplir » (les bords qui dépassent sont rognés, en gardant le centre ou le sujet), « Tout garder » (bords flous, noirs, blancs ou transparents) ou « Étirer ».
- Taille personnalisée : remplis la largeur, la hauteur, ou une seule des deux pour garder les proportions.

### OneMirror 1.2.0

- Le volume du téléphone règle maintenant le son sur le PC : les boutons + et − du téléphone montent et baissent le son de OneMirror, comme dans le mélangeur de volume de Windows.
- Le volume du téléphone s’affiche sur la carte du téléphone pendant l’affichage (par exemple « 47 % »).
- Tu préfères garder le son du PC fixe ? Désactive « Le volume du téléphone règle le son sur le PC » dans la partie Son.

### OneCloud 1.5.2

- OneCloud se prépare au nouveau nom de son cloud sur GitHub (OneCloud au lieu de Cadreur-Release) : il cherche les mises à jour à la nouvelle adresse, et à l’ancienne en secours. Rien ne change pour toi.

## Comment ce dépôt est rangé

Pas besoin de télécharger quoi que ce soit ici à la main : OneCloud s'en occupe.

| Élément | Rôle |
|---|---|
| `installer/OneCloud-Setup.exe` | L'installateur de OneCloud (le lien « Télécharger OneCloud »). |
| `catalog.json` | La liste des logiciels et de leurs versions, lue par OneCloud. |
| `applications/oneclip` | Les fichiers de OneClip. |
| `applications/onefile` | Les fichiers de OneFile. |
| `applications/onemirror` | Les fichiers de OneMirror. |
| `applications/onecloud` | Les mises à jour de OneCloud lui-même. |

Le code des logiciels n'est pas ici : ce dépôt ne contient que les versions prêtes à installer.
