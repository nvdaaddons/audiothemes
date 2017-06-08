# Audio Themes #

*   Auteurs : Musharraf Omer et autres
*   Télécharger [version stable][1]
*   Télécharger [version de développement][2]

Ce module complémentaire crée un affichage audio virtuel qui joue des sons
quand il est sur le focus ou la navigation par objet (tels que des boutons,
liens, etc...) l’audio se jouera dans un endroit qui correspond à
l'emplacement de l'objet dans l'affichage visuel.

Le module complémentaire permet également d’activer, installer, supprimer,
modifier, créer et de distribuer des paquets de thème audio.

## Utilisation

Ce module complémentaire vous permet d'effectuer trois tâches distinctes, y
compris la gestion de vos thèmes audio installés, l'édition du thème audio
actuellement actif et la création d'un nouveau thème audio.

Vous pouvez accéder à ces fonctions depuis le menu du module complémentaire
qui se trouve dans le menu principal de NVDA.

### Gérer Vos Thèmes Audio

- Le dialogue "Gérer les Thèmes Audio" vous permet d'activer ou de
  désactiver les thèmes audio, en plus d’installer ou de retirer des thèmes
  audio.
- Dans ce dialogue, il y a quelques options supplémentaires, y compris :
 - Jouer des sons en mode 3D : Lorsque vous décochez cette case le module complémentaire va jouer les sons en mode mono (toujours dans le centre de l'affichage audio) indépendamment de l'emplacement de l'objet.
 - Annoncer rôle tels que bouton, zone d'édition, lien etc. : lorsque vous décochez cette case NVDA commencera en annonçant le rôle lors de la focalisation des objets plutôt que d'ignorer  ceux-ci (qui est le comportement par défaut lors de l'installation  de ce module complémentaire).
 - Utiliser le Volume du Synthétiseur : Vérifié que cette case définira le son du lecteur du module complémentaire pour utiliser le son de la voix active, ce qui rend toute sortie audible le même que le volume de la voix à chaque fois que vous changez ce volume.
 - Potentiomètre du Volume  du Thème Audio : Alternativement, vous pouvez régler le volume pour ce module complémentaire en utilisant ce potentiomètre. Positionnement de celui-ci à 0 va couper tous les sons, et 100 est le volume maximum.

### Édition Du Thème Audio Actif :

- Lorsque vous cliquez sur l'option "Modifier le thème audio actif", un
  dialogue s’ouvre avec une liste contenant tous les sons contenus dans le
  thème actuellement actif. Depuis ce dialogue, vous pouvez :
- Changement Sélectionné : En sélectionnant un son dans la liste et en
  cliquant sur ce bouton, il va ouvrir un dialogue standard ouvrir fichier,
  sélectionnez un fichier audio ogg ou wave depuis votre système de fichiers
  pour remplacer le son sélectionné et cliquez sur OK pour terminer le
  processus.
- Supprimer Sélectionné : Cela permettra de supprimer le son sélectionné
  depuis le thème, cliquez sur "Oui" pour confirmer le processus de
  suppression et le son sélectionné sera supprimé.
- Ajouter Nouveau Son : Lorsque vous cliquez sur ce bouton un nouveau dialogue s'affichera. Depuis la première zone de liste déroulante dans le dialogue récemment ouvert, sélectionnez le type d'objet auquel vous souhaitez assigner le son, par exemple (bouton, lien, onglet, menu et ainsi de suite), puis cliquez sur le bouton "Accéder à un fichier audio" pour sélectionner le son que vous souhaitez assigner au type d'objet sélectionné précédemment. Facultativement, vous pouvez cliquer sur le bouton Aperçu pour écouter le son, et enfin en cliquant sur le bouton OK s'appliquera les modifications et va être assigner le son sélectionné à l’objet sélectionné.
- Fermer : Quittera le dialogue sans exécuter d'action.

### Création d'Un Nouveau Thème Audio

- Si vous avez une bonne compétence dans la production de son vous pouvez
les appliquer ici et créer un thème audio de votre propre   choix, plutôt
que d'éditer un existant. Pour ce faire, vous pouvez suivre ces étapes.  -
Récupérer vos fichiers audio en un seul endroit, , ils doivent être au
format ogg ou wave, et renommez-les quelle qu'en soit votre manière de le
faire. Par exemple lorsque Je créais le thème audio par défaut pour ce
module complémentaire, J’ai regroupé les sons selon la relation des modèles,
par exemple, la zone de liste déroulante, le bouton de liste déroulante, et
le bouton partagé peuvent avoir le même son, alors que la Case à cocher, Le
bouton bascule, et cocher l'élément du menu peuvent avoir le même son.  -
Depuis le menu du module complémentaire cliquez sur "Créer un nouveau thème
audio" - Un dialogue s'ouvrira vous demandant des informations sur votre
nouveau thème audio, y compris : *	Nom du Thème : Le nom de votre thème qui
sera affiché dans le gestionnaire de thèmes audio. Ceci doit être un nom de
dossier valide de Windows.  *	Votre Nom : Entrez votre vrai nom ou un
surnom.  *	Description du thème : Une brève description de votre thème
audio.  - Cliquez sur OK pour passer à l'étape suivante.  - Dans la
prochaine étape un dialogue similaire au "Éditeur de Thèmes  Audio" sera
affichée, et depuis eux le processus est le même que le  Processus de
modification de thème, voir aussi la section "Édition Du Thème Audio Actif".

## Copyright :

Copyright (c) 2014-2016 Musharraf Omer et Autres

Bien que ce module complémentaire a commencé comme un projet indépendant, il
a évolué pour être une version améliorée du module complémentaire "Unspoken"
par Austin Hicks et Bryan Smart. La majorité du développement de ce module
complémentaire est entré en créant les outils pour gérer, modifier et créer
des paquets de thème audio. Donc un grand Merci à eux pour créer un
merveilleux module complémentaire, et faire celui-ci disponible pour nous
afin de construire par-dessus de leur travail.

## Une Note sur les fichiers audio Tiers partie :

Le paquet du thème audio **Par défaut** dans ce module complémentaire
utilise des sons provenant de plusieurs sources, voici un détail pour eux :
- Unspoken 3D Audio : Un module complémentaire pour NVDA - TWBlue : Un
client  twitter gratuite et à source ouverte - Mushy TalkBack : Une
alternative talkback avec des meilleurs sons.

## Licence
Publié sous la GNU GPL (General Public License). Consultez le fichier
**copying** pour plus de détails.

[[!tag dev stable]]

[1]: https://addons.nvda-project.org/files/get.php?file=ath

[2]: https://addons.nvda-project.org/files/get.php?file=ath-dev
