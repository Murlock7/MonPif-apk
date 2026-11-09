# 🍷 MonPif

Application Android pour gérer sa cave à vin : photo de l'étiquette pour reconnaître le vin (Vivino, IA Gemini),
cote estimée, période idéale de dégustation (apogée), sommelier qui propose la bouteille pour un plat,
plan de la cave avec l'emplacement de chaque bouteille, statistiques.

Projet personnel (et prétexte pour se former à l'IA), partagé en famille et entre amis.

## Télécharger

👉 **[Télécharger la dernière version (MonPif.apk)](https://github.com/Murlock7/MonPif-apk/releases/latest/download/MonPif.apk)**

Vieux téléphone (Android refuse d'installer MonPif.apk) :
[MonPif-anciens-telephones.apk](https://github.com/Murlock7/MonPif-apk/releases/latest/download/MonPif-anciens-telephones.apk).

Toutes les versions et leurs nouveautés : [Releases](https://github.com/Murlock7/MonPif-apk/releases).

## Installer (Android 9 ou plus récent)

1. Ouvrir le lien ci-dessus **sur le téléphone** et télécharger `MonPif.apk`.
2. Ouvrir le fichier téléchargé. Android demande d'**autoriser l'installation d'applications inconnues**
   pour le navigateur : accepter, revenir en arrière, puis toucher **Installer**.
3. Si Play Protect affiche « Application non vérifiée » : **Installer quand même**
   (normal pour une application qui ne vient pas du Play Store).
4. Mise à jour : télécharger la nouvelle version et l'installer par-dessus. Les données sont conservées.

> **Vous avez installé la toute première version (1.32) ?** Les versions suivantes sont signées avec une
> nouvelle clé : Android refusera de les installer par-dessus. Une seule fois : menu ⋮ → « Sauvegarde complète
> (zip) », désinstaller MonPif, installer la nouvelle version, puis menu ⋮ → « Restaurer une sauvegarde ».
> Les clés Gemini ne sont pas dans la sauvegarde : les saisir à nouveau.

## Clé Gemini (facultative)

Sans clé, l'application fonctionne : reconnaissance par Vivino et code-barres, sommelier local.
Pour la lecture des étiquettes par IA, créer **sa propre clé gratuite** sur
[Google AI Studio](https://aistudio.google.com/apikey), puis la saisir dans l'application (icône 🔑).
La clé reste chiffrée sur le téléphone.

## Bon à savoir

- Les données (cave, photos) restent sur le téléphone ; menu ⋮ → « Sauvegarde complète (zip) » pour les mettre à l'abri.
- Usage personnel uniquement. Ce dépôt ne contient que l'application à installer.
