# Discord Link

## 1 ) Description

Le plugin Discord Link permet d'envoyer des messages sur son serveur Discord : 
 - Messages Classiques
 - Messages Evolués
 - Messages TTS
 - Gestion des Channels ( Salon )
 - Compatible avec les interactions de Jeedom
 - Fonction ASK
 - Fonction Envoi de Fichiers
 - Fonction Etat des Démons de Jeedom et des antenne Blea
 - Fonction Etat des Dépendances des plugins Jeedom
 - Fonction Etat du résumé global
 - Fonction Etat de résumé par Pièce / Object
 - Fonction Etat des batteries
 - Fonction Etat des communication des modules Zwave
 - Fonction Envoie des etats des deamon, dépendances et zwave si erreur
 - Personalisation des Emojys pour les résumés et les messages

Pour cela, il faut avoir son serveur Discord. <br>

## 2 ) Paramètres obligatoires : 

### Son Serveur Discord :

**Création de son serveur :** 
Dans Discord, menu de Gauche, cliquez sur + pour créer votre Serveur Discord

**Récupération de son Token :** 
 - Allez sur le lien suivant: 
 [https://discordapp.com/developers/applications/](https://discordapp.com/developers/applications/)
 
 ![Discord-Server1](../images/Discord-Server_1.PNG)
 
 Cliquez sur "New Application"
  
 ![Discord-Server2](../images/Discord-Server_2.PNG)

Vous Obtenez cette fenêtre

 ![Discord-Server3](../images/Discord-Server_3.PNG)

Entrez le nom pour votre Bot et cliquez sur "Create"

 ![Discord-Server4](../images/Discord-Server_4.PNG)

Votre Bot est créé, vous pouvez lui affecter un avatar et n'oubliez pas de sauvegarder.

 ![Discord-Server5](../images/Discord-Server_5.PNG)

Cliquez sur le menu de gauche sur "Bot" et cliquez à droite sur "Add Bot"

 ![Discord-Server6](../images/Discord-Server_6.PNG)

Cliquez sur "Yes, do it!"

 ![Discord-Server7](../images/Discord-Server_7.PNG)

Voilà, votre Bot est créé, cliquez sur "Click to Reveal Token"

 ![Discord-Server8](../images/Discord-Server_8.PNG)

Copiez-collez votre Token dans un bloc-note, vous en aurez besoin plus loin.

## 3) Configuration du Plugin
Après le téléchargement du plugin, il vous suffit de l’activer et de le configurer.
 ![Discord-Plugin1](../images/Discord-Plugin_1.PNG)
Une fois activé, il faut le configurer.

**3.1) Dépendances** 

Cette partie permet de valider et d’installer les dépendances requises au bon fonctionnement du plugin Discord Link 
 ![Discord-Plugin2](../images/Discord-Plugin_2.PNG)
Cliquez sur "Relancer" et attendre la fin de l'installation des Dépendances.
Un Statut **OK** confirme que les dépendances sont satisfaites.
> **Tip**
> 
> La mise à jour des dépendances peut prendre plus de 20 minutes selon votre matériel. La progression est affichée en temps réel et un log **discordlink_dep** est accessible.

> **Important**
> 
> La mise à jour des dépendances est normalement à effectuer seulement si le Statut est **NOK**, mais il est toutefois possible, pour régler certains problèmes, d’être appelé à refaire l’installation des dépendances.

**3.2) Configuration** 

Cette partie permet de configurer les paramètres généraux du plugin
![Discord-Plugin3](../images/Discord-Plugin_3.PNG)
Entrez votre token précédemment mis de côté dans un bloc-note
Cliquez sur **"Ajouter votre bot à votre serveur Discord"**.

Vous pouvez personaliser la phrase envoyé par votre Bot sur votre Serveur Joue à : .


N’oubliez pas de ![Discord-Plugin6](../images/Discord-Plugin_6.PNG) si vous effectuez une modification.

