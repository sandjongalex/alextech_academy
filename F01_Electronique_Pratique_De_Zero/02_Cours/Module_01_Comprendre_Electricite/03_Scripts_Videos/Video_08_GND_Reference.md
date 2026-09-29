# Vidéo 08 — Masse, GND et référence électrique

## Position dans le module
Cette vidéo vient après la distinction DC/AC. Elle doit permettre à l’apprenant de comprendre qu’une tension n’existe jamais « toute seule » : elle est toujours mesurée entre deux points. Cette notion prépare directement les mesures au multimètre, les schémas électroniques, les alimentations et les futures interfaces entre microcontrôleurs et capteurs.

## Durée cible
8 à 10 minutes.

## Objectif pédagogique
À la fin de la vidéo, l’apprenant doit pouvoir :
- expliquer ce qu’est une référence électrique ;
- comprendre pourquoi GND est souvent choisi comme référence 0 V d’un circuit ;
- distinguer GND, masse châssis et terre de protection ;
- comprendre que deux circuits peuvent avoir des références différentes ;
- expliquer pourquoi deux systèmes doivent souvent partager une référence commune pour échanger un signal électrique correctement.

---

# SCRIPT DE TOURNAGE

## 0:00 – 0:40 — Hook

**Face caméra**

« Quand on dit qu’un point est à 5 volts, la première question devrait être : 5 volts par rapport à quoi ?

Parce qu’en électronique, une tension est toujours une différence entre deux points.

Et c’est exactement pour cela qu’on utilise une référence électrique, souvent appelée GND ou masse. Mais attention : GND ne veut pas forcément dire terre, et ce n’est pas non plus un zéro volt absolu universel. »

**Visuel écran**

`5 V ... par rapport à quoi ?`

Puis afficher deux points : A et B.

---

## 0:40 – 1:40 — Rappel : une tension se mesure entre deux points

« Dans la vidéo sur la tension, nous avons vu que le multimètre mesure une différence de potentiel entre deux points.

Si je place la pointe noire sur un point B et la pointe rouge sur un point A, l’appareil m’indique la tension de A par rapport à B.

Donc lorsqu’on dit qu’un circuit possède une alimentation de 5 V, cela signifie généralement que le rail positif est à 5 V par rapport au point de référence choisi du circuit. »

**Visuel**

- Point A : +5 V
- Point B : GND = 0 V de référence
- flèche de mesure entre B et A

**Texte écran**

`UAB = VA - VB`

Préciser oralement : « Pas besoin de mémoriser cette écriture maintenant. Retenez surtout qu’il faut toujours deux points. »

---

## 1:40 – 2:50 — Qu’est-ce que GND ?

« Pour simplifier les schémas et les mesures, on choisit généralement un point du circuit comme référence.

On décide alors de lui attribuer la valeur 0 volt.

Ce point est souvent appelé GND, Ground, masse ou commun selon le contexte.

À partir de cette référence, on peut décrire les autres tensions du circuit. Par exemple :

- ce point est à 3,3 V par rapport au GND ;
- celui-ci est à 5 V ;
- un autre peut même être à -5 V par rapport à cette même référence.

Le GND est donc avant tout un repère électrique. »

**Visuel**

Schéma simple avec :

- GND = 0 V
- rail +3,3 V
- rail +5 V
- éventuellement rail -5 V

**À retenir à l’écran**

`GND = référence choisie du circuit`

---

## 2:50 – 4:10 — GND n’est pas toujours la terre

« Voici une confusion très fréquente : penser que le symbole GND signifie automatiquement que le circuit est relié physiquement à la terre.

Ce n’est pas toujours vrai.

Prenons une petite carte électronique alimentée uniquement par une pile. Nous pouvons appeler la borne négative de la pile GND. Pourtant, cette borne n’est pas nécessairement reliée au sol ou à une installation de terre.

Il faut donc distinguer plusieurs notions. »

**Visuel comparatif**

1. **GND / signal ground** : référence électrique d’un circuit.
2. **Masse châssis** : partie métallique d’un équipement utilisée comme référence mécanique ou électrique selon la conception.
3. **Terre de protection / PE** : connexion de sécurité utilisée notamment dans les installations électriques.

« Ces trois éléments peuvent parfois être reliés ensemble, mais ce n’est pas une règle universelle. Cela dépend de la conception du système. »

**Important**
Ne pas transformer cette vidéo débutant en cours complet sur les schémas de liaison à la terre du réseau électrique.

---

## 4:10 – 5:20 — Deux circuits peuvent avoir deux références différentes

« Imaginons maintenant deux circuits totalement séparés.

Le circuit A possède sa propre pile et son propre GND A.

Le circuit B possède une autre pile et son propre GND B.

Tant que ces deux circuits sont isolés l’un de l’autre, rien ne nous oblige à dire que GND A et GND B sont exactement au même potentiel.

Chacun possède simplement sa propre référence interne. »

**Visuel**

Deux blocs séparés :

`Circuit A : +5 V / GND A`

`Circuit B : +9 V / GND B`

Aucune liaison entre eux.

« C’est une idée très importante : le zéro volt d’un circuit est généralement un choix de référence, pas un zéro absolu valable partout. »

---

## 5:20 – 6:50 — Pourquoi partager le GND pour communiquer ?

