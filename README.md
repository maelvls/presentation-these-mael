# Notes pour ma présentation

Ma soutenance a eu lieu le lundi 8 avril 2019 à 10h, salle des thèses
à l'IRIT.

## Éditer les `.pdf` avec Ipe

La plupart des `.pdf` avec des schémas sont ouvrables en utilisant
Ipe <http://ipe.otfried.org/>. Ipe est une sorte de Inkscape beaucoup
plus simple et incluant l'écriture Latex. Ipe est toujours maintenu en 2019
et est (en plus) open-source et dispo sous macOS, Linux et Windows.
Ce qui est assez cool, c'est que Ipe permet d'inclure dans le PDF produit
le code source qui a permis de créer ce PDF, ce qui permet de se self-contain.

Il faut d'abord installer Ipe ; ensuite, clic droit sur un PDF et 'ouvrir
avec Ipe'.

Avec shift+cmd+P, ça ouvre le bout de code Latex qui est inséré en préembule
et qui contient les choses comme les \usepackage{} et les macros.

Pourquoi ne pas avoir utilisé un autre outil ?
- Inkscape est bien mais lourd/pas agréable sous macOS et galère de gérer
  Latex.
- Powerpoint pour faire des schémas et les exporter en PDF pour les intégrer
  dans la présentation : bof bof car closed-source et souvent pas pérenne.
- TikZ : cool car c'est du pur latex donc pas de dépendances externes. Mais
  courbe d'apprentissage trop élevée.

