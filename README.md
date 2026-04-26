# Page d'information sur la L3 Maths à Nancy
============================================

Cette page contient:
- [Contacts : qui contacter pour quelle demande](#contacts)
- [Semaine de la recherche](#semaine-de-la-recherche)
- [Séminaire du magistère](#seminaire-du-magistere)
- [Emploi du temps](#emploi-du-temps)
- [Calendrier](#calendrier)

## Contacts

- Questions en rapport avec un cours : le responsable de cours directement.
- Responsable L3 : Damien Mégy
- Responsables Magistère : David Dos Santos Ferreira et Gianluca Pacienza
- pour une question administrative (frais de scolarité, certificats, attestation de réussite, diplôme...) : contacter la scolarité : Mme Emmanuel Schafroth fst-scol-miae@univ-lorraine.fr
- secrétariat pédagogique (emploi du temps, changement d'option, justification d'absence, conventions de stage): Élisa Landormy  fst-licence-maths-adm@univ-lorraine.fr 



## Semaine de la recherche

La semaine de la recherche aura lieu du 22 au 26 septembre. Un exposé est prévu le jeudi 25 à 14h et il y aura peut-être d'autres activités liées à cette semaine. Vous devez y assister (ce n'est pas que pour celles et ceux qui veulent faire de la recherche, c'est pour tout le monde).
Ces activités apparaissent dans votre emploi du temps.

## Séminaire du magistère

Les séminaires du magistère sont destinés aux étudiant(e)s de magistère mais ouverts à toute la promotion de L3, MA comme ME, si l'emploi du temps le permet. Pour les L3 hors magistère, c'est facultatif mais nous vous invitons fortement à regarder les programmes et à venir quand vous voulez. Il s'agit d'exposés mathématiques donnés par les enseignants de l'IECL.
Le programme prévisionnel pour l'instant est le suivant : 

- 25/09/2025 : Régine Marchand, "La percolation: un modèle probabiliste pour les matériaux poreux. »
- 02/10/2025 : Nicolas Marque et Samuel Tapie, "Relativité, Bulles de savon, Pavages de Penrose : de la recherche au grand public."
- 06/11/2025 : Anne de Roton, « Ensemble assommants, sans progression… ou comment éviter les solutions (d’une équation linéaire) » 
- 04/12/2025 : Alexandre Afgoustoudis, « La symétrie aujourd’hui »
- 19/01-23/01 : Pause (master class théorie des nombres/probabilités)
- 05/02/2026 : Nicolas Marque : « Le chemin le plus court : mirages, arcs-en-ciel et trous noirs » 
- 05/03/2026 : Julien Bernat, « Introduction aux pavages avec les polyominos »
- 02/04/2026 : Damien Mégy,  « Empilements compacts de sphères en dimension 2 et 3 puis 8 et 24 »
- 30/04/2026 : Victoria Callet Feltz, « Analyse topologique de données musicales, ou comment différencier Bach de Metallica »

Les résumé des exposés sont [ici](magistere/seminaire-magistere-2025-2026.md)

## Emploi du temps

Vous voyez normalement votre emploi du temps sur votre ENT (ent.univ-lorraine.fr, ou bien l'appli UL). Si vous n'avez pas encore d'inscription administrative (urgent!!) vous pouvez néanmoins consulter l'emploi du temps même sans compte, voir les instructions dans le fichier [procedure-consultation-EDT](procedure-consultation-EDT.pdf)


## Calendrier prévisionnel de la L3

Le calendrier de l'année : 
[calendrier2526.pdf](calendrier2526.pdf)

## Pour débuter en LaTeX

Le rapport de stage doit être rendu en LaTeX. Voici un document minmal fonctionnel, compilable avec "pdflatex" qui est le compilateur _legacy_ mais toujours le plus répandu et standard :

```latex
\documentclass{article}
\usepackage[T1]{fontenc} % Toujours nécessaire (contrairement à \usepackage[utf8]{inputenc})
\usepackage{lmodern} % Police 'Latin Modern' vectorielle. Alternative populaire : 'fourier'
\usepackage[a4paper,margin=2.5cm]{geometry}
\usepackage[french]{babel} % Règles typographiques françaises
\usepackage{mathtools,amssymb,amsthm} % mathtools remplace et améliore amsmath
\usepackage{microtype,enumitem,graphicx} % Et autres : mdframed, xcolor, tikz, ...
\usepackage{hyperref} % À charger en dernier de préférence
\begin{document}
Tutoriel recommandé : \url{https://www.overleaf.com/learn/latex/Learn_LaTeX_in_30_minutes}
\end{document}
```


Dans le sous-dossier [ressources-pour-latex](ressources-pour-latex/), vous trouverez des documents pdf pour vous ader à vous familiariser avec LaTeX. (Conseil : si vous disposez d'un ordinateur personnel, installez LaTeX. Overleaf, c'est bien pour partager son travail ou collaborer sur un projet, mais c'est quand même assez lent et pénible pour plein de choses.


## Bibliographie pour la Licence de mathématiques

Une [bibliographie pour la licence et le magistère de mathématiques](magistere/bibliographieL3Magistere.pdf) est disponible.

Elle propose des livres de transition entre la L2 et la L3, des livres ciblés pour l'année de L3 ou de magistère, et des livres pour la transition L3-> M1.

Liste de livres de maths gratuits : https://cain.math.gatech.edu/textbooks/onlinebooks.html (Livres en anglais. [Version archivée](https://web.archive.org/web/20251114185815/https://cain.math.gatech.edu/textbooks/onlinebooks.html))

Il est conseillé de lire des livres au cours de la L3, pas forcément beaucoup mais un peu.


## Récupération de son diplôme

Pour les anciens. Les informations sont dans le fichier [retirer-son-diplome.md](retirer-son-diplome.md)


## STAGES

Le stage est obligatoire pour valider le diplôme de licence.
Dans tous les cas listés ci-dessous, un rapport de stage devra être remis avant mi-mai, sera noté, et comptera dans votre moyenne.

- Si vous êtes magistérien(ne), vous *devez* faire un stage de recherche en laboratoire de recherche : IECL, ou autre laboratoire scientifique comme le Loria (info) ou le laboratoire de physique théorique.
- Sinon, il faut faire un stage mais pas nécessairement mathématique : ça peut être un stage en laboratoire de recherche (maths ou autre), en entreprise (n'importe quel type d'entreprise, non nécessairement scientifique), ou en établissement scolaire, auquel cas la durée est réduite de 3 à deux semaines. Le travail salarié de plus de trois semaines valide également le stage (fiche de paie à l'appui). Pour plus d'informations, me contacter ou contacter Elisa Landormy, qui gérera la signature des conventions de stage.