**3.3) Démon**

 Cette partie permet de valider l’état actuel du ou des démons et de configurer la gestion automatique de ceux-ci.
 ![Discord-Plugin4](../images/Discord-Plugin_4.PNG)
Le démon local et l’ensemble des démons déportés seront affichés avec leurs différentes informations.

-   Le **Statut** indique que le démon est actuellement en fonction.
    
-   La **Configuration** indique si la configuration du démon est valide.
    
-   Le bouton **(Re)Démarrer** permet de forcer le redémarrage du plugin, en mode normal ou de le lancer une première fois.
    
-   Le bouton **Arrête**, visible seulement si la gestion automatique est désactivée, force l’arrêt du démon.
    
-   La **Gestion automatique** permet à Jeedom de lancer automatiquement le démon au démarrage de Jeedom, ainsi que de le relancer en cas de problème.
    
-   Le **Dernier lancement** est comme son nom l’indique la date du dernier lancement connu du démon.

**3.4) Log**

Cette partie permet de choisir le niveau de log ainsi que d’en consulter le contenu.
 ![Discord-Plugin5](../images/Discord-Plugin_5.PNG)
Sélectionnez le niveau puis sauvegardez, le démon sera alors relancé avec les instructions et traces sélectionnées.

Le niveau **Debug** ou **Info** peuvent être utiles pour comprendre pourquoi le démon plante ou ne remonte pas une valeur.

> **Important**
> 
> En mode **Debug**, le démon est très verbeux, il est recommandé d’utiliser ce mode seulement si vous devez diagnostiquer un problème particulier. Il n’est pas recommandé de laisser tourner le démon en **Debug** en permanence, si on utilise une **SD-Card**. Une fois le debug terminé, il ne faut pas oublier de retourner sur un niveau moins élevé comme le niveau **Error** qui ne remonte que d’éventuelles erreurs.

## 4) Configuration des équipements
La configuration des équipements Discord Link est accessible à partir du menu plugin :

 ![Discord-Equipement1](../images/Discord-Equipement_1.png)

Ci-dessous un exemple d’une page du plugin Discord Link (présentée avec quelques équipements) :

 ![Discord-Equipement2](../images/Discord-Equipement_2.png)

**4.1) Général**
Vous retrouvez ici toute la configuration de votre équipement :

 ![Discord-Equipement3](../images/Discord-Equipement_3.png)

-   **Nom du channel** : nom de votre équipement.
    
-   **Objet parent** : indique l’objet parent auquel appartient l’équipement.
    
-   **Catégorie** : les catégories de l’équipement (il peut appartenir à plusieurs catégories).
    
-   **Activer** : permet de rendre votre équipement actif.
    
-   **Visible** : le rend visible sur le dashboard.

-   **Interactions avec Jeedom** : Pour activer les interactions avec cet équipement 

-   **Deamon Check / Dependance Check / Zwave Check** : Permet d'activer la fonction envoie des etats coché Si erreur détécté.
    
-   **Channels** : Liste des Salons présents sur votre Discord. C'est ici que vous sélectionnez le salon que vous avez créé dans votre Discord. Vous devez créer autant d'équipements que vous avez de salon.

**4.2) Commandes**
Ci-dessous, vous retrouvez la liste des commandes :

 ![Discord-Equipement4](../images/Discord-Equipement_4.png)

-   Envoi message ( Message simple )

-   Envoi message TTS ( Message lu par Discord )
    
-   Envoi message évolué ( Message Personalisable )
    
-   Envoi fichier ( Envoyer une pièce jointe ou une photo de caméra ou une vidéo)

