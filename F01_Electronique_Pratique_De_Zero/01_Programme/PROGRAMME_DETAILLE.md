# Programme détaillé — F01 Électronique pratique de zéro

## Module 1 — Comprendre l’électricité
- atome, charge et courant ;
- tension électrique ;
- courant électrique ;
- résistance comme grandeur électrique ;
- puissance ;
- énergie ;
- courant continu et alternatif ;
- masse, GND et référence électrique.

## Module 2 — Résistances : comprendre, lire et choisir
- rôle d’une résistance ;
- symbole et unité ;
- code couleur ;
- lecture des valeurs ;
- séries normalisées usuelles ;
- tolérance ;
- puissance nominale ;
- échauffement ;
- résistance fixe et potentiomètre ;
- résistances en série et en parallèle ;
- mesure au multimètre ;
- choix pratique d’une résistance.

### TP suggérés
- identifier plusieurs résistances par leur code couleur ;
- vérifier leur valeur au multimètre ;
- comparer valeur théorique, tolérance et mesure réelle ;
- observer l’effet d’un mauvais choix de puissance.

## Module 3 — Loi d’Ohm et puissance
- U = RI ;
- calcul de tension ;
- calcul de courant ;
- calcul de résistance ;
- puissance dissipée ;
- dimensionnement pratique.

## Module 4 — Circuits série et parallèle
- associations série ;
- associations parallèle ;
- partage des tensions ;
- partage des courants ;
- résistance équivalente ;
- comparaison calculs / mesures.

## Module 5 — Lois de Kirchhoff
- loi des nœuds ;
- loi des mailles ;
- analyse de circuits simples.

## Module 6 — Diviseur de tension
- principe ;
- calcul ;
- influence de la charge ;
- limitations ;
- adaptation d’un signal pour ADC.

## Module 7 — Condensateurs et circuits RC
- capacité ;
- charge et décharge ;
- constante de temps RC ;
- filtrage ;
- découplage ;
- condensateurs polarisés ;
- choix pratique.

## Module 8 — Bobines, inductances et circuits RL
- champ magnétique créé par un courant ;
- principe d’une bobine ;
- inductance et unité henry ;
- énergie stockée dans le champ magnétique ;
- opposition aux variations de courant ;
- constante de temps RL ;
- tension induite ;
- comportement en courant continu et en régime variable ;
- résistance série réelle d’une bobine ;
- saturation du noyau ;
- pertes et échauffement ;
- selfs de filtrage ;
- inductances dans les convertisseurs Buck et Boost ;
- lien avec relais, moteurs et transformateurs ;
- précautions lors de la coupure d’une charge inductive.

### TP suggérés
- observer la montée du courant dans un circuit RL ;
- comparer une charge résistive et une charge inductive ;
- observer la surtension à la coupure d’une bobine ;
- montrer l’effet d’une diode de roue libre sur une bobine de relais.

## Module 9 — Diodes et protections
- diode PN ;
- tension directe ;
- diode de redressement ;
- Schottky ;
- Zener ;
- LED ;
- diode de roue libre ;
- protections contre inversions et surtensions simples.

## Module 10 — Redressement et alimentation DC
- transformateur ;
- pont de diodes ;
- condensateur de filtrage ;
- ondulation ;
- régulation ;
- réalisation d’une petite alimentation DC.

## Module 11 — Transistor BJT
- NPN ;
- PNP ;
- base, collecteur, émetteur ;
- amplification ;
- commutation ;
- commande de charge.

## Module 12 — MOSFET
- N-channel ;
- P-channel ;
- gate, drain, source ;
- RDS(on) ;
- MOSFET logic-level ;
- commutation de puissance ;
- causes d’échauffement ;
- commande en 3,3 V et 5 V.

## Module 13 — Relais et optocoupleurs
- relais ;
- contacts NO/NC ;
- bobine ;
- isolation ;
- optocoupleur ;
- isolation galvanique ;
- interface de puissance ;
- transistor de commande ;
- diode de roue libre.

## Module 14 — Amplificateur opérationnel
- AOP idéal ;
- comparateur ;
- ampli inverseur ;
- ampli non-inverseur ;
- buffer ;
- conditionnement de capteur.

## Module 15 — Capteurs et grandeurs électriques
- capteurs analogiques ;
- numériques ;
- résistifs ;
- capacitifs ;
- optiques ;
- température ;
- pression ;
- courant ;
- poids ;
- comprendre la grandeur électrique produite par le capteur.

## Module 16 — Alimentations modernes
- régulateur linéaire ;
- 7805 ;
- AMS1117 ;
- LDO ;
- Buck ;
- Boost ;
- Buck-Boost ;
- rendement ;
- échauffement ;
- choix entre régulation linéaire et conversion à découpage.

## Module 17 — Instruments de mesure
### Multimètre
- VDC ;
- VAC ;
- courant ;
- résistance ;
- test diode ;
- continuité.

### Oscilloscope
- amplitude ;
- fréquence ;
- période ;
- duty cycle ;
- couplage AC/DC ;
- trigger.

### Alimentation de laboratoire
- réglage de tension ;
- limitation de courant.

## Module 18 — Diagnostic électronique
- méthode de raisonnement ;
- vérifier alimentation ;
- masse ;
- polarité ;
- composants ;
- signaux ;
- sorties ;
- recherche méthodique de pannes.

## Projet final — Contrôleur intelligent de température
- capteur ;
- comparateur ou conditionnement ;
- transistor ou MOSFET ;
- ventilateur ;
- relais ;
- LEDs ;
- alimentation ;
- protections.

Le projet doit servir de transition vers les formations Arduino, ATmega328P et STM32.
