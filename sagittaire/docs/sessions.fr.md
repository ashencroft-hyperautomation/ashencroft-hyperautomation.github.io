# Séances

Une séance, c’est une visite au pas de tir : un lieu, une date, un arc et une épreuve, et les volées que vous tirez. En mode jeu, la **ligne de tir** en commence une, et **Tirer maintenant** ouvre directement l’appareil photo.

<div class="shots" markdown>
<figure markdown>
![Formulaire de nouvelle séance rempli pour un arc à poulies sur deux trispots verticaux.](images/screenshots/fr/new-session.png){ .shot }
<figcaption><b>Nouvelle séance.</b> Les valeurs par défaut de l’arc remplissent le reste.</figcaption>
</figure>
<figure markdown>
![Écran de séance avec le total, le graphique des volées et la feuille de marque.](images/screenshots/fr/session.png){ .shot }
<figcaption><b>La séance.</b> Total, graphique et feuille de marque.</figcaption>
</figure>
</div>

## Commencer une séance

Dans l’onglet **Accueil**, touchez **Commencer une séance**, puis remplissez :

- **Lieu** : tapez-en un nouveau, ou choisissez-en un déjà utilisé. Pour corriger une faute de frappe, réunir deux noms du même terrain ou en retirer un, voir [Lieux enregistrés](#lieux-enregistres).
- **Date** : maintenant, par défaut.
- **Discipline** : tir sur cible (par défaut), tir en campagne, tir 3D ou para-tir à l’arc.
- **Type d’arc** (arc nu, arc recourbé ou arc à poulies, chacun avec son petit dessin) et **arc**. Les valeurs par défaut de l’arc remplissent le reste. Voir [Arcs](bows.md).
- Sous la distance, le **repère de visée** de l’arc à cette distance, et les **flèches** quand l’arc a des jeux de flèches : le jeu utilisé la dernière fois. Voir [Repères de visée, jeux de flèches et carnet de réglages](bows.md#reperes-de-visee-jeux-de-fleches-et-carnet-de-reglages).
- **Distance**, **blason**, **blasons sur la butte** (pour les trispots : combien il y en a sur la butte, par exemple 2 blasons = 6 spots) et **flèches par volée** (n’importe quel nombre, souvent 3 ou 6). Les blasons suivent la discipline : blasons de tir sur cible, blasons de **campagne** (80, 60, 40 cm, ou 20 cm en colonnes de trois), ou la cible **3D**. Voir [Campagne et 3D](rules.md#campagne-et-3d).
- **Comptage** : la règle, proposée d’après les réglages et le type d’arc. Voir [Règles de comptage](rules.md).

## Tirer une volée

1. Tirez votre volée et allez à la cible.
2. Touchez **Prendre la photo**. Placez-vous face à la cible et cadrez le blason dans le cercle à l’écran. Vous pouvez aussi choisir une photo avec **Depuis la galerie**, ou saisir la volée à la main.
3. La suite dépend de la [méthode de comptage](scoring.md) : comptée en arrière-plan, partagée avec votre application d’IA, ou placée par vous.
4. [Vérifiez la volée](review.md) et validez-la. **Valider · volée suivante** revient directement à l’appareil photo.

Avec le comptage automatique, pas besoin d’attendre : tirez la volée suivante pendant que la précédente est comptée. Chaque volée affiche son état dans la feuille de marque (voir [Votre propre clé API](scoring-api.md#au-pas-de-tir)).

## L’écran de la séance

- **Feuille de marque :** volée par volée, avec le cumul. Touchez une volée pour revoir sa photo et ses flèches.
- Le graphique **Score par volée**, avec la ligne de moyenne, et la meilleure et la moins bonne volée.
- **Modifier** change la règle de comptage, à tout moment. Tous les totaux sont recalculés.
- Le **repère de visée** à cette distance et les **flèches** tirées, chacun avec **Modifier**.
- **Terminer**. Les volées non validées ne comptent pas tant que vous ne les validez pas, ce que vous pouvez encore faire plus tard.
- **Supprimer cette séance** l’efface, après confirmation.
- **Record personnel :** une fois terminée, la séance dit où elle se situe sur son épreuve (même distance, blason, blasons sur la butte et nombre de flèches) : votre record personnel, et le score qu’elle a battu; égale au record; ou le record à battre.

## Partager une séance

![Le résumé de la séance avec sa ligne de record personnel, et le menu Partager ouvert : En texte, ou Avec une image de la feuille de marque.](images/screenshots/fr/session-share.png){ .shot width="220" align=right }

Le bouton **Partager cette séance**, en haut d’une séance qui a au moins une volée validée, ouvre la fenêtre de partage du téléphone : courriel, messages, une conversation avec votre entraîneur.

- **En texte** : la date, l’arc et le lieu, l’épreuve, la règle de comptage, le total, la moyenne et le nombre de X, puis chaque volée avec ses flèches, son total et le cumul.
- **Avec une image de la feuille de marque** : le même texte, plus une image avec les totaux et chaque flèche dans la couleur de sa zone.

![L’image de la feuille de marque : les renseignements et le total de la séance sur un bandeau foncé, puis une ligne par volée avec ses flèches dans la couleur de leur zone, le total de la volée et le cumul.](images/screenshots/fr/share-card.png){ .shot width="220" }

Seul ce que montre l’écran de la séance est partagé, et seulement avec l’application choisie : jamais les photos de vos volées.

Une séance en cours apparaît dans l’onglet **Accueil** avec **Reprendre**. Si l’application se ferme pendant une séance, rien n’est perdu.

## Lieux enregistrés

![Lieux enregistrés : chaque lieu avec son nombre de séances et la date de sa dernière utilisation, avec un crayon pour le renommer et une corbeille pour le supprimer.](images/screenshots/fr/places.png){ .shot width="220" align=right }

**Réglages → Lieux enregistrés** liste tous les lieux que vous avez saisis, du plus récent au plus ancien, avec le nombre de séances qui y ont eu lieu.

- **Renommer** (le crayon, ou touchez le lieu) : corrige une faute de frappe partout à la fois, puisque toutes les séances qui y ont eu lieu suivent.
- **Fusionner** : donnez à un lieu le nom d’un autre (*terrain du club* et *Terrain du club*, par exemple). sagitt·AI·re vous le dit d’abord, et le bouton devient **Fusionner**. Les séances des deux se retrouvent sous un seul nom.
- **Supprimer** (la corbeille), après confirmation : le lieu quitte la liste, et les séances qui y ont eu lieu sont conservées, sans lieu.