-   Etat des démons ( Envoyer sur votre channel l'état des démons des plugins installés)

-   Etat des dépendances ( Envoyer sur votre channel l'état des dépendances des plugins installés)

-   Résumé général ( Envoyer sur votre channel l'état du résumé global de votre installation)

-   Résumé par object ( Envoyer sur votre channel l'état du résumé d'un objet de votre installation)

-   Résumé des batteries ( Envoyer sur votre channel l'état des batteries de votre installation)

-   Dernier message ( Info pour récuperer le dernier message reçu sur votre channel)

-   Avant dernier message ( Info pour récuperer l'avant-dernier message reçu sur votre channel)

-   Avant Avant dernier message (Info pour récuperer l'avant-avant-dernier message reçu sur votre channel)

Afficher : permet d’afficher la donnée sur le dashboard.

## 5) Personalisation des Emojys pour les résumés

Si vous voulez personaliser les emojys des resumés automatique allez sur "Emojy setting"

![Discord-Equipement7](../images/Discord-Plugin_7.PNG)

![Discord-Equipement8](../images/Discord-Plugin_8.PNG)

dans la colonne Verte vous mettez l'emojy que vous souhaitez, pour remettre les emojy par defaut cliquer sur "Reset Emojy"

Cliquer sur "Sauvegarder" pour prendre en compte les modifications

Cliquer sur "Retours à Discord Link" pour revenir a la page précedente.

## 6) Utilisations dans un scénario

**6.1) Envoi message**
 ![Discord-Scenario1](../images/Discord-Scenario_1.png)
Résultat sur votre discord
 ![Discord-Scenario2](../images/Discord-Scenario_2.png)

**6.2) Envoi message évolué**
 ![Discord-Scenario3](../images/Discord-Scenario_3.png)
Résultat sur votre discord
 ![Discord-Scenario4](../images/Discord-Scenario_4.png)
 
**6.3) Fonction ASK**
 ![Discord-Scenario5](../images/Discord-Scenario_5.png)
Résultat sur votre discord
 ![Discord-Scenario6](../images/Discord-Scenario_6.png)
Il vous suffit de cliquer sur la réponse dans le carré rouge

**6.4) Envoi fichier**

- Envoi d'une photo d'une Caméra
 ![Discord-Scenario7](../images/Discord-Scenario_7.png)
 Résultat sur votre discord
 
 ![Discord-Scenario8](../images/Discord-Scenario_8.png)

- Envoi d'une vidéo de 5 secondes avec l'envoi de la première image en photo

nbSnap=5 delay=0,01 title='Camera' message='Video' movie=1 sendFirstSnap=1

 ![Discord-Scenario9](../images/Discord-Scenario_9.png)
Résultat sur votre discord

 ![Discord-Scenario10](../images/Discord-Scenario_10.png)
 
 **6.5) Résumé général, Etat des démons, Etat des dépendances, Etat des batteries, Etat des modules Zwave**
 
 vous ajoutez simplement ces commandes dans un scénario:

 ![Discord-Scenario11](../images/Discord-Scenario_11.png)
 
 Résultat :
 
 ![Discord-Scenario12](../images/Discord-Scenario_12.png)
 
 ![Discord-Scenario12](../images/Discord-Scenario_13.png)
 
 ![Discord-Scenario12](../images/Discord-Scenario_14.png)
 
## 7) Astuces
**7.1) Emojys**
  
 Pour ajouter un emojy, il faut le faire en mode texte. Dans l'exemple, c'est :joy: : joy : (ne pas mettre d'espace)
 
 Liste des emojys avec leur texte :  [https://www.webfx.com/tools/emoji-cheat-sheet/](https://www.webfx.com/tools/emoji-cheat-sheet/)


**7.2) Mentionner quelqu'un dans un message**

On met la mention sur discord. On met un anti-slash devant comme ceci :

![Discord-Astuce1](../images/Discord-Astuce_1.png)

Ensuite, quand on envoie, ça doit donner un truc comme ça :
![Discord-Astuce2](../images/Discord-Astuce_2.png)

Il suffit de mettre le message qui s’affiche pour qu’il mentionne : <@195159794636685xxx>

**7.3) Articles avec des exemples**

Vous pouvez retrouver des exemples pratiques sur cet article : [https://youdom.net/2020/04/21/installer-et-configurer-jeedom-discord-link/](https://youdom.net/2020/04/21/installer-et-configurer-jeedom-discord-link/)

## Faq
A venir
