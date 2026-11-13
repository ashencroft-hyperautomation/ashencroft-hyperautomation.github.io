# Politique de confidentialité

*Version 3 · En vigueur le 13 novembre 2026*

La présente politique explique quels renseignements l’application sagitt·AI·re (l’« Application ») traite, où ils sont conservés, quand ils quittent votre appareil et ce que vous pouvez faire à leur égard. Elle fait partie des conditions d’utilisation. Le « Développeur » désigne le développeur de sagitt·AI·re.

## 1. En bref

Le Développeur ne recueille rien. L’Application n’a ni compte, ni publicité, ni outil d’analyse, ni pistage, et elle n’envoie rien au Développeur. Vos registres restent sur votre appareil. Une photo de la cible ne quitte votre appareil que lorsque vous choisissez de faire compter une volée par un service d’intelligence artificielle (« IA »), et seulement vers ce service.

## 2. Ce que l’Application conserve sur votre appareil

Pour fonctionner, l’Application conserve les éléments suivants dans son espace de stockage privé, sur votre appareil :

- vos arcs (nom, type, réglages et description de vos flèches) et les lieux où vous tirez, tels que vous les nommez;
- vos séances : date, lieu, arc, distance, blason, volées, flèches, pointages, ainsi que la photo de chaque volée et un petit aperçu;
- vos réglages, dont votre méthode de comptage, les services d’IA que vous avez configurés, leurs adresses et leurs modèles, votre apparence et votre archer en mode jeu, ainsi que la date à laquelle vous avez accepté les conditions d’utilisation;
- vos clés API, chiffrées au moyen d’une clé conservée dans le matériel sécurisé de l’appareil (Android Keystore).

Les autres applications ne peuvent pas lire ces renseignements, et les photos n’apparaissent pas dans votre galerie. L’Application désactive la sauvegarde automatique d’Android dans le nuage et le transfert d’un appareil à un autre : rien n’est donc copié automatiquement hors de votre appareil.

## 3. Quand des renseignements quittent votre appareil

**Comptage avec votre propre clé API.** Lorsqu’une volée est comptée, l’Application envoie, par une connexion chiffrée (HTTPS) et uniquement au service d’IA que vous avez choisi, à l’adresse enregistrée avec sa clé :

- la photo de la volée, dont les données cachées (lieu, modèle de l’appareil, date) ont été retirées et qui, sauf si vous désactivez cette option, est recadrée sur la cible;
- les renseignements dont le service a besoin pour la compter : le blason et les blasons sur la butte, le nombre de flèches, la règle de pointage, la description de vos flèches et la langue de ses remarques;
- votre clé API, qui identifie votre compte auprès de ce service.

Votre nom, vos lieux, votre historique, vos pointages et les détails de votre appareil ne sont jamais envoyés. Les renseignements techniques que les applications envoient habituellement au sujet de l’appareil sont remplacés par « unknown ». Comme pour tout service Internet, le service d’IA peut voir votre adresse réseau (IP).

**Partage avec votre application d’IA.** L’Application prépare la photo et une requête, et vous choisissez l’application avec laquelle les partager, au moyen de la fenêtre de partage d’Android. La suite se passe entre vous et cette application.

**Comptage manuel.** Rien ne quitte votre appareil.

**Partage d’une séance.** Lorsque vous touchez Partager sur une séance, l’Application prépare un résumé (date, arc, lieu, épreuve, pointages et, si vous le choisissez, une image de la feuille de marque), et vous choisissez l’application avec laquelle le partager. Les photos de vos volées n’y sont jamais incluses.

**Signaler un problème de comptage.** Lorsque vous touchez Signaler un problème de comptage sur une volée, l’Application rédige un e-mail sur cette volée (blason, distance, règle, modèle d’IA, et chaque flèche telle que l’IA l’a comptée et telle qu’elle est maintenant) et, si vous cochez la case, y joint la copie de la photo envoyée au service d’IA. Votre application de messagerie s’ouvre sans destinataire : vous choisissez à qui l’envoyer, et rien n’est envoyé tant que vous ne l’envoyez pas. Vos arcs, lieux et dates n’y figurent pas.

