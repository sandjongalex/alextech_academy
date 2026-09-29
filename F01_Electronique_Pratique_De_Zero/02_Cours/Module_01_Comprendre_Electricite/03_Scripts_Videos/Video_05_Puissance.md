# Vidéo 05 — Comprendre la puissance électrique

**Durée cible :** 8 à 10 minutes  
**Format :** face caméra + schémas/animations + démonstration basse tension  
**Position dans le module :** après tension, courant et résistance ; avant énergie.

## Objectif pédagogique

À la fin de cette vidéo, l’apprenant doit pouvoir :
- expliquer simplement ce qu’est la puissance électrique ;
- distinguer puissance et énergie ;
- connaître l’unité watt (W) ;
- utiliser la relation `P = U × I` dans des cas simples ;
- comprendre pourquoi deux appareils alimentés sous la même tension peuvent consommer des puissances différentes ;
- relier puissance, échauffement et dimensionnement des composants.

---

## 0:00 – 0:35 — Hook

### Narration

« Deux appareils peuvent fonctionner sous exactement la même tension, par exemple 5 volts, mais l’un peut consommer 2 watts et l’autre 20 watts.

Alors si la tension est la même, qu’est-ce qui change réellement ?

C’est ici qu’intervient une grandeur très importante en électronique : la puissance électrique. »

### Visuel
- deux charges marquées `5 V` ;
- première : `0,4 A` ;
- seconde : `4 A` ;
- apparition des puissances correspondantes.

---

## 0:35 – 1:30 — Relier tension, courant et puissance

### Narration

« Dans les vidéos précédentes, nous avons vu deux grandeurs essentielles :

- la tension, qui représente une différence de potentiel entre deux points ;
- le courant, qui représente un débit de charges électriques.

La puissance nous indique maintenant à quel rythme l’énergie électrique est transférée ou transformée.

Autrement dit, elle nous donne une idée de l’intensité de l’action électrique d’un appareil à un instant donné. »

### À afficher

`Tension + courant → puissance`

Puis :

`Puissance = rythme de transfert / conversion d’énergie`

---

## 1:30 – 2:20 — Le watt

### Narration

« L’unité de la puissance est le watt, noté W.

Quand un appareil est donné pour 10 watts, 50 watts ou 100 watts, cette valeur parle de puissance, pas directement de la quantité totale d’énergie qu’il consommera sur une journée.

Le temps intervient plus tard quand on parlera d’énergie. »

### Visuel

Afficher plusieurs exemples :
- LED : quelques watts ;
- chargeur : dizaines de watts selon le modèle ;
- moteur : puissance variable selon l’application.

Préciser que les valeurs sont seulement illustratives.

---

## 2:20 – 4:10 — Relation fondamentale : P = U × I

### Narration

« Dans un circuit continu simple, une relation fondamentale est :

`P = U × I`

avec :

- P, la puissance en watts ;
- U, la tension en volts ;
- I, le courant en ampères.

Prenons un exemple simple.

Une charge fonctionne sous 5 volts et consomme 2 ampères.

Sa puissance vaut :

`P = 5 × 2 = 10 W`

Deuxième exemple.

Un petit montage fonctionne sous 12 volts et consomme 0,5 ampère.

`P = 12 × 0,5 = 6 W`

Tu vois donc qu’on ne peut pas connaître la puissance avec la tension seule. Il faut également connaître le courant consommé. »

### Visuels

Afficher successivement :

`5 V × 2 A = 10 W`

`12 V × 0,5 A = 6 W`

---

## 4:10 – 5:10 — Même tension, puissance différente

### Narration

« Revenons maintenant à notre question de départ.

Prenons deux appareils alimentés sous 5 volts.

Le premier consomme 0,2 ampère.

Sa puissance vaut :

`5 × 0,2 = 1 W`

Le second consomme 2 ampères.

Sa puissance vaut :

`5 × 2 = 10 W`

Même tension, mais puissance dix fois plus importante pour le second appareil.

La différence vient ici du courant consommé. »

### Visuel

Tableau simple :

| Appareil | U | I | P |
|---|---:|---:|---:|
| A | 5 V | 0,2 A | 1 W |
| B | 5 V | 2 A | 10 W |

---

## 5:10 – 6:20 — Puissance et échauffement

### Narration

« En électronique, la puissance est également importante parce qu’une partie de l’énergie électrique peut être transformée en chaleur.

C’est pour cette raison qu’un composant mal dimensionné peut chauffer fortement, voire être détruit.

Plus tard, quand nous étudierons les résistances, les transistors, les MOSFET et les régulateurs, nous reviendrons très souvent sur cette question de puissance dissipée.

