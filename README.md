# comptea2-privacy
Comptea2 Privacy Policy

Politique de Confidentialité — CompteA2
Dernière mise à jour : 19 septembre 2026

La présente politique de confidentialité décrit la manière dont l'application CompteA2 (développée par DidierBlueeyes33) collecte, utilise, stocke et protège les données des utilisateurs, en conformité avec le Règlement Général sur la Protection des Données (RGPD) et les exigences de la Google Play Console.

1. Responsable du Traitement
Application : CompteA2 — Budget & Dépenses

Développeur : DidierBlueeyes33

Contact : Pour toute question ou demande relative à vos données personnelles, vous pouvez nous contacter à l'adresse e-mail de support indiquée sur la fiche Google Play Store de l'application.

2. Données Collectées et Finalités
Dans le cadre du bon fonctionnement de l'application, les données suivantes sont collectées et traitées :

A. Identifiants Personnels
Donnée collectée : Identifiant unique d'utilisateur Firebase (UID).

Finalité : Authentification, création de compte et synchronisation multi-utilisateurs/multi-appareils des budgets.

B. Informations Financières
Données collectées : Historique des transactions (titres, montants, dates, catégories) et budgets mensuels configurés.

Finalité : Permettre le suivi budgétaire, le calcul des dépenses, la génération de graphiques et l'exportation CSV des données.

C. Traitement de la Saisie Vocale
Donnée traitée : Entrées vocales dictées par l'utilisateur.

Finalité : Utilisation de l'API native RecognizerIntent d'Android pour convertir la voix en texte (extraction du montant et de la catégorie).

Remarque : L'enregistrement audio est directement traité par le système Android. Aucune donnée vocale ou fichier audio n'est conservé ni stocké sur nos serveurs.

D. Gestion des Abonnements et Facturation
Données traitées : Statut de l'abonnement et achats in-app (Licence Pro).

Finalité : Vérification des droits d'accès aux fonctionnalités Pro via la bibliothèque officielle Google Play Billing. Les détails de paiement (cartes bancaires) sont exclusivement gérés par Google Play et ne sont jamais accessibles au développeur.

3. Stockage et Sécurité des Données
Stockage Local (Room DB) : L'ensemble de vos transactions et budgets est stocké localement sur votre appareil via une base de données interne Room.

Synchronisation Réseau (Firebase) : Pour la synchronisation multi-utilisateurs et le partage de budget, les données nécessaires sont sauvegardées sur Firebase (Firebase Auth & Cloud Firestore).

Chiffrement en transit : Toutes les données transmises entre votre appareil et nos services cloud sont chiffrées en transit en utilisant les protocoles de sécurité standard TLS/HTTPS sécurisés par Google Firebase.

4. Partage et Revente des Données
Aucune revente de données : Nous nous engageons fermement à ne jamais vendre, louer ni céder vos données personnelles ou financières à des tiers à des fins commerciales ou publicitaires.

Prestataires tiers indispensables : Les données transitent uniquement via les services d'infrastructure de Google (Google Firebase et Google Play Services) pour assurer la sécurité, l'authentification et le paiement.

5. Vos Droits et Suppression des Données (RGPD)
Conformément à la réglementation sur la protection des données personnelles (RGPD), vous disposez des droits suivants :

Droit d'accès et d'exportation : Vous pouvez consulter l'ensemble de vos données directement depuis l'application et exporter vos transactions au format CSV.

Droit à la suppression (Droit à l'oubli) : Vous pouvez demander à tout moment la suppression intégrale de vos données.

La suppression des données locales s'effectue simplement en désinstallant l'application ou en effaçant le stockage de l'application dans les réglages d'Android.

Pour demander la suppression définitive de votre compte Firebase UID et de vos données synchronisées sur Firestore, contactez-nous par e-mail ou faites-en la demande via l'option dédiée dans l'application. Vos données seront définitivement supprimées sous 30 jours.

6. Modifications de la Politique de Confidentialité
Nous nous réservons le droit de mettre à jour cette politique afin de refléter d'éventuelles évolutions légales ou techniques. Toute modification sera publiée sur cette même page avec une date de mise à jour actualisée.
