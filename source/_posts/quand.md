---
title: Quand
date: 2018/2/24
author: Dave Letech
subtitle: Comme quoi développer, c'est comme pondre un roman.
---

Je chattais l'autre jour avec un pote développeur au sujet du "Quand", car
c'est une des questions qui nous revient le plus souvent.

"Quand" auras-tu fini ce projet ? Quand pourra-t-il etre déployé ? Etc etc.

Question terriblement complexe. Lorsqu'on me la pose, je reste un peu interdit
puis je finis par marmonner une date en y croyant à moitié. Allez, je vais
essayer d'expliquer en quoi c'est si difficile.

# Un travail créatif

La réalité, c'est que demander une date pour fournir un développement est par
essence une question terriblement complexe.

**Développer un logiciel est proche, conceptuellement, de l'écriture d'un roman ou
de la peinture d'un tableau.**

On tâtonne, on lit différentes sources d'inspiration, on essaie une version puis
une autre; puis on se fait relire, modifie une bavure ou une formulation ça et
là, parfois on recommence tout lorsqu'on est parti du mauvais pied.

Même les plus expérimentés développeurs peuvent avoir du mal à estimer le temps
nécessaire pour un développement. Ce n'est pas parce qu'on est Zola que l'on va
forcément savoir à l'avance combien de temps va prendre *Germinal* à écrire !

C'est donc un travail créatif et incertain par essence. On est pas rendus avec
ça. Heureusement des méthodes existent, de plus en plus, pour tenter de
délimiter le temps que va prendre le boulot.

# Le découpage en livrables

Une des premières choses est le découpage. Un projet complet est en général bien
trop complexe pour être évalué; une -longue- phase d'analyse préliminaire peut
donc aider à "découper" un projet en N tâches plus compréhensibles et prévisibles.

Autrement dit, si Zola ne peut pas prévoir *Germinal* il peut certainement avoir
une idée de la durée nécessaire pour *J'accuse* !

Attention cependant: découper signifie aussi réunir, après coup... Ca se fait
soit de manière continue, pendant le développement (ce qu'on appelle [Agile])
soit avec un travail d'intégration et de tests pour les éléments développés
séparément.

Dans les deux cas il y aura un un surcoût de temps.


## Ecriture "Agile"
Pour continuer l'analogie, imaginons *Le Comte de Monte-Cristo* livré de manière
[Agile]: Dumas livrerait donc une histoire complète, chaque semaine un peu plus
étoffée. Ça donnerait en gros:

**Le compte de Monte-Cristo, sprint n°1**

*Un marin découvre en prison la cachette d'un grand trésor, et l'utilise pour
obtenir sa revanche sur ceux qui lui ont volé sa vie.*

**Le compte de Monte-Cristo, sprint n°2**

*Dans le port de Marseille, Edmond Dantès, amoureux de la belle Mercedes, part en
voyage à l'île d'Elbe et suite à une infâme machinerie, il se retrouve
incarcéré. Son voisin de cellule, l'abbé Faria lui dévoile alors le secret d'un
fabuleux trésor. [...]*

Difficile pour Dumas, non ?

## Ecriture "avec intégration"

Autre scénario: Dumas utiliserait N nègres, disons venant de différents pays,
qui livreraient chacun sous 6 mois un des chapitres du *Comte* et s'arrangerait
pour en sortir un roman acceptable (ce qui se passe avec les équipes de
développement offshore, NDLR) ; bon courage !

C'est pourtant le quotidien d'un projet: on le découpe en livrables, et l'on
itère en essayant de tenir des objectifs de temps qui sont en général
complètement arbitraires du point de vue du développeur.

# Avoir de l'expérience

En réalité **c'est souvent le marché qui décide de quand un produit doit être
livré**.  Le développeur, lui, ne peut que tenter d'estimer si c'est totalement
Un des meilleurs atouts pour une estimation réussie est l'expérience d'une
équipe: a-t-on déjà fait ce genre de choses auparavant ? S'appuie-t-on sur des
développements passés stables, dans un environnement et sur un domaine maîtrisés
?

Dans certains cas il est donc possible de se ramener à un terrain connu. Ainsi
il est envisageable d'estimer grossièrement le temps que va prendre l'écriture
d'un nouveau SAS ou Chair de Poule, quand on en a déjà écrit dix.

De même, on peut supposer que si un magazine existe depuis des années, les
rédacteurs connaissent les délais nécessaires pour un article, dossier,
voire un hors-série ! **Une équipe qui a longtemps travaillé ensemble sur des
sujets proches sera d'autant plus à même d'estimer les charges futures sur des
projets similaires.**

En inversant cette logique, gare aux inadéquations entre une demande et la
maîtrise d'un sujet par une équipe ! Demandez à un développeur C comment centrer
une image verticalement en CSS, et on a toutes les chances d'obtenir un regard
médusé et un gros "bah j'en sais fichtre rien...". Vous avez demandé à Mozart de
préparer la meilleure recette de cuisine de la Tour d'Argent, vous ?

De la même manière, tout projet qui débute, pour lequel on réunit une équipe,
est soumis à une incertitude très forte quant à ses chances et délais de
réussite. Il faut en tenir compte !

# Et pour finir...

La question du "quand" est difficile, et sa complexité explose avec la taille ou
l'ambition d'un projet. On arrive vite à des estimations infaisables, que l'on
peut au mieux borner: "j'aurai probablement fini dans deux ans", "surement que 3
personnes sur 6 mois peuvent le faire".

**Plus le sujet est restreint, plus l'équipe est expérimentée, plus il est
possible de donner une estimation fiable.**

J'irai même plus loin: plus l'objectif à réaliser est ennuyeux, plus il est
facile.  On pourra toujours dire que ça ne prend qu'une journée d'écrire un
encart sportif dans un quotidien. Mais développer étant en général plus innovant
que de la simple création de contenu, ce genre de cas reste très rare... et pas
forcément intéressant à discuter !

Et tout cela a des conséquences pour toi, mon ami consultant, qui te situes entre le
marteau du client -qui veut une date de livraison- et l'enclume des
développeurs, qui ne sont pas capables d'en fournir une; cela signifie qu'il y
aura toujours du travail (bonne nouvelle, non ?) pour en permanence réajuster
les choix, les possibilités du produit, éduquer le client sur certaines demandes
irréalistes, convaincre les développeurs de ne pas trop en faire et se
forcer à rentrer dans les clous avec inventivité. Passionnant, non ?


[Agile]: https://en.wikipedia.org/wiki/Agile_software_development
