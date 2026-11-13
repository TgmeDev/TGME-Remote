# TGME Remote

Assistance de postes Windows à distance avec un serveur hébergé sur un NAS Synology. **Version publiée : 1.0.0-0456.**

[Site de présentation](https://tgmedev.github.io/TGME-Remote/) · [Guide Synology](https://tgmedev.github.io/TGME-Remote/guide-complet.html) · [Tutoriel application et serveur NAS](tutoriel-application.html) · [Télécharger le SPK 0456](https://github.com/TgmeDev/TGME-Remote/releases/download/1.0.0-0456/TGMERemoteServer-1.0.0-0456.spk) · [Détails de la Release 0456](https://github.com/TgmeDev/TGME-Remote/releases/tag/1.0.0-0456) · [Historique de la Release 1.0.0-0450](https://github.com/TgmeDev/TGME-Remote/releases/tag/1.0.0-0450)

## Nouveautés de la version 1.0.0-0456

- Enregistrement local du mot de passe permanent protégé par un PIN propre au compte Technicien. Le double-clic sur un poste configuré lance le contrôle après validation du PIN.
- Transferts optimisés avec un débit d’envoi maximal relevé et une réception des outils plus rapide. Les performances réelles dépendent du réseau.
- Bibliothèques réseau Windows actualisées et nouvelles séparations entre opérations dans le compte rendu Analyse IA.

La version 1.0.0-0450 reste consultable pour son historique; son paquet n’est plus proposé au téléchargement.

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
