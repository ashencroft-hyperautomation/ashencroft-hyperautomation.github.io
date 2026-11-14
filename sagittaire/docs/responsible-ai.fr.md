# Vie privée, souveraineté et IA responsable

sagitt·AI·re met une IA au service des archers, et non l’inverse. Cette page explique ce que cela veut dire concrètement : vos registres restent les vôtres, vous choisissez qui voit une photo (ou personne), et l’IA ne fait que proposer.

## En bref

- **Vos registres vivent sur votre téléphone.** Ni compte, ni serveur à nous, ni publicité, ni outil d’analyse, ni pistage.
- **Vous choisissez l’IA, ou aucune.** Votre propre clé chez le service de votre choix, votre propre application d’IA, ou le comptage manuel, sans rien envoyer.
- **L’IA propose ; vous décidez.** Chaque flèche vous est montrée avant de compter, et les flèches douteuses sont encerclées.
- **Conçu pour être vérifié.** Désormais, les changements de consignes sont mesurés sur de vraies photos annotées avant d’être publiés.

## Vie privée : vos registres restent les vôtres

- Arcs, lieux, séances, photos et scores sont gardés dans le stockage privé de l’application, sur votre téléphone. Les autres applications ne peuvent pas les lire, et ils ne sont pas dans votre galerie.
- Il n’y a ni compte ni serveur à nous : le développeur ne reçoit rien de l’application.
- Rien n’est copié automatiquement vers une sauvegarde en ligne ou un nouveau téléphone. Vous décidez quand exporter, et où va le fichier.
- Quand une volée est comptée par un service d’IA, seul le nécessaire quitte le téléphone : la photo **recadrée sur la cible** (un réglage activé par défaut), **sans ses données cachées** (position, modèle de téléphone, date), les paramètres de votre épreuve, et votre clé. Votre nom, vos lieux, votre historique et vos scores ne sont jamais envoyés. Détails : [Vie privée](privacy.md) et la [politique de confidentialité](privacy-policy.md).

## Souveraineté : vous gardez la main

- **Choisissez votre service.** Prenez le service d’IA en qui vous avez confiance, avec votre propre clé : le compte, la facture et les conditions sont les vôtres, pas les nôtres.
- **Choisissez où il tourne.** Un service compatible OpenAI, à l’adresse que vous indiquez, peut être hébergé par vous-même ou dans la région de votre choix.
- **Ou pas d’IA du tout.** Le comptage manuel fonctionne pleinement : touchez vos flèches sur la photo ou tapez les points. Rien ne quitte le téléphone.
- **Aucun enfermement.** Une exportation est un seul fichier dans des formats ouverts (registres en JSON, photos en JPEG) que vous gardez, restaurez sur un autre téléphone ou lisez avec d’autres outils.
- **Aucune dépendance envers nous.** L’application n’a besoin d’aucun serveur à nous pour fonctionner, aujourd’hui comme demain.

## IA responsable : l’archer décide

- **Des suggestions, jamais officielles.** sagitt·AI·re sert à l’entraînement et au loisir ; en compétition, seules les feuilles de marque des arbitres comptent.
- **Chaque flèche est vérifiée.** Les points ne comptent qu’une fois la volée confirmée. Les flèches dont l’IA doute (près d’une ligne, en partie cachées, floues) sont encerclées, avec la zone de l’autre côté de la ligne prête à choisir.
- **La règle de la ligne, comme un arbitre.** Un tube qui touche une ligne marque la zone supérieure ; l’IA doit regarder le bord du tube, là où il entre dans le blason.
- **Elle signale quand quelque chose cloche.** Si la photo ne montre pas le blason choisi, l’application le dit et vous permet de le corriger.
- **Mesuré, pas supposé.** Désormais, les changements de consignes de l’IA sont testés sur de vraies photos annotées (zones exactes, doutes manqués, flèches encerclées) et ne sont publiés que s’ils font mieux.
- **Attentif au coût.** Une seule requête par volée, une photo recadrée sur la cible, aucun appel caché.

## Sécurité

- Votre clé API est chiffrée avec une clé gardée dans le matériel sécurisé du téléphone, n’est plus jamais affichée et n’est jamais mise dans une exportation.
- Les requêtes passent uniquement par HTTPS, vers l’adresse enregistrée avec la clé ; l’application ne suit pas les redirections ailleurs.
- Plus de détails : [Sécurité](security.md).

## Pour tout le monde

- Quatre langues : français, anglais, allemand et espagnol.
- Étiquettes pour lecteur d’écran, grandes zones tactiles et graphiques vérifiés pour les personnes daltoniennes.
- Ne s’adresse pas aux enfants de moins de 14 ans. Un parent peut choisir le comptage manuel, qui n’envoie rien.

## Les limites, en toute franchise

- Une IA peut se tromper, surtout en angle prononcé, avec des reflets ou des flèches serrées. C’est pour cela que vous vérifiez chaque volée.
- Le service d’IA que vous choisissez traite la photo selon ses propres conditions. Lisez-les, et choisissez le service et les réglages qui vous conviennent.

## Questions

Posez-les sur les [tickets GitHub](https://github.com/ashencroft-hyperautomation/ashencroft-hyperautomation.github.io/issues). Les tickets sont publics : n’y mettez ni renseignements personnels, ni photos, ni clés API.
