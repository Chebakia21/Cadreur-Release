# OneCloud

**Un seul programme à installer : OneCloud.** Il installe OneClip, OneFile et OneMirror, les ouvre, et les tient à jour tout seul.

## ⬇️ [Télécharger OneCloud](https://github.com/Chebakia21/Cadreur-Release/releases/latest/download/OneCloud-Setup.exe)

Pour Windows 10 et 11 (64 bits).

1. Clique sur le lien ci-dessus : le fichier **OneCloud-Setup.exe** se télécharge.
2. Ouvre-le. Si Windows affiche « Windows a protégé votre ordinateur », clique sur **Informations complémentaires**, puis sur **Exécuter quand même** (OneCloud n'est pas signé par un éditeur connu, c'est normal).
3. OneCloud s'ouvre tout seul. Clique sur **Installer** à côté du logiciel que tu veux.

Ensuite, plus rien à faire : chaque nouvelle version arrive toute seule dans OneCloud.

## Ce que contient OneCloud

| Logiciel | À quoi il sert | Version | Mise à jour |
|---|---|---|---|
| **OneClip** | Montage vidéo et clips : timeline multipiste, moments forts, cadrage, sous-titres, export. | 0.7.0 | 24/10/2026 |
| **OneFile** | Convertisseur de fichiers : images, vidéos, sons, PDF et archives, par lots, 100 % en local. | 1.2.1 | 27/10/2026 |
| **OneMirror** | L’écran de ton téléphone Android sur le PC, en USB ou en Wi-Fi, avec le son : prêt pour OBS. | 1.2.0 | 30/10/2026 |
| **OneCloud** | Installe et met à jour les trois logiciels. | 1.5.1 | 30/10/2026 |

## Nouveautés

### OneClip 0.7.0

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

### OneFile 1.2.1

- Les vidéos YouTube sont acceptées dans l’onglet « Depuis un lien » : colle le lien, OneFile affiche le titre, la chaîne, la durée et la miniature.
- Choix de la qualité (de 360p jusqu’à 4K, 1080p par défaut) et du format : MP4 tel quel, ou converti en WebM, MKV, MOV, GIF, MP3, M4A ou WAV. Pour un son, seul le son est téléchargé.
- Un lien YouTube collé dans l’onglet Vidéos ou Sons ajoute directement la vidéo (ou le son) à la liste.
- Au premier usage, OneFile installe son outil YouTube (environ 18 Mo, une seule fois) et le tient à jour tout seul chaque jour.
- Playlists, chaînes, directs en cours et vidéos privées ou réservées aux adultes sont expliqués clairement au lieu d’échouer.

### OneMirror 1.2.0

- Le volume du téléphone règle maintenant le son sur le PC : les boutons + et − du téléphone montent et baissent le son de OneMirror, comme dans le mélangeur de volume de Windows.
- Le volume du téléphone s’affiche sur la carte du téléphone pendant l’affichage (par exemple « 47 % »).
- Tu préfères garder le son du PC fixe ? Désactive « Le volume du téléphone règle le son sur le PC » dans la partie Son.

### OneCloud 1.5.1

- « Redémarrer » marche enfin : OneCloud se ferme puis se rouvre tout seul sur la nouvelle version, au lieu de rester fermé.
- Tout ce qui était prévu dans la 1.5 arrive avec : le nom OneCloud, le bouton « Désinstaller », la suppression de Billythebot de ton PC et OneMirror 1.1.

## Comment ce dépôt est rangé

Pas besoin de télécharger quoi que ce soit ici à la main : OneCloud s'en occupe.

| Élément | Rôle |
|---|---|
| `catalog.json` | La liste des logiciels et de leurs versions, lue par OneCloud. |
| `applications/oneclip` | Les fichiers de OneClip. |
| `applications/onefile` | Les fichiers de OneFile. |
| `applications/onemirror` | Les fichiers de OneMirror. |
| `applications/onecloud` | Les mises à jour de OneCloud lui-même. |

Le code des logiciels n'est pas ici : ce dépôt ne contient que les versions prêtes à installer.