**Exportations.** Lorsque vous exportez vos registres, l’Application écrit un fichier à l’endroit que vous choisissez (par exemple, vos téléchargements ou un espace de stockage en ligne). Les clés API et les adresses des services ne sont jamais incluses dans une exportation. Gardez ce fichier en lieu sûr : quiconque l’a en main peut lire vos registres.

**Vérification d’une clé.** Le bouton « Vérifier la clé » envoie votre clé à son service pour confirmer qu’elle fonctionne.

## 4. Services d’IA

Chaque service d’IA que vous utilisez est une entreprise distincte qui a ses propres conditions et sa propre politique de confidentialité. Ce sont elles qui déterminent comment il utilise, conserve et protège ce qu’il reçoit, notamment s’il peut s’en servir pour entraîner ses modèles, et où dans le monde il le traite, ce qui peut être à l’extérieur du Québec et du Canada. Lisez-les avant d’utiliser le service, et choisissez le service et les réglages de votre compte en conséquence. Le Développeur n’a aucun contrôle sur ces services et ne reçoit rien d’eux.

## 5. Autorisations

- **Appareil photo**, pour photographier la cible. Android vous le demande la première fois.
- **Internet**, pour joindre le service d’IA que vous avez choisi. Elle n’est pas utilisée en comptage manuel.

L’Application ne demande aucune autorisation de localisation, de contacts, de microphone ou de stockage. L’importation d’une photo passe par le sélecteur de photos d’Android, qui ne donne à l’Application que la photo choisie.

## 6. Durée de conservation

Vos renseignements restent sur votre appareil jusqu’à ce que vous les supprimiez. Vous pouvez supprimer une volée ou une séance, supprimer les anciennes photos en pleine taille (Réglages → Stockage et sauvegarde → Libérer de l’espace), retirer une clé, ou effacer toutes les séances ou tout (Réglages → Stockage et sauvegarde → Effacer les données). La désinstallation de l’Application supprime tout ce qu’elle conserve sur votre appareil.

## 7. Vos choix et vos droits

Comme le Développeur ne détient aucun renseignement à votre sujet, tout ce que l’Application sait de vous se trouve sur votre appareil et reste sous votre contrôle : vous pouvez le consulter dans l’Application, en obtenir une copie au moyen d’une exportation, le rectifier et le supprimer, comme il est décrit ci-dessus. Pour les renseignements qu’un service d’IA a reçus, exercez les droits que vous donne sa politique de confidentialité; en vertu des lois du Québec et du Canada, et des lois de l’endroit où vous résidez, vous pouvez avoir auprès de ce service des droits d’accès, de rectification et de suppression.

## 8. Sécurité

L’Application protège vos renseignements au moyen de l’isolement des applications d’Android, chiffre vos clés API, n’envoie les demandes de comptage que par HTTPS, bloque les connexions non chiffrées et retire les données cachées des photos avant de les envoyer. Aucune méthode n’est entièrement sûre : protégez votre appareil par un verrouillage d’écran, créez une clé API réservée à l’Application avec une limite de dépenses, et supprimez-la auprès de son service si vous perdez votre appareil.

## 9. Enfants

L’Application ne s’adresse pas aux enfants de moins de 14 ans et ne recueille de renseignements auprès de personne. Les services d’IA fixent leur propre âge minimum. Un parent ou un tuteur devrait configurer tout service d’IA qu’un enfant utilise, ou choisir le comptage manuel, qui n’envoie rien.

## 10. Modifications de la présente politique

Si la présente politique change de façon importante, la nouvelle version sera affichée dans l’Application, avec sa date, et il vous sera demandé d’accepter de nouveau les conditions d’utilisation avant de continuer. La version en vigueur se trouve toujours dans l’Application (Réglages → À propos et mentions légales) et sur le site Web de sagitt·AI·re.

## 11. Questions

L’Application et son site Web sont créés pro bono pour Tir à l’arc Canada et gérés par le Développeur. Pour toute question sur la présente politique, ouvrez un billet (« issue ») à l’adresse github.com/ashencroft-hyperautomation/ashencroft-hyperautomation.github.io/issues. Les billets sont publics : n’y incluez aucun renseignement personnel, aucune photo et aucune clé API.

## 12. Langue

La présente politique est rédigée en français et en anglais, et les deux versions font également foi. *This policy is drawn up in French and in English; both versions are equally authoritative.*
