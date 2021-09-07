# Projet ligne de commande

Pour les deux prochaines semaines, vous devez remplir les défis de ce document. L'élément le plus important dans ce travail est de réussir à chercher l'information de manière efficace. Je vous laisse beaucoup d'ouverture pour justement parfaire l'apprentissage de la recherche d'information.

## Documentation

Pour vous aider, vous avez accès à:

* Internet
* Le site [learnshell.org](https://learnshell.org)
* Le livre *Learn Enough Command Line to be Dangerous* (disponible sur LÉA, dans la section document du cours)
* Vos collègues et moi, évidemment

## À remettre
Pour chaque défis, me remettre un fichier script contenant les commandes nécessaires. Chaque fichier doit commencer par la ligne suivante: `!#/usr/bin/bash`. Cela permet d'exécuter les commandes présentes dans le fichier lorsqu'il est appelé. Placer les scripts dans un dossier zip puis le remettre sur LÉA.

## Défi 1: le plein de dossier

Reproduire l'arborescence de dossiers suivante:

* A
  * A1
  * A2
  * A3
    * A31
* B
  * B1
  * B2
  * B3
  * B4
  * B5
  * B6
    * B61
    * B62
    * B63
  * B7
  * B8
  * B9
  * B10

Dans les dossier ayant deux chiffres dans le nom, ajouter un fichier README.md, ayant comme titre H1 le nom du dossier le contenant. En dessous du titre, inscrire la date à laquelle le fichier a été créé. Le format pour la date est: AAAA/MM/JJ HH:MM:SS.

Rendre les dossier ayant un nombre pair en lecture seule pour les membres du groupe et complètement invisible pour les autres.

## Défi 2: 
Pour ce défi, vous devez, en moins de 20 lignes de code, générer 150 dossiers ayant comme nom DOSSIER### où ### correspond au numéro de dossier allant de 001 à 150. Vous devez avoir une commande par ligne.

## Défi 3: 
Ce défi se fait sur le Raspberry Pi. Un des problèmes que les rPi ont au Cégep est que la date ne se synchronise pas correctement. Ce défi est de réussir à changer le serveur de temps vers l'adresse suivante: `time.apple.com`, activer le service de temps par Internet (NTP) puis procéder au redémarrage du service de temps.
