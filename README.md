![alt text](https://i.ytimg.com/vi/mgBlmSIZwMU/maxresdefault.jpg)

Dernière mise à jour du wiki le 30 octobre 2020.

Cette documentation n'est pas officielle.

## Table des matières

- [À propos](#à-propos)
- [Installation](#installation)
- [Commandes](#commandes)
- [Vidéos](#vidéos)
- [Ressources](#ressources)
- [FAQ](#faq)
- [FAQ - Minecraft Loup Garou Assistant](#faq---minecraft-loup-garou-assistant)


## À propos

Le mode Loup-Garou est un mode inspiré du jeu de société [Les Loups-Garous de Thiercelieux](https://fr.wikipedia.org/wiki/Les_Loups-garous_de_Thiercelieux) reprenant son fonctionnement ainsi que sa manière d'être joué, à la seule différence qu'aucun maître du jeu n'est requis, le déroulement de chaque partie étant entièrement automatisé :

- Déroulement de la partie automatisé
- Rôles du jeu de base, et nouveaux rôles
- Utilisable sur n'importe quelle map

[Liste des rôles Loup-Garou](http://bit.ly/30lDmqw)

## Installation

[Lien vers Minecraft Loup Garou Assistant (Installation simplifié)](https://jvin042.github.io/minecraft-loup-garou-assistant)

[Lien vers le plugin LoupGarou](https://github.com/leomelki/LoupGarou)

## Commandes

`/lg roles` : Retourne la liste des rôles dans la partie  
`/lg roles set <ID> <MONTANT>` : Définit le nombre de joueurs pour un certain rôle  
`/lg addSpawn` : Ajoute un point de spawn (emplacement de joueur)  
`/lg start <PSEUDO>` : Lance la partie  
`/lg end <PSEUDO>` : Arrête une partie  
`/lg reloadConfig` : Recharge la configuration  
`/lg joinAll` : À utiliser après avoir changé les rôles

## Vidéos

- [LOUP GAROU MINECRAFT [1/4] - Présentation du logiciel Minecraft Loup Garou Assistant](https://www.youtube.com/watch?v=Ru_DVwe-xSQ)
- [LOUP GAROU MINECRAFT [2/4] - Configurer sa partie de loup garou !](https://www.youtube.com/watch?v=yzkjvO56kWs)
- [LOUP GAROU MINECRAFT [3/4] - Accès au serveur à vos amis !](https://www.youtube.com/watch?v=FEscKoGYS78)
- [LOUP GAROU MINECRAFT [4/4] - Vous avez vu le super wiki !](https://www.youtube.com/watch?v=PNbmapq6T24)

## Ressources

- [config.yml pour la map Village avec spawns prédéfinis](https://github.com/jvin042/minecraft-loup-garou-assistant/blob/master/ressources/maps/config-village.yml)
- [config.yml pour la map Medieval avec spawns prédéfinis](https://github.com/jvin042/minecraft-loup-garou-assistant/blob/master/ressources/maps/config-medieval.yml)

## FAQ

- ### Pourquoi la partie ne se lance pas ? - Le serveur me dit qu'il n'y a pas assez de points de spawn ?

Il faut taper la commande /lg start <PSEUDO> en mettant le pseudo d'un des joueurs qui sera présent dans la partie. Si cela ne fonctionne toujours pas, c'est parce qu'il n'y a pas suffisamment de rôles pour le nombre de joueurs, il doit y avoir le même nombre de rôles qu'il y aura de joueurs dans la partie. N'oubliez pas de taper /lg joinAll après avoir modifié la liste des rôles.

**Nous conseillons de modifié les rôles que depuis le fichier de config de Loup Garou les commandes de chat ne sont pas très fiables !**  

Le fichier ce situe dans plugins\LoupGarou\config.yml et modifié les rôles à votre convenance et de redémarrer votre serveur.

Vidéo explicative : [https://www.youtube.com/watch?v=yzkjvO56kWs](https://www.youtube.com/watch?v=yzkjvO56kWs)

- ### J'ai mal placés mes spawns ou je veux utiliser une nouvelle map, comment faire ?

Supprimer le fichier plugins\LoupGarou\config.yml et relancer le serveur.

- ### J'ai une erreur "an internal error occured while attempting to perform this command" que faire ?

Supprimer le fichier plugins\LoupGarou\config.yml et relancer le serveur.

- ### J'ai une erreur "Il vous faut le ressourcepack pour jouer ! (FAILED_DOWNLOAD)" que faire ?

Il suffit d'aller dans ton menu minecraft multijoueur, puis de cliquer une fois sur ton serveur, et enfin sur le bouton "Modifier", Puis tu peut sélectionner "Activé" pour l'option du ressources pack.

- ### J'ai des erreurs d'éxecution dans la console du serveur ou les plugins ne sont pas reconnu !

Vérifier que vous êtes bien sur la version de Spigot 1.15.1. 

- ### J'ai plusieurs personnes sur la même dalle que faire ?

Vous avez mal définit les spawns des joueurs, si vous utilisez les maps fournis par le mode vous avez dans la partie [Ressources](#ressources) les configs des maps avec les spawns de définit il suffit que copier le fichier de config sur votre serveur.

- ### Pourquoi je ne suis pas dans le village au départ ?

Au départ vous spawnez en dessous du village, dès que vous lancerez la partie l'ensemble des joueurs seront téléportés sur les spawns du villages.

Vous pouvez vous mettre en créative et fly jusqu'au village.

- ### Puis-je mettre plusieurs fois le même rôle dans une seule partie ?

Cela est possible pour les rôles Loup-Garou, Villageois et Chasseur. D'autres rôles peuvent aussi marcher mais n'ont pas été testés avec plusieurs joueurs ayant ce rôle dans une seule partie. C'est à vos risques et périls.

- ### Je ne peux casser aucun block sur la map, comment-faire ?

Il vous suffit de désactivé le plugin en supprimant le fichier LoupGarou.jar du dossier, d'effectuer vos modifications et de remettre le fichier LoupGarou.jar.

- ### Est-ce que je peux créer mes propres rôles ?

Le code source du Loup Garou est disponible sur le github de Leomelki il faut pour ça codé votre propre rôle et le soumettre à leomelki pour qu'il accepte. Actuellement aucun rôle n'a été accepté.

- ### Comment avoir les nouveaux rôles ?

Il faut attendre que Leomelki MAJ son plugin avec les nouveaux rôles.

## FAQ - Minecraft Loup Garou Assistant

- ### Mes amis n'arrivent pas à se connecter à mon serveur ?

    - Essayer de désactiver le pare-feu de votre ordinateur.
    - Vérifier les ports ouvert sur votre routeur.
    - Vous n'avez peut-être pas d'adresse IP publique fixe.

- ### Quelle est l'adresse IP à donner à mes amis ?
    
    Il faut donner l'adresse IP v4 publique vous pouvez l'obtenir sur ce site web :
    [https://ip.lafibre.info/](https://ip.lafibre.info/)

- ### J'ai une erreur "Error occurred during initialization of VM Could not reserve enough space"

Vous n'avez pas assez de ram sur votre ordinateur pour hébergé le serveur.