Il ne suffit donc pas de vérifier qu’un composant supporte la bonne tension ou le bon courant. Il faut aussi vérifier la puissance qu’il doit dissiper ou transférer. »

### Visuels
- résistance qui chauffe ;
- boîtier transistor avec dissipateur ;
- icône chaleur.

---

## 6:20 – 7:15 — Démonstration pratique

### Option A — Lire un chargeur

Montrer un chargeur/alimentation portant une indication du type :

`5 V — 2 A`

### Narration

« Si la sortie indique 5 volts et jusqu’à 2 ampères, la puissance électrique maximale correspondante dans ce cas simple est :

`P = 5 × 2 = 10 W`

Attention : cela ne signifie pas forcément que l’appareil consomme en permanence 10 watts. Le courant réel dépend de la charge connectée, dans les limites prévues par l’alimentation. »

### Option B — Deux charges basse tension

Comparer deux petites charges fonctionnant sous la même tension, mais avec des courants différents.

---

## 7:15 – 7:55 — Erreur fréquente : puissance ≠ énergie

### Narration

« Une erreur très fréquente consiste à confondre puissance et énergie.

La puissance dit à quel rythme l’énergie est utilisée ou transférée.

L’énergie, elle, tient compte de la durée.

Un appareil de 100 watts utilisé pendant quelques secondes ne consomme pas la même quantité totale d’énergie que le même appareil utilisé pendant plusieurs heures. »

### À afficher

`Puissance = rythme`

`Énergie = puissance × durée`

Ne pas développer davantage : ce sera la vidéo suivante.

---

## 7:55 – 8:35 — Mini exercice

### Narration

« Petite question avant de continuer.

Un appareil fonctionne sous 12 volts et consomme 2 ampères.

Quelle est sa puissance ?

Mets la vidéo sur pause si tu veux calculer.

La réponse est :

`P = 12 × 2 = 24 W` »

### Deuxième question rapide

« Un autre appareil fonctionne aussi sous 12 volts, mais consomme seulement 0,5 ampère.

Sa puissance est donc :

`12 × 0,5 = 6 W` »

---

## 8:35 – 9:10 — Résumé

### Narration

« Retenons l’essentiel.

La puissance électrique décrit la vitesse à laquelle l’énergie est transférée ou transformée.

Elle se mesure en watts.

Dans un circuit continu simple :

`P = U × I`

Donc pour comprendre la puissance d’une charge, il faut regarder à la fois la tension et le courant. »

### Visuel résumé

`P = U × I`

`W = V × A`

---

## 9:10 – 9:30 — Transition vers la vidéo 6

### Narration

« Maintenant, une nouvelle question apparaît.

Si la puissance nous dit à quelle vitesse un appareil utilise de l’énergie, comment calculer la quantité totale utilisée pendant une minute, une heure ou une journée ?

C’est exactement ce que nous allons voir dans la prochaine vidéo avec l’énergie électrique. »

---

# Visuels à produire

1. Illustration `5 V / 0,4 A` vs `5 V / 4 A`.
2. Formule animée `P = U × I`.
3. Exemple `5 V × 2 A = 10 W`.
4. Exemple `12 V × 0,5 A = 6 W`.
5. Tableau comparaison de deux appareils sous 5 V.
6. Illustration puissance dissipée en chaleur.
7. Gros plan d’une étiquette de chargeur/alimentation.
8. Carte finale `Puissance ≠ énergie`.

# Matériel de tournage

- alimentation ou chargeur basse tension avec caractéristiques lisibles ;
- éventuellement deux charges basse tension ;
- multimètre si une mesure complémentaire est montrée ;
- tableau ou écran pour les calculs.

# Sécurité pédagogique

- rester sur des exemples basse tension pour les démonstrations ;
- ne pas ouvrir ni manipuler le secteur pour illustrer cette notion ;
- préciser qu’une valeur de courant inscrite sur une alimentation représente souvent une capacité maximale, pas un courant imposé en permanence à toute charge compatible.

# Extrait TikTok / Short possible

**Hook :** « Même tension, mais 10 fois plus de puissance : comment c’est possible ? »

Démonstration :
- appareil A : `5 V × 0,2 A = 1 W` ;
- appareil B : `5 V × 2 A = 10 W`.

Conclusion :
« La tension seule ne suffit pas. La puissance dépend aussi du courant. »

# Validation avant tournage

- [ ] Calculs vérifiés.
- [ ] Visuels `P = U × I` prêts.
- [ ] Chargeur/alimentation disponible.
- [ ] Exemple basse tension choisi.
- [ ] Transition vers l’énergie préparée.
