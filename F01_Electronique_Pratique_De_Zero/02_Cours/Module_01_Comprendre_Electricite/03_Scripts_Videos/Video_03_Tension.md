# Vidéo 03 — Comprendre la tension électrique

## Durée cible
8 à 10 minutes.

## Objectif pédagogique
À la fin de cette vidéo, l’apprenant doit pouvoir :
- expliquer simplement ce qu’est une tension électrique ;
- comprendre qu’une tension se mesure toujours entre deux points ;
- distinguer tension disponible et courant réellement consommé ;
- identifier le symbole U et l’unité volt ;
- comprendre pourquoi une référence électrique est indispensable.

---

# Script de tournage

## 0:00 – 0:35 — Hook

### Narration
« Regarde cette pile de 9 volts. Rien n’est branché dessus. Pourtant, si je prends un multimètre et que je mesure entre ses deux bornes, il affiche environ 9 volts.

Alors une question importante se pose : si aucun courant ne circule dans un circuit extérieur, qu’est-ce que représentent réellement ces 9 volts ?

C’est exactement ce que nous allons comprendre dans cette vidéo. »

### Visuel
- gros plan sur une pile 9 V ;
- multimètre affichant une valeur proche de 9 V ;
- texte à l’écran : **Tension ≠ courant**.

---

## 0:35 – 1:20 — Rappel de la vidéo précédente

### Narration
« Dans la vidéo précédente, nous avons vu que le courant électrique correspond à un déplacement organisé de charges électriques dans un circuit.

Mais pour que ces charges commencent à se déplacer, il faut qu’il existe une cause, une différence entre deux points du circuit.

Cette différence, c’est ce que nous appelons la tension électrique. »

### Visuel
- conducteur avec charges immobiles ;
- puis deux points A et B avec niveaux différents ;
- flèche entre A et B.

---

## 1:20 – 2:30 — La tension est toujours une différence entre deux points

### Narration
« Une erreur très fréquente chez les débutants consiste à penser qu’un point possède une tension tout seul.

En réalité, une tension se mesure toujours entre deux points.

Par exemple, si je dis : “ce point est à 5 volts”, la question correcte est : 5 volts par rapport à quoi ?

Dans beaucoup de circuits électroniques, on choisit un point de référence que l’on appelle souvent GND ou masse.

On peut alors dire : ce point est à 5 volts par rapport au GND. »

### Visuel
- point A : +5 V ;
- point B : GND ;
- indication U_AB = 5 V ;
- rappel : **une tension = comparaison entre 2 points**.

---

## 2:30 – 3:45 — Différence de potentiel

### Narration
« Le terme plus rigoureux utilisé en électricité est différence de potentiel.

Imagine deux niveaux différents. Tant qu’il existe une différence entre ces deux niveaux, il existe une possibilité de transfert d’énergie.

Pour la tension électrique, l’idée est comparable : une source comme une pile crée une différence de potentiel entre ses deux bornes.

Cette différence peut provoquer le déplacement des charges lorsque nous fermons le circuit avec une charge. »

### Analogie
« Une comparaison simple consiste à imaginer deux réservoirs d’eau placés à des hauteurs différentes.

La différence de hauteur crée une possibilité d’écoulement. Mais attention : cette analogie aide à comprendre l’idée de différence, elle ne décrit pas parfaitement tous les phénomènes électriques. »

### Visuel
- deux réservoirs à hauteurs différentes ;
- puis équivalent électrique avec une pile.

---

## 3:45 – 4:35 — Le volt et le symbole U

### Narration
« La tension électrique est généralement représentée par la lettre U dans les cours d’électronique et d’électricité.

Son unité est le volt, symbole V.

On peut rencontrer :
- 1,5 V pour une pile ;
- 3,3 V dans de nombreux microcontrôleurs ;
- 5 V dans beaucoup de circuits numériques ;
- 12 V dans des systèmes automobiles ou certaines alimentations.

Nous apprendrons plus tard à manipuler ces tensions correctement et à les adapter à nos circuits. »

### Visuel
Tableau simple :
- pile AA → 1,5 V ;
- logique → 3,3 V / 5 V ;
- batterie/alim → 12 V.

---

## 4:35 – 6:05 — Démonstration au multimètre

### Matériel
- pile 1,5 V ou pile 9 V ;
- multimètre ;
- cordons rouge et noir.

### Narration
« Passons à une mesure réelle.

Je règle le multimètre sur la mesure de tension continue, VDC.

