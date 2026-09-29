# Vidéo 07 — Courant continu et courant alternatif

## Position dans le module
Cette vidéo arrive après la puissance et l’énergie. Elle introduit les deux grandes formes de tension/courant que l’apprenant rencontrera ensuite dans presque toute la formation : **DC** et **AC**.

## Durée cible
**8 à 10 minutes**.

## Objectifs pédagogiques
À la fin de cette vidéo, l’apprenant doit pouvoir :
- distinguer courant/tension continus et alternatifs ;
- reconnaître visuellement une tension DC et une tension AC idéalisée ;
- donner des exemples de sources DC et AC ;
- comprendre que AC ne signifie pas simplement « tension élevée » ;
- savoir qu’un multimètre ne se règle pas de la même façon pour mesurer DC et AC ;
- retenir qu’un débutant ne manipule pas directement le secteur.

---

# Script de tournage

## 0:00 – 0:35 — Hook

### Narration
« Une pile de 9 volts et une prise secteur fournissent toutes les deux de l’énergie électrique. Pourtant, ce qu’elles délivrent n’évolue pas de la même façon dans le temps.

La pile fournit une tension que l’on considère continue. La prise secteur fournit une tension alternative.

Dans cette vidéo, nous allons voir simplement ce que signifient DC et AC, comment les reconnaître et pourquoi cette différence est fondamentale en électronique. »

### Visuel
Écran partagé :
- pile 9 V + ligne horizontale ;
- symbole secteur + sinusoïde.

Texte :
**DC = continu**
**AC = alternatif**

---

## 0:35 – 2:00 — 1. Comprendre le DC

### Narration
« Commençons par DC.

DC vient de l’anglais *Direct Current*. En français, on parle de courant continu.

Dans le cas idéal, une source DC maintient la même polarité : une borne reste positive par rapport à l’autre, qui reste négative.

Prenons une pile. Si je mesure sa tension correctement, je peux lire environ 1,5 V, 9 V ou une autre valeur selon la pile. La polarité ne s’inverse pas constamment toute seule.

Sur un graphique tension en fonction du temps, une tension DC idéale peut être représentée par une ligne horizontale. »

### Visuel
Graphique :
- axe vertical : tension ;
- axe horizontal : temps ;
- ligne horizontale au-dessus de 0 V.

Ajouter :
**Exemples DC : pile, batterie, USB, alimentation de laboratoire.**

### Précision pédagogique
« Dans la réalité, une alimentation DC peut contenir un peu d’ondulation ou de bruit. Mais à ce niveau, retiens surtout que sa polarité reste globalement la même. »

---

## 2:00 – 3:30 — 2. Comprendre le AC

### Narration
« Passons maintenant au courant alternatif, ou AC pour *Alternating Current*.

Ici, la tension varie avec le temps et peut changer de polarité.

Dans un signal sinusoïdal idéal, la tension est d’abord positive, revient à zéro, devient négative, revient à zéro, puis recommence périodiquement.

C’est pour cela que l’on parle d’alternatif : la polarité alterne. »

### Visuel
Animation d’une sinusoïde avec repères :
- positif ;
- zéro ;
- négatif ;
- zéro.

### Narration complémentaire
« Dans un conducteur alimenté par une source AC, le sens conventionnel du courant peut lui aussi s’inverser périodiquement. »

---

## 3:30 – 4:25 — 3. AC ne signifie pas “haute tension”

### Narration
« Une erreur fréquente consiste à croire que DC signifie basse tension et AC signifie haute tension.

C’est faux.

On peut avoir un signal alternatif de seulement quelques volts dans un circuit électronique. Et on peut aussi avoir des tensions continues très élevées dans certaines applications.

DC et AC décrivent avant tout la façon dont la tension ou le courant évoluent avec le temps, pas simplement leur valeur. »

### Visuel
Deux encadrés :
- `5 V AC` → possible ;
- `300 V DC` → possible.

Texte :
**AC/DC = forme dans le temps, pas niveau de tension.**

---

## 4:25 – 5:35 — 4. Exemples du quotidien

### Narration
« Regardons quelques exemples concrets.

Une pile AA : DC.
Une batterie de voiture : DC.
La sortie USB d’un chargeur : DC.
Une alimentation de laboratoire réglée à 12 V : DC.

Le réseau électrique domestique, lui, est alternatif.

Mais attention : entre la prise secteur et ton téléphone, il y a un chargeur. Ce chargeur transforme et convertit l’énergie pour fournir au téléphone une tension continue adaptée. »

### Visuel
Chaîne :
**Secteur AC → chargeur → DC basse tension → téléphone**

### Message clé
« Une grande partie de l’électronique fonctionne en DC, même lorsque l’énergie provient initialement du réseau AC. »

---

## 5:35 – 6:40 — 5. Démonstration sûre

### Matériel
- pile ou alimentation basse tension DC ;
- multimètre ;
- générateur de fonctions si disponible, ou animation/simulation d’un signal AC basse tension.

### Narration
« Je vais d’abord mesurer une pile.

