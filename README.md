# TGME Remote

Assistance de postes Windows à distance avec un serveur hébergé sur un NAS Synology. **Version publiée : 1.0.0-0471.**

[Site de présentation](https://tgmedev.github.io/TGME-Remote/) · [Guide Synology](https://tgmedev.github.io/TGME-Remote/guide-complet.html) · [Tutoriel application et serveur NAS](tutoriel-application.html) · [Télécharger le SPK 0471](https://github.com/TgmeDev/TGME-Remote/releases/download/1.0.0-0471/TGMERemoteServer-1.0.0-0471.spk) · [Détails de la Release 0471](https://github.com/TgmeDev/TGME-Remote/releases/tag/1.0.0-0471) · [Historique de la Release 0458](https://github.com/TgmeDev/TGME-Remote/releases/tag/1.0.0-0458) · [Historique de la Release 0457](https://github.com/TgmeDev/TGME-Remote/releases/tag/1.0.0-0457) · [Historique de la Release 0456](https://github.com/TgmeDev/TGME-Remote/releases/tag/1.0.0-0456) · [Historique de la Release 1.0.0-0450](https://github.com/TgmeDev/TGME-Remote/releases/tag/1.0.0-0450)

## Nouveautés de la version 1.0.0-0471

- Le curseur distant reprend sa forme dans la fenêtre de contrôle, notamment les poignées de redimensionnement.
- Cadences cibles : Équilibrée 20, Fluidité 30, Netteté 40 et Faible débit 50 images/s pour VP8 hybride, VP9 hybride et Tuiles seul. La cadence réelle dépend du traitement et du réseau.
- La console d’administration ajoute une page « Charge du NAS » : activation de l’adaptation automatique, seuils CPU et réseau, capacités Internet de référence et test manuel NAS/Internet. Elle affiche aussi les sessions, les mesures actualisées et le niveau d’adaptation appliqué.
## Historique de la version 1.0.0-0458

- Ajout d’un bouton sous le champ de connexion pour enregistrer ou remplacer le mot de passe permanent du Client et son PIN personnel à six chiffres.
- La Release 0458 reste consultable, mais son SPK n’est plus proposé au téléchargement. Ses notes d’origine restent sur la [page GitHub Release](https://github.com/TgmeDev/TGME-Remote/releases/tag/1.0.0-0458).

## Historique de la version 1.0.0-0457

- Enregistrement local du mot de passe permanent protégé par un PIN du compte Technicien; double-clic sur un poste configuré pour ouvrir le contrôle après validation.
- Transferts de fichiers et réception des outils optimisés; OpenSSL 3.5.9 LTS et MsQuic 2.6.4 intégrés; compte rendu Analyse IA mieux organisé.
- Deuxième Technicien en accès de visualisation et reprise des transferts après une coupure temporaire pendant une session ouverte.

La Release 0457 reste consultable, mais son SPK n’est plus proposé au téléchargement.

## Historique de la version 1.0.0-0456

- Mot de passe permanent mémorisé localement par compte Technicien et protégé par un PIN à six chiffres; double-clic sur un poste configuré pour ouvrir le contrôle après validation.
- Transferts de fichiers et réception des outils optimisés.
- OpenSSL 3.5.9 LTS et MsQuic 2.6.4 intégrés aux applications Windows.
- Compte rendu Analyse IA mieux organisé entre opérations.
- Deuxième Technicien en accès de visualisation, avec le contrôle conservé au premier.
- Reprise des demandes de transfert après une coupure temporaire tant que la session reste ouverte.

Les Releases 0456 et 0450 restent consultables pour leur historique; leurs SPK ne sont plus proposés au téléchargement.

## Ce que comprend TGME Remote

Le serveur s’installe sur un NAS Synology. Les applications Windows Client et Technicien sont fournies par la console du NAS après l’installation. Selon le mode d’accès configuré, l’utilisateur accepte la demande d’assistance ou un accès permanent autorisé est utilisé. Le Technicien intervient depuis son propre compte.

## Licence et inscription

- La licence gratuite autorise un compte Technicien lié à un seul poste Technicien, ainsi que deux PC Clients inscrits. Le compte admin est séparé, sert à administrer le serveur et ne peut pas prendre la main.
- Pour inscrire un troisième PC Client, supprimez d’abord un poste utilisé dans la console admin. Les licences payantes définissent leurs quotas de comptes Technicien et de PC Clients.
- Les licences payantes sont permanentes et définissent le nombre de Techniciens et de PC Clients autorisés.
- Le jeton d’inscription Client est valable 30 jours pour inscrire un nouveau Client. Après expiration, les nouvelles inscriptions sont refusées ; les Clients déjà inscrits peuvent se reconnecter. Le jeton est indépendant de la licence.

## Installation

Le paquet serveur requiert DSM 7.2.2-72806 au minimum et un modèle Synology pris en charge par le Centre de paquets. Après installation, téléchargez les applications Client et Technicien depuis la console TGME Remote du NAS.

## Contenu du dépôt

Ce dépôt public contient le README, le site de présentation, le guide et la page de téléchargement. Il ne contient pas le code source de l’application. Les archives automatiques du dépôt générées par GitHub ne contiennent que ces fichiers publics du site.