« Maintenant, imaginons qu’un microcontrôleur veuille envoyer un signal électrique à un autre circuit.

Supposons qu’il envoie un niveau de 5 V.

La question revient encore : 5 V par rapport à quoi ?

Si le deuxième circuit doit interpréter correctement ce signal, il doit connaître la même référence électrique, sauf si l’interface utilise une technique d’isolation ou de communication qui ne nécessite pas de référence commune directe. »

**Visuel**

Cas 1 :

- Carte A : sortie signal
- Carte B : entrée signal
- liaison SIGNAL seulement
- gros point d’interrogation sur la référence

Cas 2 :

- liaison SIGNAL
- liaison GND commun

« C’est pourquoi, dans beaucoup de montages simples avec Arduino, STM32, ESP32, capteurs ou modules, on relie aussi les GND des appareils lorsqu’ils doivent échanger directement un signal électrique. »

**Nuance importante**

« Mais plus tard, nous verrons qu’il existe aussi des systèmes isolés, par exemple avec des optocoupleurs ou certains bus isolés. Dans ce cas, la stratégie de référence peut être différente. »

---

## 6:50 – 8:00 — Démonstration avec deux piles

### Matériel
- deux piles ou deux petites sources basse tension indépendantes ;
- multimètre.

### Étape 1
Mesurer chaque pile séparément.

« Cette pile possède sa propre différence de potentiel entre ses deux bornes. »

Faire la même chose avec la seconde pile.

### Étape 2
Présenter les deux systèmes comme indépendants.

« Chacune peut avoir son propre zéro de référence dans son propre circuit. »

### Étape 3
Relier volontairement les bornes négatives dans une démonstration basse tension sûre.

« Maintenant, je décide que les deux bornes négatives constituent une référence commune. Je peux alors comparer plus facilement les autres points par rapport à cette même référence. »

**Important tournage**
Utiliser uniquement des sources basse tension simples et compatibles. Ne jamais illustrer cette notion en reliant arbitrairement des alimentations secteur ou des équipements inconnus.

---

## 8:00 – 8:50 — Erreurs fréquentes

### Erreur 1
« GND veut toujours dire terre. »

**Correction :** non. Le GND est souvent la référence électrique du circuit et peut être flottant par rapport à la terre.

### Erreur 2
« Tous les GND sont automatiquement identiques. »

**Correction :** non. Deux circuits isolés peuvent avoir des références différentes.

### Erreur 3
« Un point possède 5 V tout seul. »

**Correction :** on devrait préciser : 5 V par rapport à quelle référence ?

### Erreur 4
Relier deux masses sans comprendre le système.

**Correction :** dans les petits montages basse tension simples, une masse commune est souvent nécessaire. Mais dans des systèmes plus complexes, isolés ou reliés au secteur, il faut analyser l’architecture avant toute connexion.

---

## 8:50 – 9:25 — Question de validation

**À l’écran**

« Une carte fonctionne sur une pile de 9 V. Son GND doit-il obligatoirement être connecté à la terre du bâtiment ? »

Pause 3 secondes.

**Réponse**

« Non. Son GND peut simplement être la référence interne du circuit alimenté par la pile. »

Deuxième question rapide :

« Pourquoi relie-t-on souvent le GND d’un capteur au GND du microcontrôleur ? »

Réponse :

« Pour qu’ils interprètent les tensions des signaux par rapport à une référence commune. »

---

## 9:25 – 10:00 — Résumé et transition

« Retenez trois idées.

Premièrement, une tension est toujours mesurée entre deux points.

Deuxièmement, GND est généralement le point de référence auquel on attribue 0 volt dans un circuit.

Troisièmement, GND, masse châssis et terre ne signifient pas automatiquement la même chose.

Dans la prochaine vidéo, nous allons apprendre à lire correctement les unités et les préfixes : milli, micro, kilo et méga. C’est indispensable pour éviter des erreurs de facteur mille ou même un million en électronique. »

---

# Visuels à produire

1. Tension mesurée entre deux points A et B.
2. Rail +5 V par rapport au GND.
3. Schéma avec +5 V, +3,3 V, 0 V et -5 V.
4. Comparatif GND / masse châssis / terre de protection.
5. Deux circuits flottants avec GND A et GND B.
6. Deux cartes communiquant sans GND commun puis avec GND commun.
7. Démonstration de deux piles et référence commune.
8. Carton final : `Une tension = toujours entre deux points`.

---

# Extrait potentiel TikTok / Short

## Hook
« Quand tu dis “ce point est à 5 V”, il manque une information essentielle. »

## Corps
« 5 V par rapport à quoi ? En électronique, une tension est toujours une différence entre deux points. Le GND sert souvent de référence 0 V, mais il ne signifie pas forcément que ton circuit est relié à la terre. »

## CTA
« Si tu veux comprendre l’électronique depuis zéro, la formation complète est disponible sur AlexTech Academy. »

---

# Checklist avant tournage

- multimètre disponible ;
- deux piles ou deux sources basse tension sûres ;
- fils de connexion ;
- préparer les symboles GND et terre ;
- préparer les schémas Circuit A / Circuit B ;
- ne faire aucune démonstration directe sur le secteur ;
- cadrer clairement les pointes du multimètre pendant les mesures ;
- rappeler plusieurs fois la phrase : « une tension se mesure entre deux points ».
