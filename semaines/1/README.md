# Semaine 1

## Présentation plan de cours
Le plan de cours est disponible sur LÉA.

## Révision des opérateurs logiques et bases numériques

### Portes logiques
Porte OU (*OR*)
|OU|0|1|
|--|--|--|
|0|0|1|
|1|1|1|

Porte ET (*AND*)
|ET|0|1|
|--|--|--|
|0|0|0|
|1|0|1|

Porte inverseur (*NOT*)
|INV|0|1|
|--|--|--|
||1|0|

Pour plus d'informations sur les portes, voir le [wikilivre](https://fr.wikibooks.org/wiki/Électronique/Les_portes_logiques).

### Bases numériques

Base 2
Chiffres possibles: 0, 1

Base 8
Chiffres possibles: 0, 1, 2, 3, 4, 5, 6, 7

Base 16
Chiffres possibles: 0, 1, 2, 3, 4, 5, 6, 7, 8, 9, A, B, C, D, E, F

Pour revisiter les concepts sur les bases numériques, voici un [article pertinent](https://www.squalenet.net/fr/ti/tutorial_c/a1-bases-numeriques-binaire-decimale-hexadecimale.php5).

## Conception d'un additionneur à partir de portes logiques

À partir de portes logiques, il est possible de construire un additionneur binaire. Cette section se base sur le chapitre 12 du livre CODE, disponible dans la section Document du cours sur LÉA.

Les étapes principales pour la conception de l'additionneur:
* Création d'un additionneur 1 bit à l'aide d'une porte XOR et une porte OR.
* La mise en cascade de deux *half-adder* pour obtenir un *full adder*.
* La mise en cascade de plusieurs *full adder* pour obtenir un additionneur multi-bit.

## Lectures
Dans le livre CODE:
* Chapitre 1 à 11 est de la révision sur les bases numériques, portes logiques et transistors. Peut être feuilleté rapidement.
* Chapitre 12 correspond à la conception d'un additionneur. Important à lire.
* Chapitre 13 est l'ajout de la soustraction. À lire sommairement. Il n'y aura pas de questions en tant que tel sur la soustraction, mais il pourrait y avoir des questions bonus là dessus.

## Questions de validation sur la théorie

1. Quelle est la différence entre un *half* et *full adder* ?
1. Pourquoi, dans un *full adder*, est-il correct d'avoir deux sorties *CO* des *half adder* dans un OU logique ? Que ce passe-t-il d'un point de vue logique si les deux *CO* des *half adder* sont à 1 ?