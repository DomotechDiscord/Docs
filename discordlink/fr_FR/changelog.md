## 3.7 (15/04/2021) BETA !!!

- Ajout : Vous avez maintenant la possibilité de répondre à des ASK par un texte et non plus une réaction
- Update : Dépendance Discord.JS
- Update : Commande "Supprime les messages du channel" (Attention s'est devenu ultra puissant sa delete tous les messages des 15 derniers jours). 
- Update : Erreurs HTTP a cause du Deamon Éteint 
- Update : Version de Node JS pour correspondre au reste des plugiciels ainsi qu'à la nouvelle version de l'api Discord.JS

## 3.6 (24/02/2021)

- Mise a jours de la dependance discord. (Test pour fix les problème de reaction.)
- Mise à jour de l'affichage des commandes pour être compatible avec le core V4.1
- Mise à jour des widgets scénarios
- Mise à jour de l'affichage des commandes pour être compatible avec le core V4.2 

## 3.5.Covid (02/11/2020)

- Ajout d'une commande scénario qui permet de send les attestations Covid (Sauvgarde obligatoire des équipements)
  (Dans les settings de jeedom votre adresse doit être renseignée, et vous devez créer un user dans la page principale du plugin)

Merci à @Noodom et au discord pour la création des scénarios et l'édition du site de génération.
Lien du github du serveur qui genre les attestations : https://github.com/DomotechDiscord/Covid19

## 3.5 (20/10/2020)

- Mise à jour de icon font (Merci @Jag)
- Ajout d'une fonction pour delete les anciens messages (Messages compris entre -14 et -2 jours)
- Update des depandance

## \*\*\* (02/08/2020)

- Update lien doc
- Update repository

## 3.2.6 (31/07/2020 à 9h30)

- Mise à jour des dépendances.

## 3.2.5 (13/07/2020 à 21h37)

- Ajout d'une fonction pour les créateurs de scénarios et les développeurs.

#### discordlink::addemojy("ID Emojis","Emojis Création");

Elle permet aux développeurs de créer des émojis dans la page "Emojis Settings". Elle retourne soit l'émoji suite à la création, soit celui modifié par l'utilisateur.
Il ne nécessite que l'émoji ID. Il retournera l'émoji set à cet id ou alors des points d'interrogations en cas de création.
Le paramètre "Emojis Création" est optionnel, mais s'il est spécifié, si création de l'émoji il sera set à la valeur définie

- Migration de la "Dernière connexion de l'utilisateur" By Yasu et Jcamus86" en émoji éditable par l'utilisateur.

## 3.2.4 (04/07/2020 à 14h17)

- Correction de l'erreur 500 à la création de l'équipement

## 3.2.3 (03/07/2020 à 21h45)

- Update du system "Dernière connexion de l'utilisateur" By Yasu et Jcamus86

## 3.2.2 (03/07/2020 à 18h05)

- Nouveau système sur les invites et channels discord

## 3.2.1 (12/06/2020 à 20h11)

- Ajout de logs en mode debug pour les channels et l'invite.

## 3.2 (06/06/2020 à 16h20)

- Ajout des crons persos pour les checks
- Ajout des exclusions de node Z-Wave
- Ajout de la config de temps de check des modules Zwave
- Ajout d'une commande "Centre de messages" By jcamus86
- Ajout d'une commande "Dernière connexion de l'utilisateur" by Yasu
- Ajout de notification automatique sur la commande "Dernière connexion de l'utilisateur" by Yasu
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