Je règle le multimètre sur tension continue, souvent indiquée par un V accompagné d’un trait continu.

Je place les pointes aux bornes de la pile. On obtient une valeur stable proche de la tension nominale.

Pour illustrer l’alternatif, je n’utilise pas la prise secteur. Je préfère un générateur de fonctions, une source AC basse tension isolée ou simplement une visualisation logicielle.

L’objectif ici est de comprendre la forme du signal sans prendre de risque inutile. »

### Visuel
Gros plan sur les deux symboles usuels du multimètre :
- V DC ;
- V AC.

### Consigne de sécurité
**Ne jamais demander à un débutant d’insérer des pointes de mesure dans une prise secteur pour “voir combien il y a”.**

---

## 6:40 – 7:35 — 6. Fréquence : première introduction

### Narration
« Un signal alternatif périodique se répète.

Le nombre de cycles effectués en une seconde s’appelle la fréquence. Son unité est le hertz, symbole Hz.

Si un signal réalise 50 cycles en une seconde, sa fréquence est de 50 Hz.

Nous reviendrons plus en détail sur période, fréquence et observation à l’oscilloscope plus tard dans la formation. Pour l’instant, retiens seulement qu’un signal AC peut être périodique et caractérisé par une fréquence. »

### Visuel
Une sinusoïde avec un cycle encadré.

Texte :
**Fréquence = nombre de cycles par seconde**
**Unité : Hz**

---

## 7:35 – 8:20 — 7. Erreurs fréquentes

### Erreur 1
**« AC = toujours dangereux, DC = toujours sans danger. »**

Correction :
« Le danger électrique dépend notamment de la tension, du courant possible, du chemin dans le corps, de la durée de contact et des conditions. DC n’est pas automatiquement sans danger. »

### Erreur 2
**« Le courant continu est parfaitement constant. »**

Correction :
« Une source est dite DC lorsque sa polarité reste globalement constante. Sa valeur peut néanmoins varier ou contenir du bruit. »

### Erreur 3
**Utiliser le mauvais mode du multimètre.**

Correction :
« Avant une mesure, il faut identifier si l’on cherche une tension continue ou alternative et sélectionner le bon mode. »

---

## 8:20 – 8:50 — Question de validation

### À l’écran
**Classe ces quatre sources : DC ou AC ?**
1. pile 9 V ;
2. sortie USB 5 V ;
3. réseau secteur ;
4. batterie 12 V.

### Réponse
1. DC ;
2. DC ;
3. AC ;
4. DC.

---

## 8:50 – 9:30 — Résumé

### Narration
« Retenons l’essentiel.

Une tension DC conserve globalement la même polarité.

Une tension AC varie dans le temps et peut changer de polarité.

AC ne veut pas dire automatiquement haute tension, et DC ne veut pas dire automatiquement basse tension.

Sur un multimètre, on distingue les modes de mesure DC et AC.

Et pour apprendre, nous privilégions toujours des sources basse tension sûres plutôt que le secteur. »

### Visuel final
Tableau :

| DC | AC |
|---|---|
| polarité globalement constante | polarité pouvant alterner |
| pile, batterie, USB | réseau secteur, signaux alternatifs |
| ligne quasi constante | signal variable / sinusoïdal typique |

---

## 9:30 – 9:50 — Transition

### Narration
« Maintenant, une question devient essentielle : quand on dit qu’un point est à 5 volts, 12 volts ou moins 3 volts… par rapport à quoi ?

Dans la prochaine vidéo, nous allons comprendre la masse, le GND et la notion de référence électrique. »

---

# Visuels à produire

1. Comparaison pile / secteur.
2. Graphique DC idéal.
3. Sinusoïde AC animée.
4. Animation de changement de polarité.
5. Schéma `Secteur AC → chargeur → DC → téléphone`.
6. Symboles VDC / VAC du multimètre.
7. Illustration d’un cycle et de la fréquence.
8. Tableau final DC vs AC.

---

# Matériel pour le tournage

- multimètre numérique ;
- pile 1,5 V ou 9 V ;
- alimentation de laboratoire basse tension ;
- éventuellement générateur de fonctions ou source AC basse tension isolée ;
- ordinateur/tablette pour afficher la simulation AC.

---

# Extrait TikTok / Short dérivé

## Hook
« AC et DC, ce n’est pas “haute tension contre basse tension”. »

## Corps
« DC décrit une tension dont la polarité reste globalement la même. AC décrit une tension qui varie et peut changer de polarité. Une pile est typiquement DC. Le secteur est AC. Mais il peut exister du AC à faible tension et du DC à haute tension. »

## CTA
« Dans la formation complète, on apprend ensuite comment les mesurer correctement au multimètre. »

---

# Checklist tournage

- [ ] pile disponible ;
- [ ] multimètre prêt ;
- [ ] mode VDC clairement visible ;
- [ ] illustration ou source AC basse tension prête ;
- [ ] aucun tournage impliquant une manipulation directe du secteur par l’apprenant ;
- [ ] graphiques DC et AC exportés ;
- [ ] animation de fréquence prête ;
- [ ] tableau comparatif final prêt.
