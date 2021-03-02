# L'application est publique.

Lien de l'APK version Android : [Vive L'APK ANDROID](https://jeemate.les2t.fr/)

Pour les personnes sous iOS, la version de l'app devrait arriver d'ici 1 mois ou 2.<br>

Cordialement
Thibaut Et Pascal
   
   
   


Plugin officiel de l'application JeeMate sur Android.
Et dans le Futur sur Android TV et iOS

![JeeMate Icon](../images/jeemate_icon.png)

Ce plugin permet d'appairer JeeMate avec votre serveur JeeMate, très facilement en seulement quelques clics. Afin de créer un équipement virtuel qui vous permettra, via l'application, d'envoyer et recevoir des notifications,  et déclencher des événements basés sur la géolocalisation de votre appareil.

Présentation de l'application
==============================

JeeMate est une application mobile compatible avec Jeedom.<br/>Contrôlez facilement votre maison intelligente grâce à son interface intuitive et customisable.<br/>JeeMate dispose de nombreuses fonctionnalités, et est compatible avec de nombreux plugins Jeedom.<br/>JeeMate utilise les types génériques de Jeedom.

Sentez-vous toujours proche de chez vous!
Depuis n'importe où, vous pourrez :
- Interagir avec votre maison intelligente
- Monitorer et contrôler vos équipements
- Recevoir et répondre aux notifications PUSH, textes, images et/ou vocales.
- Gérer la présence et automatiser des actions en fonction de votre localisation
- Visualiser vos caméras, ou streams externes en Live
- Visualiser l'historique de vos équipements si préalablement activés dans Jeedom
- Envoyer des commandes vocales à votre serveur Jeedom, sans passer par les serveurs Cloud, avec écoute en continue ou non, et hotword custom
- Utiliser l'application en mode tablette de contrôle à la maison, et utiliser des fonctions d'intelligence artificielles de la caméra
- Envoyer et recevoir des sms
- etc.

Grâce à son interface customisable, vous pourrez aussi :
- Définir des équipements et scènes favoris
- Filtrer l'affichage dans vos Favoris et Pièces, par types
- Réorganiser l'ordre d'affichage
- Customiser vos widgets
- Customiser l'affichage global ou par pièces
- Customiser certaines parties de l'interface
- Changer complètement l'interface, grâce aux différents thèmes ainsi que leurs variantes Jour/Nuit aka "Light/dark"
- Sécuriser l'accès à chaque équipement! Grâce à un digicode ou la reconnaissance biométrique (faciale ou empreinte digitale)
- Afficher vos designs Jeedom et autres pages favorites, comme des pages persos Grafana ou autres
- Ou encore créer des scénarios grâce à son éditeur.
- etc.

L'application mobile et son plugin ont été développés avec comme objectifs principaux :
- "mobile-first" afin de réduire la dépendance à un autre périphérique tel qu'un ordinateur que ce soit pour le rendu dans l'application mobile et d'autres tâches quotidiennes
- contrôler votre maison intelligente le plus simplement possible, avec le moins d'étapes tout en ayant de nombreuses possibilités de customisation
- réduire le nombre de plugins utilisés et les ressources de votre serveur Jeedom
- réduire le nombre d'applications mobiles utilisées et les ressources de votre équipement

JeeMate gère aussi les droits utilisateurs et mots de passe Jeedom sur les commandes, préalablement définis dans votre Jeedom.

**Note: L'utilisation continue du GPS en tâche de fond peut réduire la durée de vie de la batterie. JeeMate contient des paramètres afin d'optimiser ceci (cf doc ci-dessous)**

JeeMate est une application Freemium. Il est ainsi possible d'utiliser de nombreuses fonctions de base gratuitement. Il est possible d'acheter la version Premium et de supporter le développement du projet, afin de bénéficier de toutes les fonctionnalités.


Fonctionnalités
==============================

Découvrez ci-dessous toutes les différences entre les versions Free et Premium.

(Liste non représentative de la lise finale)

| JeeMate                                  | Free     | Premium  |
| ---------------------------------------- | -------- | -------- |
| Nombre d'équipements connectés en simultané | Illimité | Illimité |
| Service de géolocalisation               | Oui      | Oui      |
| Tri des objets et des équipements        | Oui      | Oui      |
| Envoi de notifications PUSH              | Oui      | Oui      |
| Récupération de l'état des équipements   | Oui      | Oui      |
| Contrôle des équipements ON/OFF          | Oui      | Oui      |
| Contrôle des équipements avec variateur  | Oui      | Oui      |
| Création de favoris                      | Oui      | Oui      |
| Recherche d'équipements                  | Oui      | Oui      |
| Timeline                                 | Oui      | Oui      |
| Synthèse                                 | Non      | Oui      |
| Service de GeoFencing                    | Non      | Oui      |
| Service de Camera ML                     | Non      | Oui      |
| Service de géolocalisation               | Non      | Oui      |
| Service de Reconnaissance Vocale          | Non      | Oui      |
| Service d'envoi de SMS                   | Non      | Oui      |
| Service SIP                              | Non      | Oui      |
| Création de Groupes                      | Non      | Oui      |
| Onglet Pièces                            | Non      | Oui      |
| Onglet Cameras                           | Non      | Oui      |
| (FUTUR) Widget : Favoris                 | Non      | Oui      |
| (FUTUR) Widget : Scénarios               | Non      | Oui      |
| Serveurs max paramétrés en simultané     | 1        | Illimité |
| Soutien pour les développements futurs   | Non      | Oui ! <3 |


Compatibilité avec Jeedom
==============================

JeeMate gère les types génériques définis dans JEEDOM et plus!
Pour qu'un équipement apparaisse dans JeeMate, l'équipement doit être visible et avec des types génériques configurés sur ses commandes.

[Plus d'informations sur les types génériques.](https://www.jeedom.com/blog/3327-application-mobile-les-types-generiques/)

Dans certains cas, JeeMate va aussi au-delà des types génériques en rendant compatibles certains plugins.
JeeMate gère certains plugins Jeedom Officiels, ainsi que d'autres développés par la communauté.


Compatibilité avec les plugins Jeedom
==============================

| Nom du plugin   | Compatible ?                      |
| --------------- | --------------------------------- |
| Alarme          | Oui                               |
| Caméra          | Oui                               |
| FreeboxTelec    | Oui                               |
| Interactions    | Oui                               |
| JMQTT           | Oui                               |
| Mode            | Oui                               |
| Thermostat      | Oui                               |
| Virtuel         | Oui                               |
| Weather         | Oui                               |
| Weatherbit      | Oui                               |
| Sonos           | Oui                               |
| Squeeze         | Oui                               |
| Wifilight       | Oui                               |
| JeeRhasspy      | Oui/Intents                       |
| JeeOrangeTv     | Télécommande                      |
| AndroidTV       | Télécommandes                     |
| Squeezebox      | Dispo/En cours                    |
| Météo France    | En cours                          |
| nuki            | En cours                          |
| alexa smarthome | En cours                          |
| Pronote         | Futur                             |
| Suivi Conso     | Futur                             |


Tableau des compatibilités
==============================

TODO: Ajouter les autres types, avec plus d'informations pour la configuration.
#### Chauffage

| Type générique                  | Sous-type | Compatible ? |
| ------------------------------- | --------- | ------------ |
| Chauffage fil pilote Etat       | Info      | Oui          |
| Chauffage fil pilote Bouton     | Action    | Non          |
| Chauffage fil pilote Bouton OFF | Action    | Oui          |
| Chauffage fil pilote Bouton ON  | Action    | Oui          |

#### Généric

| Type générique                        | Sous-type | Compatible ? |
| ------------------------------------- | --------- | ------------ |
| Tous                                  | Info      | Oui          |

#### Lumière

| Type générique     | Sous-type | Compatible ? |
| ------------------ | --------- | ------------ |
| Lumière couleur    | Info      | Oui          |
| Lumière Etat       | Info      | Oui          |
| Lumière Bouton Off | Action    | Oui          |
| Lumière Bouton On  | Action    | Oui          |
| Lumière Couleur    | Action    | Oui          |
| Lumière Mode       | Action    | Oui          |
| Lumière Slider     | Action    | Oui          |
| Lumière Toggle     | Action    | Oui          |

#### Mode

| Type générique | Sous-type | Compatible ? |
| -------------- | --------- | ------------ |
| Mode Info      | Info      | Oui          |
| Mode Action    | Action    | Oui          |

#### Portail/Garage

| Type générique                  | Sous-type | Compatible ? |
| ------------------------------- | --------- | ------------ |
| Garage état ouvrant             | Info      | Oui          |
| Portail état ouvrant            | Info      | Oui          |
| Portail ou garage bouton toggle | Action    | Oui          |

#### Prise

| Type générique   | Sous-type | Compatible ? |
| ---------------- | --------- | ------------ |
| Prise Etat       | Info      | Oui          |
| Prise Bouton Off | Action    | Oui          |
| Prise Bouton On  | Action    | Oui          |
| Prise Slider     | Action    | Oui          |

#### Serrure

| Type générique        | Sous-type | Compatible ? |
| --------------------- | --------- | ------------ |
| Serrure Etat          | Info      | Oui          |
| Serrure Bouton Fermer | Action    | Oui          |
| Serrure Bouton Ouvrir | Action    | Oui          |

#### Sirène

| Type générique    | Sous-type | Compatible ? |
| ----------------- | --------- | ------------ |
| Sirène Etat       | Info      | Oui          |
| Sirène Bouton Off | Action    | Oui          |
| Sirène Bouton On  | Action    | Oui          |

#### Thermostat

| Type générique                  | Sous-type | Compatible ? |
| ------------------------------- | --------- | ------------ |
| Thermostat Température ambiante | Info      | Oui          |
| Thermostat Humidité ambiante    | Info      | Oui          |
| Thermostat Mode                 | Info      | Oui          |
| Thermostat consigne             | Action    | Oui          |
| Thermostat Mode                 | Action    | Oui          |

#### Volet

| Type générique         | Sous-type | Compatible ? |
| ---------------------- | --------- | ------------ |
| Volet BSO Etat         | Info      | Oui          |
| Volet Etat             | Info      | Oui          |
| Volet BSO Bouton Down  | Action    | Oui          |
| Volet BSO Bouton Up    | Action    | Oui          |
| Volet Bouton Descendre | Action    | Oui          |
| Volet Bouton Monter    | Action    | Oui          |
| Volet Bouton Slider    | Action    | Oui          |
| Volet Bouton Stop      | Action    | Oui          |

#### Caméra

| Type générique                  | Sous-type | Compatible ? |
| ------------------------------- | --------- | ------------ |
| Etat                            | Info      | Oui          |
| Mouvement caméra vers le bas    | Action    | Oui          |
| Mouvement caméra vers la droite | Action    | Oui          |
| Mouvement caméra vers la gauche | Action    | Oui          |
| Mouvement caméra vers le haut   | Action    | Oui          |
| Preset caméra                   | Action    | Non          |
| Stop caméra                     | Action    | Non          |
| Zoom caméra vers l'arrière      | Action    | Oui          |
| Zoom caméra vers l'avant        | Action    | Oui          |


Configuration du plugin JeeMate
==============================

Après téléchargement du plugin, vous devez commencer par l'activer.

Ensuite, vous devez **créer un équipement**. Pour cela :

1. Accéder à la page "Plugins > Communication > JeeMate"![Accès au plugin Jeedom](../images/jeemate_select_plugin.png)

2. Cliquer sur "Ajouter" pour créer votre premier appareil
   ![Ajout d'un équipement](../images/jeemate_add_device.png)

3. Entrer un nom pour votre équipement, puis cliquer sur "D'accord"

4. Par défaut, l'équipement est automatiquement activé avec la configuration adéquate :
   
   - Activé : par défaut, afin de vous épargner un clic
   - Clé API : il est préférable de laisser la valeur par défaut. Ne modifiez cette valeur que si vous souhaitez recevoir des notifications sur votre iPhone depuis 2 serveurs Jeedom. Voir section "Réception des notifications depuis 2 serveurs JEEDOM"
   - Utilisateur : permet de définir quel utilisateur se connecte à l'application
   - QRCode : le QR code qui s'affiche à la droite de la fenêtre vous permettra de configurer l'application sur votre téléphone ou tablette.

   Une fois ces étapes réalisées, vous pouvez lancer l'application JeeMate sur votre appareil.

**Note** : Pour chaque équipement créé, une liste de commandes est disponible (cf section ci-dessous)


Premier lancement de l'app JeeMate
==============================

Si ce n'est pas déjà fait, [téléchargez l'application sur votre téléphone ou tablette](https://jeemate.les2t.fr/). 
Puis :

1. Suivez les étapes proposées dans l'assistant si elles n'ont pas déjà été faites précédemment
2. Scanner le QR code présent sur l'équipement créé sur Jeedom.
3. Finaliser la création du serveur, et voilà !

**Note: JeeMate reconnaitra seulement les équipements visibles contenant des commandes avec types génériques. N'oubliez donc pas de renseigner les types génériques si ce n'est déjà fait.**


![Affichage de votre serveur](../images/jeemate_jeedom_qrcode.png)

Fonctionnalités 
==============================

JeeMate a été conçu pour être facile à utiliser

JeeMate est décomposé en quatre onglets :
- Favoris Maison
- Pièces
- Caméras
- Designs Jeedom et pages web favorites

Pour naviguer entre les onglets, il est possible soit de cliquer sur les boutons dans la barre en bas de l'application, ou alors de faire un swipe gauche/droite sur l'écran

Lorsque vous cliquez sur les boutons Pièces, ainsi que Designs, une liste apparaitra afin de sélectionner la Pièce ou le Design que vous souhaitez afficher

#### Onglets Favoris Maison

L'écran principal contient les sections suivantes :
- Barre d'outil tout en haut. Permet d'accéder au menu de JeeMate, à la reconnaissance vocale ainsi qu'aux notifications.
- Résumé global Jeedom (dépend de la configuration des résumés dans Jeedom) ainsi que l'affichage des membres présents si configurés dans votre Jeedom (un clic sur l'icone permet d'afficher la liste des membres et leur statut).
- Widgets Spéciaux liés à certains plugins Jeedom (Météo, Télécommandes, Thermostat, Alarme, Volets, Modes)
- Scénarios favoris
- Equipements et applications Android favoris

Les plugins sont automatiquempent paramétrés lors de la synchronisation de l'interface.

**Ajout de favori**

Pour ajouter un favori (Equipements, Scénarios, Groupes, Appli Android), cliquez sur le bouton "+" correspondant à la section, sur la gauche de l'écran
Pour filter, les favoris par type d'équipement, cliquez sur l'icone "Filtre", sur la droite de l'écran

**Contrôle d'un équipement**

- Pour contrôler un équipement ou lancer un scénario, il suffit de faire un clic sur l'élément.
Pour un équipement simple, comme par exemple ON/OFF, l'action sera immédiatement envoyée.
Pour un équipement contenant plusieurs commandes, ou historiques, cela affichera une page avec des contrôles complémentaires.

Note: Si un mot de passe a été défini sur la commande à exécuter dans Jeedom, alors il vous sera demandé à l'aide d'un digicode ou du fingerprint.

- Pour afficher le menu de réglages Customisation Tile, double cliquez sur l'équipement. Vous pourrez ainsi choisir de la verrouiller, ainsi que changer son widget.

- Pour réorganiser l'ordre d'affichage, appuyez quelques secondes sur l'équipement et déplacez la tuile à l'endroit souhaité.

En fonction de l'équipement, plusieurs pages différentes peuvent apparaitre :

* Allumer
* Éteindre
* Lumières (Intensité, couleur)
* Thermostats
* Volets
* Etc.

#### Onglet Pièces 
L'écran contient trois sections:
- Scénarios
- Equipements
- Caméras

Il est possible de customiser l'affichage pour chaque pièce en cliquant sur l'icone d'édition en haut à droite dans la barre d'outils JeeMate
Il sera alors possible de :
- Renommer la pièce
- Choisir une image de fond
- Choisir une couleur de fond
- Utiliser le thème par défaut
Ainsi que de configurer certains paramètres pour vos équipements, comme:
- rendre visible ou non
- ajouter aux Favoris Maison
- sécuriser par digicode ou reconnaissance biométrique

#### Onglet Caméras

L'onglet Caméras permet de visualiser toutes les caméras disponibles dans Jeedom ou non.

Cliquer sur le bouton "+" pour ajouter une caméra puis :
- saisir un nom
- et son url

La caméra apparaitra alors dans JeeMate. Vous pourrez ensuite rééditer ses paramètres, ou bien la supprimer, en cliquant sur son icone "Roue crantée"

#### Designs Jeedom et pages web favorites
Cet onglet permet d'afficher des pages web. Telles que:
- Designs Jeedom
- Vos dashboards Grafana préférés
- etc

Pour cela, il suffit de cliquer sur le bouton Onglet "Design" dans la barre en bas, puis sur l'icone "Roue crantée".

Dans la page "Liste des designs", il est possible de :
- Ajouter un design
- Choisir d'afficher le design par défaut au démarrage de JeeMate
- Trier par ordre alphabétique les designs de la modale de sélection
- Changer l'ordre des designs, de la même manière que les tuiles en appuyant pendant quelques secondes sur le design puis déplacer
- Editer la configuration d'un design en cliquant dessus

Pour ajouter un "design" ou url vers une page web, il suffit de cliquer sur le bouton "+", puis
- Visible : si vous souhaitez cacher ou non le design dans la modale de sélection
- Defaut : pour définir le design par défaut à afficher lorsque l'on clique sur le bouton Onglet "Design"
- Saisir un nom
- Saisir son url
- La fréquence de rafraichissement si besoin

#### Menu JeeMate
Accessible depuis le bouton Menu, dans la barre d'outils JeeMate, en haut, il permet :
- d'afficher la page Synthèse Jeedom
- d'afficher la page Timeline de Jeedom
- de créer des scénarios
- de configurer JeeMate

Nous allons tout d'abord explorer les paramètres de configuration JeeMate, puis la création de scénarios.

Configuration 
==============================
Le menu "Configuration" permet de paramétrer :
- les notifications avec TTS ou non
- la géolocalisation (Activer, définir des zones, affiner les réglages pour le géofencing et la durée de la batterie)
- le lien JeeMate<->Jeedom. Ici rien à configurer. Mais ce menu permet de synchroniser JeeMate avec votre serveur Jeedom et de mettre à jour de nouveaux équipements. Il permet sinon, de réapparairer votre téléphone, ou bien de remettre à zéro l'interface graphique
- Activer la détection d'objet de la caméra de votre appareil et plus tard envoyer la vidéo vers Jeedom
- Activer le service SMS pour recevoir ou envoyer des SMS, avec gestion d'une liste blanche des contacts
- Activer le service SIP. Pour l'instant testé uniquement avec Asterisk. Sert à communiquer en audio+vidéo avec par exemple des portiers vidéos, softphones etc
- Sécurité (Activer ou non les biométriques, digicode etc). Afin d'empêcher que quelqu'un d'autre n'utilise JeeMate.
- Thèmes&Langues. Entre autres, afficher une image, ou des dégradés de couleurs, en fond d'écran, activer le thème jour/nuit, choisir les fonds d'écran pour chaque mode etc
- Sauver/Importer App. Permet de sauvegarder la configuration, les favoris, pièces etc de JeeMate dans votre serveur Jeedom. Importer permet donc de réimporter une sauvegarde.


## Notifications

- Notifications : Active/désactive l'envoi depuis Jeedom des notifications PUSH
- Notifications TTS : Active/désactive la lecture vocale de la notification PUSH

## Géoloc
- Activer/Désactiver la géolocalisation
- Définir des zones principales et secondaires.
- Définir la précision de la localisation 
- Intervalle capteur en secondes : permet de paramétrer l'intervalle de lecture du capteur GPS de votre appareil
- Distance détection en mètres : permet de définir à partir de combien de mètres la lecture du capteur GPS doit se faire

## Connecteur Jeedom
- Activer/Désactiver la connexion avec votre serveur Jeedom
- Paramètres de connexion à votre serveur Jeedom (adresse interne, externe etc) récupérés lors du scan de qrcode
- Scanner le QR Code : permet de rescanner le QR Code de votre équipement dans le plugin JeeMate et ainsi mettre à jour la configuration ci-dessus
- Effacer les favoris : permet de réinitialiser l'affichage des favoris dans l'onglet Maison
- Effacer l'interface : permet de réinitialiser complètement l'interface
- Tester la connection : permet de tester la connexion entre l'application mobile et votre serveur Jeedom

## Caméra
- Streaming (pas encore disponible)
- Activer la reconnaissance d'objets
- La précision de la reconnaissance (score mini)

## Reconnaissance vocale
JeeMate permet de contrôler votre Jeedom, en mode offline. C'est-à-dire que la reconnaissance du hotword ainsi que la transcription de la voix en texte est faite sur votre appareil, et ne passe pas par le Cloud.

Rappel: pour cela, il suffit de cliquer sur l'icone micro en haut à droite dans JeeMate.

- Interactions : si l'option est activée, la commande vocale est envoyée aux Interactions Jeedom
- Rhasspy plugin : si l'option est activée, la commande vocale est envoyée à Rhasspy
- Toujours active : si l'option est activée, l'appareil reste en permanence sur écoute, en attente d'une commande. Dans ce mode, la configuration d'un hotword est obligatoire
- Hotword : la phrase clé que vous souhaitez pour valider une commande. Exemple: "Jasper", "Dis Toto" etc

Plus d'info concernant les commandes de pilotage, plus loin ci-dessous

## Service SMS
- Autoriser ou non l'envoi de SMS depuis Jeedom
- Autoriser ou non la réception de SMS
- Interactions : si l'option est activée, le contenu du SMS est envoyé aux Interactions Jeedom
- Rhasspy plugin : si l'option est activée, le contenu du SMS est envoyé au plugin Rhasspy
- Liste blanche permet d'ajouter des contacts autorisés. Tout SMS, envoyé par un contact non présent dans cette liste blanche, ne sera pas transmis à Jeedom

Plus d'info concernant les commandes de pilotage, plus loin ci-dessous

## Service SIP
- Paramètres de connexion à Asterisk

## Sécurité
- Activer biométriques : permet d'activer la reconnaissance sur empreinte digitale, ou faciale
- Activer digicode : permet d'activer l'utilisation d'un digicode
- Digicode : saisir le code souhaité
- Sécuriser lancement JeeMate : permet de sécuriser le lancement de l'app avec une des options ci-dessus

## Thème
- Choix de la langue. Pour l'instant les langues disponibles sont Français et Anglais, bientôt Espagnol. D'autres seront ajoutées.
- Activer/désactiver Image de fond pour l'onglet Favoris Maison
- Choix de l'image de fond pour l'onglet Favoris Maison
- Activer/Désactiver le changement automatique de thème Jour/Nuit
- Choix du Dégradé pour le thème Jour
- Choix du Dégradé pour le thème Nuit
- Sous-thème pour les pages de Widgets : Morphic ou Glass

## Sauver/Importer App
- Sauvegarder : permet d'enregistrer toute la configuration de votre application mobile, paramètres et interface, dans votre serveur Jeedom
- Restaurer : permet de récupérer dans votre serveur Jeedom la sauvegarde de votre application mobile


Les commandes Infos/Actions disponibles dans un équipement JeeMate
==============================

## Notifications

| Nom                             | Sous-type | Description     |
| ------------------------------- | --------- | ------------    |
| Notification                    | Message   | Permet d'envoyer à votre JeeMate des notifications PUSH |
| State                           | Info      | Etat. Si les notifications sont actives ou non          |
| Turn On                         | Action    | Active les notifications PUSH                           |
| Turn Off                        | Action    | Désactive les  notifications PUSH                       |

## Capteurs disponibles sur votre appareil JeeMate

| Nom                             | Sous-type | Description     |
| ------------------------------- | --------- | ------------    |
| State Lux Sensor                | Info      | Luminosité (en Lux) détectée par votre appareil JeeMate |
| State Battery                   | Info      | Niveau de batterie de votre appareil JeeMate            |
| State Signal                    | Info      | Qualité de réception (en dB)  de votre appareil JeeMate |
| IP JeeMate                           | Info      | Addresse IP de votre appareil JeeMate              |
| Charging State                  | Info      | Statut de charge de l'appareil                          |
| Geoloc Position                      | Info      | Position GPS de votre appareil                          |
| (geoloc) geofence                    | Info      | Une info binaire par zone                               |
| (geoloc) Distance de geofence        | Info      | Distance en mètres depuis votre position à la bordure de la zone  |
| (geoloc) Distance de geofence Centre | Info      | Distance en mètres depuis votre position jusqu'au centre de la zone  |
| Reconnaissance Objets           | Info      | Pour la détection d'objets                              |

## Send SMS

Send SMS est une commande de type message que vous pouvez utiliser depuis votre serveur Jeedom, par exemple dans les scénarios, afin d'envoyer un SMS depuis l'application mobile JeeMate.

| Paramètre | Valeur      |
| --------- | ---------   | 
| Titre     | N° téléphone destinataire    |
| Message   | Le message à envoyer    |

## TTS Speak

TTS Speak est une commande de type message que vous pouvez utiliser depuis votre serveur Jeedom, par exemple dans les scénarios, afin de faire parler l'application mobile JeeMate.

| Paramètre | Valeur      |
| --------- | ---------   | 
| Message   | Le message à envoyer    |

## Send Action

Send Action est une commande de type message que vous pouvez utiliser depuis votre serveur Jeedom, par exemple dans les scénarios, afin d'envoyer une commande spéciale à l'application mobile JeeMate.

| Nom de la commande à renseigner | Description | Paramètres      |
| ------------------------------- | ---------   | ------------    |
| TODO doc API JeeMAte            | ---------   | ------------    |



Questions fréquentes
=
