# Vidéo 04 — Introduction à la résistance électrique

**Durée cible :** 8 à 10 minutes  
**Niveau :** débutant  
**Rôle dans le parcours :** introduire qualitativement la résistance avant son étude approfondie au Module 2.

## Hook — 0:00 à 0:30

« Pourquoi deux circuits alimentés avec la même tension ne laissent-ils pas forcément passer le même courant ? Si la tension est la même, qu’est-ce qui vient limiter le déplacement des charges ? C’est ici qu’intervient une grandeur fondamentale : la résistance électrique. »

**Visuel :** deux circuits simples alimentés par la même source, avec deux résistances de valeurs différentes et des intensités différentes représentées par des flèches.

---

## 1. Rappel : tension, courant, résistance — 0:30 à 1:30

« Dans les vidéos précédentes, nous avons vu deux notions essentielles : la tension et le courant.

La tension représente une différence de potentiel entre deux points. Elle peut favoriser le déplacement des charges.

Le courant, lui, représente le débit de charges qui traverse le circuit.

Mais dans la réalité, les charges ne circulent pas librement de la même manière dans tous les matériaux. Certains matériaux laissent passer le courant facilement, d’autres s’y opposent davantage.

Cette opposition au passage du courant est ce que l’on appelle la résistance électrique. »

**À l’écran :**
- tension → différence de potentiel ;
- courant → débit de charges ;
- résistance → opposition au passage du courant.

---

## 2. Qu’est-ce que la résistance électrique ? — 1:30 à 2:45

« La résistance électrique traduit la difficulté qu’un matériau ou qu’un composant oppose au passage du courant.

Plus la résistance est élevée, plus il est difficile pour un courant important de circuler dans les mêmes conditions de tension.

À l’inverse, une faible résistance facilite davantage le passage du courant.

Attention : cela ne signifie pas que la résistance “bloque totalement” le courant. Dans beaucoup de circuits, elle sert justement à contrôler la valeur du courant. »

**Analogie possible :** tuyau plus ou moins étroit.

« On peut utiliser l’image d’un tuyau : si le passage est très large, l’écoulement est plus facile ; s’il est très étroit, l’écoulement est davantage limité. Cette analogie aide à visualiser l’idée, même si un circuit électrique réel est plus complexe qu’un circuit hydraulique. »

---

## 3. L’unité : l’ohm — 2:45 à 3:30

« La résistance se mesure en ohms.

Son symbole est la lettre grecque oméga : Ω.

Tu rencontreras très souvent :
- 10 Ω ;
- 100 Ω ;
- 1 kΩ, soit 1 000 Ω ;
- 10 kΩ ;
- 1 MΩ, soit 1 000 000 Ω.

Dans la suite de la formation, nous apprendrons à lire rapidement ces valeurs et à choisir la bonne résistance pour une application donnée. »

**Visuel :** Ω, kΩ, MΩ avec conversions simples.

---

## 4. La résistance dépend du matériau — 3:30 à 4:30

« Tous les matériaux ne s’opposent pas de la même façon au courant.

Le cuivre, par exemple, est très utilisé pour fabriquer des conducteurs parce qu’il possède une faible résistance électrique pour des dimensions usuelles.

D’autres matériaux résistent beaucoup plus au passage du courant.

C’est pour cela que le matériau choisi dans un câble, une piste de circuit imprimé, une résistance ou un élément chauffant a une importance directe sur le comportement électrique. »

**Visuel :** cuivre vs matériau résistif.

---

## 5. La géométrie influence aussi la résistance — 4:30 à 5:30

« La résistance ne dépend pas seulement du matériau.

La longueur et la section du conducteur jouent également un rôle.

De manière qualitative :
- un conducteur plus long présente généralement plus de résistance ;
- un conducteur plus épais présente généralement moins de résistance.

C’est une idée très importante lorsque l’on dimensionne des câbles ou des pistes de PCB pour transporter du courant. »

