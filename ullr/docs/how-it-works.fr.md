# Comment ça marche

De la photo de la cible au score validé, en cinq étapes. L'IA lit la cible. Ullr décide quoi entourer, applique votre règle de comptage et garde l'historique. Vous validez chaque volée.

![Les neuf étapes du comptage : photo, préparation et recadrage sur le téléphone ; requête et réponse au service d'IA ; repositionnement, signalement, points et vérification sur le téléphone.](images/diagrams/pipeline.fr.png){ width="250" align=right }

## 1. Vous prenez la photo

Après la volée, vous photographiez la cible de face, en cadrant le blason dans le cercle à l'écran. Avant tout, Ullr enregistre la photo sur le téléphone :

- remise dans le bon sens et réduite (une photo de téléphone est bien plus grande que nécessaire) ;
- **sans ses données cachées** : ni position, ni modèle de téléphone, ni date ;
- avec une petite copie pour les listes.

Par défaut, la copie qui sera envoyée est aussi **recadrée sur la zone de la cible** : les personnes ou les objets autour restent sur votre téléphone.

## 2. La photo part vers l'IA, avec des consignes

Ullr envoie une seule requête au service d'IA que vous avez choisi. Elle contient :

| Partie | Ce qu'elle dit |
|--------|----------------|
| **La photo** | La cible, recadrée. |
| **Comment lire une cible** | La même pour chaque volée. Trouver les flèches plantées dans le blason, pas les anciens trous ni les flèches des autres archers. Donner le point où chaque tube entre dans le blason, pas l'encoche. Appliquer la règle de la ligne : un tube qui touche une ligne prend la zone la plus haute. Signaler une flèche proche d'une ligne, et dire à quel point elle est sûre. |
| **Votre configuration** | Tirée de la séance : le blason et ses zones, le nombre de blasons et de spots (2 trispots = 6 spots), le nombre de flèches à chercher, votre règle de comptage avec la valeur de chaque zone, et la description de vos flèches. |
| **Le format de réponse** | Une liste de champs fixe, pour que la réponse soit toujours lisible. |

## 3. L'IA répond

Pour chaque flèche, l'IA donne :

- sa position sur la photo ;
- sa **zone** (X, 10 … 1, ou M) ;
- une **deuxième zone** si la flèche est sur une ligne ou tout près ;
- son niveau de **confiance**.

Elle donne la zone telle qu'elle est dessinée, pas les points. C'est voulu : Ullr transforme les zones en points avec votre règle, donc vous pouvez changer la règle d'une séance plus tard et tous les totaux sont recalculés, sans redemander à l'IA.

## 4. Ullr entoure ce qu'il faut vérifier

<div class="shots" markdown>
<figure markdown>
![Vérification d’une volée : un repère sur six flèches, deux entourées en orange, et 2 à vérifier.](images/screenshots/fr/review-check.png){ .shot }
<figcaption>Deux flèches entourées à vérifier</figcaption>
</figure>
</div>

Une flèche est entourée en orange quand :

- l'IA a donné une deuxième zone (elle est près d'une ligne) ;
- sa confiance est faible ;
- sur un trispot, deux flèches sont dans le même spot.

Un bandeau vous prévient aussi quand le nombre de flèches trouvées n'est pas le nombre tiré, quand aucune cible n'a été trouvée, ou quand la photo pose problème (reflet, flou, blason coupé).

Pourquoi plusieurs signaux ? La confiance d'une IA n'est pas toujours juste. Le cas dangereux, c'est une flèche mal comptée avec assurance. Demander à part « est-elle près d'une ligne ? » en rattrape beaucoup.

## 5. Vous validez

<div class="shots" markdown>
<figure markdown>
![Une flèche signalée sélectionnée : le choix de la zone met en évidence les deux zones possibles selon l'IA, 9 et 10, avec sa confiance.](images/screenshots/fr/review-select.png){ .shot }
<figcaption>Choisir la bonne zone, puis valider</figcaption>
</figure>
</div>

Vous corrigez une flèche entourée d'une touche, ajoutez une flèche oubliée ou retirez celle d'un autre archer, et validez. C'est seulement alors que la volée compte. Chaque volée garde sa photo : vous pouvez toujours la revoir.

## Le choix de l'IA

<div class="shots" markdown>
<figure markdown>
![Réglages : la méthode de comptage et le choix entre Anthropic, OpenAI et Google Gemini.](images/screenshots/fr/settings.png){ .shot }
<figcaption>Choisir l'IA dans les réglages</figcaption>
</figure>
</div>

| Service | Comment | Remarques |
|---------|---------|-----------|
| **Claude d'Anthropic** | Votre propre clé API | Recommandé : les consignes ont été conçues et testées avec Claude. |
| **OpenAI** | Votre propre clé API | Mêmes consignes. Pas encore testé sur de vraies photos de cible. |
| **Google Gemini** | Votre propre clé API | Mêmes consignes. Pas encore testé sur de vraies photos de cible. |
| **Application Claude** | Copier-coller, sans clé | Utilise votre propre compte ou abonnement Claude. |
| **À la main** | Rien | Toujours possible, sur chaque volée. |

## Au pas de tir

Il y a souvent peu de réseau sur un terrain de tir. Ullr enregistre d'abord chaque photo, et le comptage attend le réseau. Il démarre tout seul dès que le téléphone est de nouveau en ligne. Si vous voulez le score tout de suite, saisissez-le à la main. Fermer l'application ne fait rien perdre.

## Est-ce fiable ?

Ce n'est pas encore mesuré sur de vraies photos. C'est la prochaine étape : une centaine de photos de vraies volées, comptées à la main, passées dans chaque IA pour mesurer combien d'erreurs sont entourées. L'objectif : au moins 95 % des erreurs entourées pour que vous les vérifiiez. Voir la [feuille de route](roadmap.md).
