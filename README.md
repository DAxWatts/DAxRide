# DAx RIDE

Application Windows pour rouler sur home trainer, suivre ses entraînements et regarder ses contenus avec les données de séance visibles.

## Télécharger

Les installateurs seront disponibles dans [Releases](https://github.com/DAxWatts/DAxRide/releases). Tant qu’aucune version n’est publiée, aucun téléchargement n’apparaît.

1. Télécharger l’archive `DAxRIDE-Setup-x.y.z.zip` de la version souhaitée.
2. Installer au préalable **.NET 10 Desktop Runtime** et **Microsoft Edge WebView2 Runtime** s’ils sont absents du PC.
3. Extraire entièrement l’archive dans un dossier.
4. Fermer DAx RIDE, puis lancer `DAxRIDE-Setup.exe`.
5. Lancer DAx RIDE depuis le raccourci Bureau ou le menu Démarrer et créer son profil.

[.NET Desktop Runtime pour Windows](https://dotnet.microsoft.com/download/dotnet/10.0) · [Microsoft Edge WebView2 Runtime](https://developer.microsoft.com/microsoft-edge/webview2/)

Windows 10/11. Installation pour le compte Windows, sans administrateur. La version actuelle n’est pas signée par un certificat d’éditeur. Le fichier SHA-256 permet de vérifier l’intégrité de l’archive et ne constitue pas une signature d’éditeur.

## Fonctionnalités

- Puissance affichée sur trois secondes, cadence, vitesse, distance, transmission et pente.
- Séances enregistrées, pause/reprise et historique.
- Mode cassette classique ou transmission virtuelle avec Zwift Cog / Zwift Ride.
- KICKR CORE et Elite Suito T : configurations testées pendant le développement. La compatibilité avec tous les modèles et firmwares n’est pas garantie.
- Commandes Zwift Click V2 et Zwift Ride ; certaines configurations Ride nécessitent une connexion à un compte Zwift pour autoriser les commandes.
- Parcours GPX avec variation automatique de pente et entraînements Intervals.icu guidés. Pas de pilotage ERG : la pente reste ajustée par le cycliste hors parcours automatique.
- Envoi des séances vers Strava et Intervals.icu, export TCX.
- Espace Média, mode cinéma immersif et compteurs détachés transparents. La lecture des plateformes dépend de leurs protections, de la compatibilité du navigateur intégré et des abonnements.

## Mises à jour

Le bouton **Mises à jour** de DAx RIDE vérifie les versions stables publiées ici et propose le téléchargement de l’installateur. Après téléchargement, terminer la séance et fermer l’application avant installation. Les profils, séances et connexions stockés dans `%LOCALAPPDATA%/RideControl` sont conservés.

La puissance et la cadence proviennent du home trainer. En transmission virtuelle, vitesse et distance sont des estimations de simulation ; en mode cassette, la vitesse est issue du home trainer.

## Signaler un problème

Utiliser les [Issues](https://github.com/DAxWatts/DAxRide/issues) en indiquant la version de DAx RIDE, Windows, le modèle du trainer et les étapes pour reproduire le problème. Ne pas joindre de mots de passe, clés API, jetons de connexion ou captures contenant des données personnelles.

Ce dépôt contient les informations et versions distribuées. Le code source est conservé dans un dépôt privé. Les mentions des composants tiers sont incluses dans l’application.