**Visuel :** deux fils, un long/fin et un court/épais.

---

## 6. La température peut modifier la résistance — 5:30 à 6:15

« La température peut également modifier la résistance d’un matériau.

Dans de nombreux métaux, lorsque la température augmente, la résistance augmente aussi.

Tu comprendras plus tard pourquoi certains composants chauffent, pourquoi les pistes et câbles doivent être correctement dimensionnés et pourquoi la puissance dissipée compte autant en électronique. »

---

## 7. Le composant “résistance” — 6:15 à 7:15

« En électronique, on utilise aussi un composant spécialement conçu pour présenter une valeur de résistance connue : la résistance, ou resistor en anglais.

Elle peut servir à limiter un courant, créer un diviseur de tension, fixer un niveau logique, polariser un transistor et réaliser de nombreuses autres fonctions.

Pour le moment, retiens simplement ceci : ce composant possède une valeur exprimée en ohms et cette valeur influence directement le courant dans le circuit. »

**Visuel :** résistance traversante + résistance CMS + symbole schématique.

**Important :** ne pas encore détailler le code couleur ; cela sera traité dans le Module 2.

---

## 8. Démonstration au multimètre — 7:15 à 8:30

**Matériel :** multimètre + résistances de 220 Ω, 1 kΩ et 10 kΩ environ.

« Prenons maintenant trois résistances différentes et mesurons-les au multimètre.

Je place le multimètre en mode ohmmètre. Le circuit doit être hors tension pour ce type de mesure.

Première résistance : environ 220 Ω.

Deuxième : environ 1 kΩ.

Troisième : environ 10 kΩ.

Tu vois que même si les composants se ressemblent physiquement, leur comportement électrique peut être très différent. »

**Sécurité / méthode :** préciser qu’on ne mesure pas une résistance dans un circuit alimenté.

---

## 9. Erreur fréquente — 8:30 à 9:10

« Une erreur fréquente consiste à dire qu’une résistance “réduit la tension”.

Ce n’est pas une bonne définition.

La résistance s’oppose au passage du courant. Une chute de tension peut apparaître à ses bornes lorsqu’un courant la traverse, mais cette chute dépend du circuit dans lequel elle se trouve.

Nous verrons précisément cette relation avec la loi d’Ohm dans la suite de la formation. »

---

## 10. Résumé — 9:10 à 9:40

« Retenons quatre idées :

1. La résistance représente une opposition au passage du courant.
2. Elle se mesure en ohms, symbole Ω.
3. Elle dépend notamment du matériau, de la géométrie et de la température.
4. Le composant résistance est utilisé pour contrôler le comportement électrique d’un circuit. »

---

## Question de validation — 9:40 à 9:55

« Entre un conducteur très long et fin et un conducteur court et épais du même matériau, lequel aura généralement la résistance la plus élevée ? »

**Réponse attendue :** le conducteur long et fin.

---

## Transition — 9:55 à 10:10

« Nous consacrerons un module complet aux résistances : code couleur, valeurs normalisées, tolérance, puissance et dimensionnement. Mais avant cela, il nous reste une notion essentielle à comprendre dans ce premier module : la puissance électrique. »

---

## Visuels à produire

- schéma tension / courant / résistance ;
- animation d’un passage large vs étroit ;
- symbole Ω ;
- tableau Ω / kΩ / MΩ ;
- comparaison matériaux ;
- fil long/fin vs court/épais ;
- résistance traversante et CMS ;
- symbole schématique de résistance ;
- capture ou plan rapproché de la mesure à l’ohmmètre.

## Extrait TikTok / Short potentiel

**Hook :** « Une résistance ne sert pas simplement à réduire la tension. »

Format court :
1. montrer une résistance ;
2. corriger l’idée reçue ;
3. expliquer qu’elle s’oppose au courant ;
4. afficher Ω ;
5. CTA : « Le cours complet d’électronique est dans AlexTech Academy. »
