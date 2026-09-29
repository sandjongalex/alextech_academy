# Module 1 — Comprendre l'électricité

## 1. Pourquoi commencer par les grandeurs électriques ?

Avant de manipuler résistances, condensateurs, diodes, transistors ou microcontrôleurs, il faut comprendre ce que l'on mesure réellement dans un circuit.

Les grandeurs fondamentales utilisées dans ce module sont :

- la charge électrique ;
- la tension ;
- le courant ;
- la résistance ;
- la puissance ;
- l'énergie.

## 2. Charge électrique

La matière contient des particules chargées. En électronique, le déplacement organisé de charges électriques est à l'origine du courant électrique.

Unité de charge : coulomb, symbole C.

## 3. Courant électrique

Le courant électrique représente un déplacement de charges dans un conducteur.

Symbole : I.

Unité : ampère, symbole A.

Sous-unités courantes :

- 1 mA = 0,001 A ;
- 1 µA = 0,000001 A.

Idée pratique : le courant se mesure en insérant l'appareil de mesure dans le trajet du courant.

## 4. Tension électrique

La tension représente une différence de potentiel entre deux points.

Symbole : U ou V selon le contexte.

Unité : volt, symbole V.

Une tension n'existe pas seule : elle est toujours mesurée entre deux points de référence.

Exemples :

- pile : environ 1,5 V ;
- port USB : souvent 5 V ;
- logique numérique : souvent 3,3 V ou 5 V.

## 5. Introduction à la résistance

La résistance électrique exprime l'opposition au passage du courant.

Symbole : R.

Unité : ohm, symbole Ω.

Ce module introduit seulement la notion. Le choix, le code couleur, la tolérance et la puissance des résistances seront étudiés dans le Module 2.

## 6. Puissance électrique

La puissance représente la vitesse à laquelle un dispositif consomme, fournit ou dissipe de l'énergie.

Symbole : P.

Unité : watt, symbole W.

Relation fondamentale :

P = U × I

Exemple :

Un appareil alimenté sous 5 V consommant 0,2 A utilise une puissance de 1 W.

## 7. Énergie électrique

L'énergie correspond à une puissance utilisée pendant une durée.

Relation :

E = P × t

Selon le contexte, on utilise le joule ou le wattheure.

## 8. Courant continu et courant alternatif

### Courant continu — DC

La polarité reste globalement fixe.

Exemples : pile, batterie, alimentation continue.

### Courant alternatif — AC

La tension et le courant varient périodiquement et changent de sens.

Exemple courant : réseau électrique domestique.

## 9. Masse, GND et référence électrique

Le GND est une référence choisie dans un circuit. Il ne signifie pas forcément « zéro volt absolu » dans tous les systèmes.

Une tension est toujours mesurée relativement à une référence.

Cette notion est essentielle pour comprendre :

- les alimentations ;
- les capteurs ;
- les microcontrôleurs ;
- les communications entre cartes.

## 10. Préfixes et ordres de grandeur

Préfixes utiles :

- kilo : k = 10³ ;
- milli : m = 10⁻³ ;
- micro : µ = 10⁻⁶ ;
- nano : n = 10⁻⁹.

Exemples :

- 1 kΩ = 1000 Ω ;
- 10 mA = 0,01 A ;
- 100 µA = 0,0001 A.

## 11. Première approche du multimètre

Le multimètre permet notamment de mesurer :

- tension continue ;
- tension alternative ;
- courant ;
- résistance ;
- continuité ;
- parfois diodes, capacité, fréquence et température selon le modèle.

### Règle essentielle

Une tension se mesure en parallèle.

Un courant se mesure en série.

Une résistance se mesure hors tension.

## 12. Erreurs à éviter

- mesurer une résistance sur un circuit encore alimenté ;
- brancher le multimètre configuré en courant directement aux bornes d'une source ;
- utiliser une mauvaise borne du multimètre ;
- oublier la polarité en courant continu ;
- confondre masse, neutre et terre ;
- supposer que deux GND différents sont forcément au même potentiel.

## 13. Résumé du module

À retenir :

- la tension est une différence de potentiel ;
- le courant est un déplacement de charges ;
- la résistance s'oppose au passage du courant ;
- la puissance relie tension et courant ;
- l'énergie dépend de la puissance et du temps ;
- le GND est une référence ;
- DC et AC ne se comportent pas de la même manière ;
- le multimètre doit être configuré différemment selon la grandeur mesurée.