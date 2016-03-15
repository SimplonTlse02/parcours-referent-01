"JOURNAL DE BORD" 

- Environnement Linux - 
Reboot de ma machine :
Pb réinstallation WIFI, il est nécéssaire de faire un apt-get update + apt-get upgrade
puis :
sudo apt-get install linux-headers-generic
sudo apt-get install --reinstall bcmwl-kernel-source

- Configuration de THUNDERBIRD MAIL avec 2 boites mails regroupés - 
et réinstallation Package Control / EMMET pr Sublim text / de Apache le serveur

- Essai d'installation du plugin "mailpoet" de Newsletter sur mon Wordpress
mais pbs d'affichage en test non résolu.

- Reactionner réseau WIFI caché -
edit connections
choisir celui utilisé d'habitude : ex SIMPLON MIP
EDIT / MODE : et changer à Infrastructure ! SAVE
le relancer dans le choix des reseaux 
https://cloud.githubusercontent.com/assets/16001498/13570884/6c4e5814-e471-11e5-8062-c7e1e01e33c7.png >screen shot correspondant

- Config. SMTP à partir de messagerie Thunderbird / PB : les parametres essayés ne permettent pas l'envoi de mail
- Zapier : automatisation, veille sur les réseaux sociaux, mails 
- Infogram : création d infographie

WordPress Memo
==

* Présentation
WordPress est un CMS, content management system, ou système de gestion de contenu, écrit en PHP créé en 2003.
Un site Internet a besoin d'un serveur et d'une base de données pour fonctionner.
Le serveur peut être installé sur votre ordinateur pour vos tests.
L'interface d'administration permet de gérer votre site.

WordPress, écrit en PHP, langage de programmation spécialisé dans la création de sites Internet, facile à modifier, avec de nombreux plugins disponiblesdveloppés par la communauté, qui permet d'ajouter des fonctionnalités à WordPress, comme par exemple la création d'une galerie photo ou la gestion d'une newsletter.
Pour utiliser WordPress, on doit obligatoirement utilisé un serveur qui exécute le code du site web 
Il est associé à MySQL, système de base de données

* Mise en place du serveur Web
Un serveur web et la base de données peuvent s'installer sur n'importe quelle machine, même votre ordinateur personnel, tests localement, sans que votre site soit en ligne ; on parle alors d’installation « locale »
Sur Windows : WAMP, contient Apache et base de données MYSQL
Ouvrir un navigateur en indiquant http://localhost/ dans la barre d'adresse
Sur MAC : MAMP
Sur Linux : LAMP
Installation de la base de données, ou un environnement local (après avoir installé un serveur Apache sur votre ordinateur) ou bien sur un serveur dédié chez un hébergeur
interface de phpMyAdmin
Puis téléchargement des sources de WordPress.
Créer le fichier wp-config.php
choisir un titre pour votre site, définir votre nom d’utilisateur ainsi qu’un mot de passe et votre email
Wp et son interface d'administration
Interface de wp est un menu constitué de son tableau de bord avec les informations générales, le contenu qui sont les pages, les articles, les médias ainsi que les commentaires, puis les parametres du site, section ou il est possible d'ajouter des plugins, c'est à dire des modules tels que la newsletter, des statistiques de vos visiteurs … etc.

* Les publications
Les articles sont des publications régulières dépendant de l'actualité.
Les pages sont destinées à des présentations.
Le menu peut être géré automatiquement ou manuellement.
Tout type de média peut être ajouté dans une publication.

Wp est structuré entre la publication de pages et d'articles, les pages ont un contenu statique, et les articles ont un contenu d'actualité.

L'éditeur de texte permet de publier un nouvel article et de le publier, il est possible d'y ajouter un média, une image, après que celle ci ait été stocké dans la bibliothéque, un lien vers une vidéo youtube par exemple, aussi de mettre en hyperlien des mots clefs, c'est à dire de relier ses mots à une adresse web.
Il est nécéssaire aussi d'ajouter des mots clefs à chaque publication, ainsi le visiteur pourrait retrouver aisement les informations qui l'interesse. 
Un menu est l'élément essentiel de la navigation sur le site, il est possible d'organiser son menu, et de créer des sous menus.
les médias. Images, sons ou vidéos : possible d'envoyer tout type de fichier, tant que celui-ci à une taille inférieure à 2Mo

L'apparence du site est déterminée par le thème choisi.
De nouveaux thèmes peuvent être téléchargés depuis la bibliothèque officielle.
Les widgets offrent des fonctionnalités supplémentaires dans les zones périphériques de chaque page.

* Gérer un site participatif - 
Ou la gestion des commentaires laissés par les visiteurs, cela implique la modération de ceux ci.
Ou la gestion des utilisateurs, les définir en tant que : administrateur, éditeur, auteur, contributeur, abonné 

* Modifier l'apparence - 
Accès par le menu, et apparence, et il est possible de changer ses thèmes, il y en a de nombreux disponible gratuit ou payant, et au moins deux installé d'office.

* Les widgets, ou composant d'interface graphique, qui apparaitront sous forme de petit bloc sur votre site. Aller dans apparences puis Widgets, on peut les désactiver quand on le souhaite. 

* Les autres CMS:

Sous forme de blog, wiki, forum, portail ex. Joomla et Drupal, et avec différentes techniques, CMS à templates, page statique, page dynamique, stockage des données dans XML . 

Liste des CMS http://www.scriptol.fr/cms/liste.php 
Un CMS inFR https://fr.dotclear.org/
CMS.fr est un site d'information dédié aux dernières actualités des CMS et des logiciels de gestion de contenu web. http://www.cms.fr/ 
https://www.joomla.org/ 

Qq exemples de PlugIns :

Hupso Share button : partage sur les réseaux sociaux
Qtranslate : traduction
NextGenGallery : création de galeries photos

WordPress est personnalisable à l'aide de plugins. Ces modules permettent d'ajouter de nombreuses fonctionnalités.
Les plugins sont développés par la communauté.
Il existe plus de 25 000 plugins

#WordPress

* Installation, config. du serveur MAMP pour MAC
* Installation, config de WORDPRESS > fichier WordPress qd téléchargé, à placer dans le dossier à la racine! de MAMP, une fois dedans on le lance de la page MAMP et qui a un onglet " ma page web " et INSCRIPTION 
* Essai créa page WP thématique concours photos. Page avec un formulaire, plugIn "Contact Form 7", une galerie photo plugin, (si serveur local, copier le fichier telechargé et coller dans WPplugIn, il apparait alors dans la page admnin. WP) pareil pr un nouveau thème, etc.
* Tuto vidéo "les clefs pour réussir son référencement"
