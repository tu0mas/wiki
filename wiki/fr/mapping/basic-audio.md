---
sidebar: auto
prev: false
next: ./advanced-audio.md
translation-done: false
---
# Mise en place de l'audio basique
_Préparez votre audio pour le mapping_

* [Glossaire des termes](/mapping/glossary.md)

Cette page fournit aux nouveaux mappeurs et aux mappeurs expérimentés des recommandations générales pour configurer un nouveau fichier audio avant de commencer à mapper. Consultez le guide de démarrage rapide ci-dessous pour les étapes ** essentielles ** avant de commencer le mapping (et ensuite j'ai pas compris le vs.)

## Démarrage rapide de la configuration audio
::: warning
* Les étapes 1-5 **DOIVENT** êtres complétées avant de débuter le mapping ou votre audio sera désynchronisé et pourra présenter un [*hot start*](./glossary.html#h).

* L'utilisation de sites internet vous permettant de convertir votre audio en `.ogg` peut rendre votre fichier audio invalide et ne sera pas lisible en jeu ! Le traitement et l'exportation depuis [Audacity] (https://www.audacityteam.org/) est le moyen le plus simple pour garantir que votre fichier audio fonctionne comme prévu.
:::
1. Téléchargez et installez [Audacity](https://www.audacityteam.org/)
	* Facultatif : Installez [ffmpeg for windows](https://manual.audacityteam.org/man/installing_ffmpeg_for_windows.html) pour pouvoir ouvrir des types de fichiers additionnels tels que `.aac` ou `.m4a` provenant d'iTunes.
2. [Trouvez le BPM](./basic-audio.html#finding-the-bpm) et l'offset de votre chanson.
3. [Ajoutez un métronome](./basic-audio.html#add-a-click-track) pour vérifier votre BPM et [synchroniser votre audio](./basic-audio.html#sync-the-song-to-the-beat)
4. Regardez si vous avez [suffisamment d'intro/silence](./basic-audio.html#plan-your-first-note) au début de votre chanson [ajoutez du silence](./basic-audio.html#add-silence)
5. Retirez le métronome puis [Exportez votre chanson](./basic-audio.html#exporting) au format `.ogg`.

**A faire avant l'upload :**  
6. [Vérifiez le volume](./basic-audio.html#check-song-volume) et rendez-le plus [fort](./basic-audio.html#making-your-song-louder) ou plus [faible](./basic-audio.html#making-your-song-softer) si besoin.

## Choisir une chanson pour les nouveaux mappeurs
Ci-dessous se trouvent les recommandations, **pas** les pré-requis, pour vous aider dans votre mapping. Si vous souhaitez créer une map de 17 minutes de "In A Gadda Da Vida" en tant que première map alors allez-y, mais sachez que vous allez faire face à **beaucoup** de difficultés.

* Choisissez une chanson possédant un rythme simple sur lequel vous pouvez mapper. Certains styles de musiques s'y prêtent mieux que d'autres.
* Choisissez une chanson ayant un tempo consistant (par exemple, une musique de style électronique). Les chansons à tempo variable peuvent être très difficiles à mapper.
* Choisissez une chanson courte (moins de 3 minutes est idéal). Mapper une chanson de 10 minutes épique dès le début peut engendrer de la frustration et/ou causer un burn out.
* Enfin, choisissez une chanson que vous êtes prêt à écouter continuellement, encore et encore. Mais évitez de mapper votre chanson favorite lors de vos toutes premières maps, gardez-la lorsque vous serez plus expérimenté.

## Qualité audio
Avant d'attaquer votre mapping, assurez-vous de disposer d'un fichier audio de haute qualité pour votre chanson. Beaucoup de maps possèdent un audio très mauvais, souvent extrait de YouTube ou de fichiers audio de basse qualité. Beat Saber est après tout un jeu musical, avoir un audio de qualité est donc essentiel pour une bonne expérience de jeu.

Suivez ces conseils lorsque vous travaillez sur vos maps :
* Utilisez la meilleure qualité audio que vous puissiez trouver, comme par exemple des fichiers **FLAC ou WAV(E)** (format sans perte).
* Un bon substiut est un fichier **MP3 ou AAC** avec un débit audio élevé (+200 kbps).
* Utilisez un rip YouTube **uniquement** en dernier recours. Le débit audio est faible et le volume rarement correct. Dans ce cas, de l'édition audio peut être nécessaire (voir [Editing with Audacity](/mapping/basic-audio.html#editing-with-audacity)).

> Les sites proposant la vente de chansons/albums comme le [Bandcamp](https://bandcamp.com/) d'un artiste vous propose souvent la plus haute qualité disponible. Si l'ariste n'a pas de profil Bandcamp, des alternatives existent comme Google Play Music, Amazon Music et iTunes.

En achetant et en utilisant un fichier audio de haute qualité, non seulement vous soutenez l'artiste, mais vous évitez By purchasing and using a high quality audio file, not only are you supporting your artist, mais vous vous épargnez beaucoup de maux de tête lors du mapping. Regardez la différence de qualité pour la même chanson, au même rythme.

| Qualité OGG | Rip YouTube | MP3| WAV | FLAC |
| :----: | :----: | :----: | :----: | :---: |
| 1 | ![YouTube Rip 1](./images/ytrip1.jpg) | ![MP3 1](./images/mp31.jpg) | ![WAV 1](./images/wav1.jpg) | ![Flac 1](./images/flac1.jpg) |
| 5 | ![YouTube Rip 5](./images/ytrip5.jpg) | ![MP3 5](./images/mp35.jpg) | ![WAV 5](./images/wav5.jpg) | ![Flac 5](./images/flac5.jpg) |
| 10 | ![YouTube Rip 10](./images/ytrip10.jpg) | ![MP3 10](./images/mp310.jpg) | ![WAV 10](./images/wav10.jpg) | ![Flac 10](./images/flac10.jpg) |
