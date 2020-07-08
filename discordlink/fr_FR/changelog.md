## 3.2.5 (BETA !!!!)
- Ajout d'une fonction pour les créateurs de scénario ou developpeur.
#### discordlink::add émojys ("ID Emojis","Emojis Création");
Elle permet aux developpeurs de créer des émojis dans la page "Emojis Settings". Elle retourne soit l'émoji suite à la création soit celui modifié par l'utilisateur.
Il nésessite que l'émoji ID. Il retournera l'émoji set à cette id ou alors des points d'interrogations en cas de création.
Le paramètre "Emojis Création" est optionel, mais si il est spécifié, si création de l'émojy il sera set à la valeur définie
- Migration du "Dernière connexion utilisateur" By Yasu et Jcamus86" en émojy éditable par l'utilisateur.

## 3.2.4 (04/07/2020 à 14h17)
- Correction de l'erreur 500 à la création de l'équipement

## 3.2.3 (03/07/2020 à 21h45)
- Update du system de "Dernière Connexion utilisateur" By Yasu et Jcamus86

## 3.2.2 (03/07/2020 à 18h05)
- Nouveaux système sur les invites et sur les channels discord

## 3.2.1 (12/06/2020 à 20h11)
- Ajout de log en mode debug pour les channels et l'invite.

## 3.2 (06/06/2020 à 16h20)
- Ajout des cron persos pour les checks
- Ajout des exclusion de node Z-Wave
- Ajout de la config de temps de check des modulules Zwave
- Ajout d'une commande "Centre de messages" By jcamus86
- Ajout d'une commande "Dernière connexion utilisateur" by Yasu
- Ajout de notification automatique sur la commande "Dernière connexion utilisateur" by Yasu
- Ajout d'un tag contenant l'id du channel dans une intéraction
- Update des interfaces
- Correction d'un message d'erreur de TimeOut


## 3.1.1 (09/05/2020 à 03h51)
- Correction des fautes d'orthographes (Merci à noodom)

## 3.1 (08/05/2020 à 15h32)
- Debug des channels contenant des emojys

## 3.0 (07/05/2020 à 22h16)
- Ajout du choix du message du jeux du BOT (Merci Alexandre)
- Ajout de l'user id sur les intéractions #userid#
- Ajout d'un résumé par Pièce / Object
- Ajout d'un résumé de l'état des batteries
- Ajout d'un résumé des derniers contacts des modules Zwave (Si le plugin est activé)
- Ajout des antennes du plugin BLEA
- Ajout du choix des émojy sur les messages préfaits
- Ajout des émojy perso sur les messages préfaits
- Ajout du reset des emojy
- Ajout des emojy personaliser dans la description des messages évolués
- Ajout Auto Send Message deamon dependance et info zwave si erreur (Configuration du Channel)
- Ajout d'info dans la page santé de jeedom
- Refonte du system de channel (Plus d'erreur si le deamon est NOK)
- Refonte du system d'invite (Auto actualisation ainsi que save de l'invite)
- Optimisation des performances

## 2.1 (26/04/2020 à 16h30)
- Debug roue infinie

## 2.0 (25/04/2020 à 21h27)
- Mise à jour du Global Summary pour prendre les resumés custom
- Mise à jour de l'API sur la dernière version stable (Node js V12 minimum)
- Optimisation des performances
- Correction d'une multitude de petits bugs

## 1.9 (20/04/2020 à 22h00)
- ASK : Correction des messages en trois exemplaires

## 1.8 (19/04/2020 à 22h30)
- ASK : Après temps maximal dépassé, le message ce delete

## 1.7 (19/04/2020 à 14h10)
- Mise à jour de l'historique de 1 message à 3 messages.
- Ajouts des informations des démons. (Pas besoin de Jeedom Link) (Merci à fx33 pour son idée)
- Ajouts des informations des dépendances.
- Ajout du Global Summary.

## xxxxx (18/04/2020 à 00h15)
- Mise à jour indésirée. Aucune modification n'a eu lieu.

## 1.6 (17/04/2020 à 12h30)
- Débug du system d'ASK
- Correction des fautes d'orthographes (Merci à noodom)

## 1.5 (16/04/2020 à 20h00)
- Mise à jour du system d'ASK (Plus de TimeOut normalement)
- Ajout de la possibilité de send des messages avec les fichiers (Commande SendFile)
- Correction des embed sur Iphone

## 1.4 (15/04/2020 à 21h00)
- Corrections des fautes d'orthographes (Merci à Domotech)

## 1.3 (15/04/2020 à 14h00)
- Corrections des fautes d'orthographes (Merci à noodom)

## 1.2 (11/04/2020 à 21h00)

- Ajout d'exception en cas de démon éteint
- Optimisation des réponses d'interaction avec Jeedom
- Ignore les messages d'autres 

## 1.1 (10/04/2020 à 22h30)

- Correction des liens des docs et ChangeLog
- Correction des tags
- Publication en stable public

## 1.0 (03/04/2020)
- Création du plugin 