Je place la pointe noire sur la borne négative de la pile et la pointe rouge sur la borne positive.

Le multimètre affiche alors la différence de potentiel entre ces deux bornes.

Si j’inverse les pointes, la valeur reste proche de la même amplitude mais le signe devient négatif. Cela signifie simplement que j’ai inversé le sens dans lequel je compare les deux points. »

### Démonstration
1. mesure normale ;
2. inversion rouge/noir ;
3. montrer le signe négatif.

### Point pédagogique
« Le multimètre ne mesure donc pas “la tension d’un point”. Il compare deux points. »

---

## 6:05 – 7:00 — Pourquoi la pile affiche 9 V sans charge ?

### Narration
« Revenons à la question du début.

Pourquoi une pile peut-elle afficher 9 volts alors qu’aucune lampe ni résistance n’est branchée dessus ?

Parce que la pile maintient une différence de potentiel entre ses deux bornes.

Il n’est pas nécessaire qu’un courant important circule dans une charge extérieure pour que cette différence de potentiel existe.

Lorsque nous branchons ensuite un circuit fermé, cette tension peut contribuer à provoquer un courant. »

### Visuel
- pile seule : tension présente, courant extérieur nul ou négligeable ;
- pile + résistance : tension + courant.

---

## 7:00 – 7:50 — Tension disponible et courant consommé

### Narration
« Il faut donc éviter une confusion très importante.

Une alimentation peut fournir une certaine tension, par exemple 5 volts, mais cela ne signifie pas qu’un courant fixe circule en permanence.

Le courant dépendra ensuite du circuit connecté, de ses composants et de ses caractéristiques.

Nous étudierons cette relation plus précisément avec la résistance et la loi d’Ohm. »

### Visuel
- alimentation 5 V sans charge ;
- alimentation 5 V avec petite charge ;
- alimentation 5 V avec autre charge ;
- tension identique, courant différent.

---

## 7:50 – 8:35 — Erreurs fréquentes

### Narration
« Retenons trois erreurs fréquentes.

Première erreur : confondre tension et courant.

Deuxième erreur : dire qu’un point est à 5 volts sans préciser la référence.

Troisième erreur : croire qu’une tension n’existe que lorsqu’un courant important circule.

Une tension peut être présente entre deux points même lorsqu’aucune charge extérieure n’est connectée. »

### Visuel
Checklist à l’écran :
- tension ≠ courant ;
- toujours 2 points ;
- toujours une référence.

---

## 8:35 – 9:10 — Question de validation

### À l’écran
« Si ton multimètre affiche -9 V lorsque tu mesures une pile de 9 V, est-ce que la pile est défectueuse ? »

### Réponse après pause
« Non. Dans la plupart des cas, cela signifie simplement que les pointes du multimètre sont inversées par rapport à la polarité de la pile. »

---

## 9:10 – 9:40 — Résumé

### Narration
« Résumons.

La tension électrique est une différence de potentiel entre deux points.

Elle se mesure en volts.

Elle peut exister même lorsqu’aucun courant important ne circule dans un circuit extérieur.

Et lorsqu’on donne la tension d’un point, il faut toujours savoir par rapport à quelle référence cette tension est définie. »

### Visuel
**Tension = différence de potentiel entre deux points**

---

## 9:40 – 10:00 — Transition

### Narration
« Nous avons maintenant compris les charges, le courant et la tension.

Mais lorsqu’une tension est appliquée à un circuit, qu’est-ce qui limite le courant ?

Dans la prochaine vidéo, nous allons introduire l’un des composants les plus importants de toute l’électronique : la résistance. »

---

# Visuels à produire

1. Pile 9 V + multimètre.
2. Schéma de deux points A et B avec U_AB.
3. Animation simple de différence de potentiel.
4. Analogie des deux réservoirs à hauteurs différentes.
5. Tableau 1,5 V / 3,3 V / 5 V / 12 V.
6. Multimètre avec pointes normales puis inversées.
7. Comparaison pile seule / pile + charge.
8. Checklist des trois erreurs fréquentes.

---

# Extrait potentiel TikTok / Short

## Hook
« Une pile peut afficher 9 V même quand rien n’est branché. Pourquoi ? »

## Contenu
Montrer la mesure, expliquer en 30 à 45 secondes qu’une tension est une différence de potentiel entre deux points et qu’elle peut exister sans courant important dans une charge extérieure.

## CTA
« Dans la formation complète, on apprend à mesurer et comprendre tension, courant et résistance avec de vrais circuits. »
