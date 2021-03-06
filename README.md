Extension "Republier une Annonce en 1 Clic"
-------------------------------------------

Nom: Republier une Annonce en 1 Clic (originellement 'Advanced Ad Management') avec modèles d'emails traduits en français

URI: http://forums.osclass.org/development/repost-an-expired-ad/

Description: Options de gestion des annonces pour la republication facile des annonces, envois automatiques d'avis d'expiration, et suppression automatique des annonces non renouvelées

Version: 1.1

Auteurs: [Jesse](http://forums.osclass.org/profile/?u=7185 "Profil sur forums.osclass.org") & [JChapman](http://forums.osclass.org/profile/?u=1728 "Profil sur forums.osclass.org")

Traducteur: [Emmanuel](http://forums.osclass.org/profile/?u=8769 "Profil sur forums.osclass.org")



Cette Extension/plugin/module permet d'envoyer automatiquement des emails de notification et de rappel aux annonceurs quelques jours avant que leurs annonces arrivent à expiration. L'e-mail contient un lien qui permet à l'annoncer de republier son annonce en 1 clic. 

De plus, un autre e-mail est envoyé si l'annonceur n'a pas donné suite au 1er e-mail, et que son annonce est donc arrivée à échéance. Ce 2ème et dernier e-mail de rappel contient aussi un lien qui permet de republier en dernière chance l'annonce en 1 clic. 

_Et si une annonce n'a pas été republiée?_ 

Une telle annonce arrivée à échéance et donc expirée est automatiquement supprimée après **`n`** jours 
par le système de traitement des tâches d'Osclass (c.f. [cron Osclass [english]](http://doc.osclass.org/Cron)) 
avec ce nombre de jours **`n`** à choix dans les réglages de l'extension.


INSTRUCTIONS pour l'INSTALLATION
================================

+ [Téléchargez cette extension](https://github.com/emanwebdev/Advanced-Ad-Management/archive/fr_FR.zip) en cliquant à droite sur [le bouton **Download ZIP**](https://github.com/emanwebdev/Advanced-Ad-Management/archive/fr_FR.zip)

+ Unzip'it. Vous obtenez un dossier/répertoire nommé `advanced_ad_management`

+ Copiez le, ainsi que tout son contenu, dans `/oc-content/plugins/` sur votre site/machine/hébergeur

+ Rendez-vous dans le Tableau de Bord de votre installation Osclass, dans le menu Gérer les extensions

+ L'extension/plugin Republier une Annonce en 1 Clic est prête à être installée et à commencer à faire son travail 
automatiquement en arrière-plan ([cron Osclass](http://doc.osclass.org/Cron), chaque jour)

+ Les différentes options sont explicites. Il y a un menu FAQ / Aide.

+ Si vous voulez modifier le texte des emails envoyés, rendez-vous dans Paramètres => Modèles d'emails, les 2 nouveaux modèles associés à cette extenson sont à la fin de la liste et se nomment `email_ad_expire` et `email_ad_expired`

+ Voilà, ça tourne


et un Grand Merci! à [JCcoder aka trains58554 pour son travail](https://github.com/trains58554/Advanced-Ad-Management/commits/master) !


Bien à vous

Emmanuel


.

.

.

.

.

.

.

.

----

Changelog

@emanwebdev 2014-03-26: Added index_FRench.php with Emails Templates translated in french.

@emanwebdev 2014-03-26: Ajouté le fichier index_FRench.php avec les modèles d'emails traduits en français.

@emanwebdev 2014-03-26: Renamed index_FRench.php to index.php to target the french community and ease the setup.

@emanwebdev 2014-03-26: Renommée en Republier une Annonce en 1 Clic au lieu de Faire Revivre une Annonce en 1 Clic

