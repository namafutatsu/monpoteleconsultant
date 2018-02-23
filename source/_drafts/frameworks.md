---
title: Frameworks
author: Dave Letech
subtitle: Comme quoi, un framework, c'est un peu comme une cuisine.
---

Ni une ni deux, le voilà qui se ramène, mon pote le consultant. Moi qui pensais
être posé bien tranquille, tout au bout de l'open space, c'est bien raté.

"Dis-moi", qu'il me lance, "comment ça se fait que l'autre troufion de
développeur m'annonce 10 jours de boulot pour ajouter un sale menu déroulant
alors que pas plus tard que la semaine dernière, en 10 minutes il m'avait pondu
une page complète ?"

"Ah", que je lui réponds. "C'est parce que ton menu, là, il n'est pas prévu par
le **framework**."

Je regarde sa mine déconfite. Je sens qu'il y a là un point qu'il n'a pas
entièrement saisi.  Et ça, chez mon pote le consultant, ça signifie qu'il va
falloir lui expliquer un peu plus en détail...

## Pourquoi certains développements sont subitement 10 fois plus complexes ?

Les développeurs ne sont pas des magiciens; ils écrivent du code, suite
d'exécutions interpétées par un ordinateur dans un certain contexte:
- un système d'exploitation, tel Windows ou Linux;
- un navigateur, comme Chrome ou Firefox
- une machine directement, comme une carte à puce ou un robot.

Ce code permettra au logiciel, site web ou robot résultant de présenter le
comportement désiré, généralement suivant une spécification fonctionnelle
(besoin métier) bien précise.

Or écrire ce code est la plupart du temps complexe et comporte de très nombreux
coûts cachés qui sont en général invisibles du point de vue du métier:
- faire un formulaire d'enregistrement requiert de penser à une palanquée
  d'impératifs de sécurité, de systèmes de récupération de mots de passe, de
  jetons sécurisés, ...
- faire un robot qui avance en ligne droite demande des systèmes de
  positionnement, des mathématiques, etc.

Pour ce faire, la plupart du temps le développeur utilise des raccourcis; il
utilise des **bibliothèques**.

### Les bibliothèques Une bibliothèque est un ensemble de code déjà existant,
écrit par des développeurs que l'on ne remerciera jamais assez, et qui répond à
un impératif connu et relativement générique.

Non seulement ce code existe déjà, mais il est en général vérifié, testé,
utilisé dans de nombreux autres logiciels (ou applications, sites Web, ...) et
il est donc assez recommandé de l'utiliser plutôt que de tenter de le réécrire.

Par exemple, il est probable qu'aucun de vos développeurs n'aie jamais écrit de
code qui calcule le tri d'un tableau d'un million d'éléments, sauf cas
particulier; des bibliothèques existent pour cela et il y a fort à parier que si
votre développeur tentait d'en réécrire une, son premier jet serait bourré
d'erreurs.

Bref: les bibliothèques sont utilisées en permanence pour gérer des
fonctionnalités "communes" et ne pas réinventer la roue; le développeur les
intègre dans un logiciel, s'appuie sur leurs fonctionnalités et ajoute du code
d'intégration et de spécialisation pout réaliser les besoins métier.
