# Aiguillage

Un jeu de rythme en train à vapeur, à travers champs, forêts, villages et rivières. À chaque aiguillage, une voie porte un wagon et l'autre finit sur un butoir : change l'aiguillage du bon côté pile quand la locomotive y arrive. Chaque wagon pris (rondins, caisses, charbon, citerne, voyageurs, fruits) allonge le train. Joue les 1200 morceaux du plugin Rythme, ou ta propre musique.

*English version: [README.en.md](README.en.md)*

## Comment jouer

- **← ou D/F** : à gauche · **→ ou J/K** : à droite. Un **clic** marche aussi : sur la moitié gauche ou droite de l'écran.
- La **flèche** devant l'aiguillage montre le côté du wagon ; l'autre voie finit sur un **butoir rouge**. Le mauvais côté mène à l'**impasse**.
- Une **voie de garage dorée** : garde la touche jusqu'à ce qu'elle rejoigne la ligne, sinon le combo casse.
- Un **croisement** (panneau jaune) : les deux côtés presque ensemble.
- **Manette** : la croix et les boutons de gauche à gauche, ceux de droite à droite.

## Précision et points

Les notes sont jugées selon l'écart avec le bon moment : **Parfait** (environ ±45 ms), **Bien** (±90 ms), **OK** (±140 ms), sinon raté.

Les points d'une note augmentent de 1 % par note de combo, jusqu'au double à 100 notes de suite ; une note ratée remet le combo à zéro. À la fin, la précision donne une note : **S** à partir de 95 %, **A** à 90 %, **B** à 80 %, **C** à 70 %, **D** en dessous.

## Chansons et difficulté

L'onglet **Chansons** reprend les 1200 morceaux de Rythme, en quatre difficultés (Facile, Normal, Difficile, Expert). La difficulté de chaque niveau est calculée d'après ses notes (densité, passages chargés), de 1 à 10 étoiles.

## Mes musiques

Dans **Mes musiques**, crée un niveau à partir d'un **fichier audio** importé ou d'une musique de ta bibliothèque **NeoMusic** : le jeu trouve son tempo et ses temps forts et en fait un niveau, à la **difficulté** choisie (1 à 10 étoiles).

## Réglages

- **Volume** de la musique.
- **Son des clics** : le son joué à chaque note touchée, au choix parmi 10 (Doux, Clap, Bois, Grosse caisse, Cristal, Pop, Charleston, Caisse claire, Pluck, Tok) ou aucun. Perdre un combo de 10 ou plus joue un son « combo cassé ».
- **Décalage** (−300 à +300 ms) : il se règle tout seul après chaque partie selon ton retard ou ton avance moyens ; tu peux aussi le changer à la main.

## Données et synchronisation

Tes scores et notes par niveau et tes réglages sont enregistrés par NeoDex, sauvegardés et synchronisés entre tes PC si la synchro est activée.

## Installer

Dans NeoDex : **NeoStore → À découvrir → Aiguillage → Installer**.

Développer un plugin : voir le [SDK NeoDex](https://github.com/NDesumeur/neodex-sdk).
