# Overlay d'initiation pour OBS v1.0


## Description

![overlay-initiation](https://user-images.githubusercontent.com/91347360/210372163-1003ba8c-8e9d-43dd-a5a5-59018c5908a3.gif)

L'overlay proposé ici est un template volontairement **simplifié et générique**. Il est personnalisable et peut être utilisé dans le cadre d'un stream simple, mais est principalement pensé dans un but de découverte et d'initiation pratique à OBS.

Il vous suffit de télécharger le pack overlay et de l'importer proprement dans OBS Studio (voir instructions ci-dessous), ensuite soyez libres de l'utiliser, de le modifier, de le décortiquer comme bon vous semble.

**Cet overlay sera régulièrement amélioré avec de nouvelles options et de nouvelles techniques.**


## Contenu

Le dossier de l'overlay contient : 
- les **élements graphiques** utilisés (image de fond, cadre, logo...)
- Le fichier **"overlay-initiation.json"** à importer en tant que **"Collection de scènes"** dans OBS Studio et qui contient la structure de l'overlay (scènes, sources...)
- Le dossier **"overlayinitiation720p"** à importer en tant que **"Profil"** dans OBS Studio et qui contient une première base de paramétrages basiques (bitrate, encodage...)

L'overlay est construit sur le principe des **scènes imbriquées** (ou "nested scenes") avec 3 niveaux différents : 

- **Scènes “ASSET”** : Ces scènes ne sont pas destinées à être utilisées directement en live. Elles servent à **"stocker"** certains éléments uniques, comme par exemple la scène "ASSET - Background"
- **Scènes "MIX"** : Ces scènes ne sont pas destinées à être utilisées directement en live. Il s'agit d'un niveau intermédiaire de scènes qui sert à **"composer"** des éléments récurrents, comme par exemple la scène "MIX - Scène d'attente".
- **Scènes "LIVE"** : Ces scènes sont destinées à être utilisées en live et intégrer les derniers éléments. 

Les scènes **"====LIVE===="**, **"=====MIX====="** et **"=====ASSETS====="** restent vides et servent uniquement de "séparateur" entre les scènes.

Pour **personnaliser l'overlay** à votre convenance, vous pouvez ajouter ou modifier l'image de fond, le logo, les textes, la chatroom (avec [Kapchat](https://nightdev.com/kapchat))  dans les scènes correspondantes. Vous pouvez également vous connecter à votre compte Twitch dans les paramètres puis dans **"Stream (Flux)"**.

N'hésitez pas à faire une copie de sauvegarde de l'overlay avant de commencer à modifier les éléments.


## Installation et mise en place de l'overlay
- Telechargez [OBS](https://obsproject.com/fr) si besoin. La version utilisée (28.1.1) est une version *vanilla* (sans scripts ou plugins ajoutés).
- Téléchargez l'overlay via le **bouton vert "Code"** puis sélectionnez **"Download Zip"**.
- Décompressez le dossier sur votre ordinateur
- Lancez OBS
- Dans le menu **"Collection de scènes”**, sélectionnez **“Importer”** puis dans le champ **“Chemin de la collection”**, selectionnez le fichier **overlay-template.json**.
- Pour compléter les fichiers manquants, toujours dans le menu **"Collection de scènes"**, séléctionnez l'option **"Vérifier les fichiers manquants"** puis **"Rechercher dans le dossier"** puis pointez vers le dossier contenant les éléments de l'overlays,
- Dans le menu **"Profil"**, sélectionnez **"Importer"** et pointez le dossier **"overlayinitiation720p"**.


## Aller plus loin

- [Atelier Badgeek - OBS partie 1 : Les bases](https://www.youtube.com/watch?v=zDg4tO1_jhM)
- [Atelier Badgeek - OBS partie 2 : Filtres, plugins et overlays](https://www.youtube.com/watch?v=luTexi3Aefc)


## Auteur
* **Peremptoire** [@peremptoire](https://twitter.com/peremptoire)
