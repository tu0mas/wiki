---
sidebar: auto
prev: false
next: ./intermediate-mapping.md
translation-done: false
---
# Les bases du mapping
_Un résumé rapide des bases du mapping_

* [Glossary of Terms](/mapping/glossary.md)

## Prêt à mapper ?
**Avez-vous…**
1. [x] [Téléchargé Audacity](https://www.audacityteam.org/) et choisi un [éditeur de map](/mapping#map-editing-resources)?
2. [x] [Préparé votre fichier audio](/mapping/basic-audio.html) pour valider le bpm et être sur que vous avez une bonne intro/outro ?
3. [x] [Exporté](/mapping/basic-audio.html#exporting) votre fichier audio au format OGG ?

::: tip Tout est prêt ?
Super ! Vous êtes prêt à plonger dans votre éditeur préféré et à commencer à mapper ! Si non, cliquez sur les liens au dessus pour plus d'informations.
:::

## Les points essentiels.
Avant de commencer le mapping, vous devez apprendre les bases.
### Les fichiers de maps
Quelque soit l'éditeur choisi pour vos maps, elles ont toutes besoin de :

* **Fichier audio :** Au format OGG, le fichier audio est nécessaire avant même de pouvoir mapper. Nommez-le `song.ogg`
* **Pochette d'album :** JPG ou PNG, elle doit être parfaitement carrée et 512 pixels pour chaque côté est recommandé. Cet élément est nécessaire avant de pouvoir sortir votre map. Nommez-la `cover.jpg` ou `cover.png`
* **Fichier info :** Contient toutes les métadonnées de votre map. Le fichier info s'applique à TOUTES les difficultés (ex : nom, artiste, mapper, nom du fichier, pochette, etc.). Ce fichier est automatiquement crée par l'éditeur.
* **Fichiers de difficultés :** Une fichier par difficulté dans votre map. Ce fichier s'applique à une seule difficulté (ex : placement des notes, placement de l'éclairage, NJS, etc.). Ces fichiers sont automatiquement crées par l'éditeur.

Certains éditeurs créent automatiquement un dossier `Autosaves` où vous pouvez récupérer des copies plus anciennes de votre travail si nécessaire. Lorsque vous êtes prêt à préparer votre chanson pour l'upload, vous devez avoir au minimum quatre fichiers.

Lorsque vous êtes prêt à préparer votre chanson pour l'upload, vous devez avoir au minimum quatre fichiers.

::: warning
Les caractères spéciaux comprises dans les langues telles que, le Japonais (日本語/にほんご), le Chinois (汉语/漢語), l'Arabe (اَلْعَرَبِيَّةُ‎), et les caractères accentués (Ä/é/ó) ne sont pas entièrement supportés par Beatsaver. Utiliser ces caractères dans les métadonnées ou les bookmark (traduire?) peut causer des problèmes.
:::

### Types de blocs

| Blocs directionnels | Blocs point | Bombes | Murs |
| :----: | :----: | :----: | :----: |
| ![Directional Block](./images/arrow-block.png) | ![Dot Block](./images/dot-block.png) | ![Bomb](./images/bomb.png) | ![Wall](./images/wall.png) |
| Doit être coupé dans le <br />sens de la flèche | Peut être coupé dans n'importe quel sens | Cause des dégats lorsque frappé <br />mais sûr pour les joueurs | Blesse les joueurs mais peut<br />être traversé par les sabres |

**Au sujet des murs :**
* Les murs standards peuvent être affichés par tous les casques VR de par leur compatibilité. New mappers should stick with these until they’re a bit more experienced.
* Il existe plusieurs types de murs “hack” ne nécessitant pas le plugin Mapping Extensions : les "fast walls" (passent très rapidement), "hyper walls" (passent TRÈS rapidement), et les "fake walls" (ressemblent à des murs normaux mais ne causent aucun dégâts). 
* Malgré le fait que ces types de murs soient supportés sur certains éditeurs, ils exploitent la mécanique du jeu de base et sont considérés unrankable.
* Plus d'informations sur les murs sans Mapping Exntensions dans [Intermediate Mapping](/mapping/intermediate-mapping.md) et sur les autres types de murs dans [Extended Mapping](/mapping/extended-mapping.md)

**Au sujet des bombes :**
* Bomb hitboxes are smaller than block hitboxes, smaller even than the bomb model itself
* Bombs are hard to see when there are no lighting events active. Make sure your map isn’t dark when bombs are coming up. See [Basic Lighting](/mapping/basic-lighting.html) for more tips.
* Bombs can still be hit once they have passed the player.
