# Overlay d'initiation pour OBS v1.0


## Description

L'overlay proposé ici est un template volontairement simplifié et générique. Il est personnalisable et peut être utilisé dans le cadre d'un stream simple, mais est principalement pensé dans un but de découverte et d'initiation pratique à OBS.

Il vous suffit de télécharger le pack overlay et de l'importer proprement dans OBS Studio (voir instructions ci-dessous), ensuite soyez libres de l'utiliser, de le modifier, de le détourner comme bon vous semble.


## Contenu

Le dossier de l'overlay contient : 
- les élements graphiques utilisés (image de fond, cadre, logo...)
- Le fichier "overlay-initiation.json" à importer en tant que "Collection de scènes" dans OBS Studio et qui contient la structure de l'overlay (scènes, sources...)
- Le dossier "overlay-initiation-720p" à importer en tant que "Profil" dans OBS Studio et qui contient les paramètres de streaming et d'enregistrement (bitrate, encodage...)

L'overlay est construit sur le principe des scènes imbriquées (ou "nested scenes") avec 3 niveaux différents : 

- Scènes “ASSET” : Ces scènes ne sont pas destinées à être utilisées directement en live. Elles servent à "stocker" certains éléments uniques, comme par exemple la scène "ASSET - Background"
- Scènes "MIX" : Ces scènes ne sont pas destinées à être utilisées directement en live. Il s'agit d'un niveau intermédiaire de scènes qui sert à "composer" des éléments récurrents, comme par exemple la scène "MIX - Scène d'attente".
- Scènes "LIVE" : Ces scènes sont destinées à être utilisées en live. 

Pour personnaliser l'overlay à votre convenance, vous pouvez ajouter ou modifier l'image de fond, le logo, les textes, la chatroom dans les scènes correspondantes. Vous pouvez également vous connecter à votre compte Twitch dans les paramètres puis dans "Stream (Flux)".

N'hésitez pas à faire une copie de sauvegarde de l'overlay avant de commencer à modifier les éléments.


### Installation et mise en place de l'overlay
- Telechargez OBS si besoin. La version utilisée (28.1.1) est une version vanilla (sans scripts ou plugins ajoutés).
- Téléchargez l'overlay via le bouton vert "Code" puis sélectionnez "Download Zip".
- Décompresser le dossier sur votre ordinateur
- Lancez OBS
- Dans le menu "Collection de scènes”, sélectionnez “Importer” puis dans le champ “Chemin de la collection”, selectionnez le fichier overlay-template.json. 
- Pour compléter les fichiers manquants, toujours dans le menu "Collection de scènes", séléctionnez l'option "Vérifier les fichiers manquants" puis "Rechercher dans le dossier" puis pointez vers le dossier contenant les éléments de l'overlays,
- Dans le menu "Profil", sélectionnez "Importer" et pointez sur le dossier "overlay-initiation-720p".


## Fabriqué avec

Entrez les programmes/logiciels/ressources que vous avez utilisé pour développer votre projet

_exemples :_
* [Materialize.css](http://materializecss.com) - Framework CSS (front-end)
* [Atom](https://atom.io/) - Editeur de textes

## Contributing

Si vous souhaitez contribuer ou que vous avez des retours ou des demandes à faire, contactez moi 

## Versions
Listez les versions ici 
_exemple :_
**Dernière version stable :** 5.0
**Dernière version :** 5.1
Liste des versions : [Cliquer pour afficher](https://github.com/your/project-name/tags)
_(pour le lien mettez simplement l'URL de votre projets suivi de ``/tags``)_

## Auteur
* **Peremptoire** [@peremptoire](https://twitter.com/peremptoire)
