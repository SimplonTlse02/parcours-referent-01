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

Referencement 
==
Principales notions pr améliorer son référencement et avec quels outils le mesurer?

Notion de WebMarketing
* Le visiteur a 3 comportements:
il cherche, besoin de référencement, il participe, utilité des réseaux sociaux, il surfe, d’où le display, et que l’on éveille son intérêt.

Comment se réalise le positionnement:
* Google tient 90% du marché
Un moteur de recherche réalise un « crawling », puis analyse la page, la lis ou ne peut pas la lire, l’index, et traite les requêtes.
À retenir que les méthodes, les algorithmes évoluent tout le temps. 

Donc, dans les 10 er résultats GOOGLE, sont tenus en compte la PERTINENCE et la NOTORIETE

* La notoriete 
Page dont les gens parlent, ou l’importance des liens entrants ou « backlinks »
Les « backlinks » sont placés dans un article, dans le texte, pas dans le footer par exemple!

* Un « mot-clé » est un ensemble de mot, pas juste un mot.
À savoir qu’il est tapé en moyenne 4 mots en recherche sur G.
Ils peuvent être acheter sur AdWords

* Le « Net-linking » ou obtenir des liens : 
en commentant sur un site généraliste, annuaire, blog, réseaux, sociaux
Ainsi on obtient une note de G : le « PAGE RANK » cette note est donné page par page !  et pas par site. 

* La pertinence
Ou la bonne réponse posé par l'internaute.
D’où l’obligation de définir 1 mot-clé principal, associé à une page.

SEO - Search Engine Optimization
Importance de:
mot-clé, contenu, accueil des visiteurs
optimisation technique du site
Contenant, G est une librairie
ergonomie
un contenu unique

Donc pertinence et notoriété : 
meilleur réponse, contenant, mot-clé, contenu

CONCLUSION
==
Mot-clé très important, le principal est à définir, et les secondaires.
Les placer selon de façon à optimiser, du titre, de la métadescription, hiérarchiser les titres dans les balisesLes lister
Analyse recherche des internautes
Concurrence
Pertinence > Bonne réponse, mot-clé et comportement visiteur
Notoriété > Qui parle de moi


Outils
==

Adwords   
Outil de planification de mot-clé   
Google Analytics    
Google Webmaster Tools    
Google Page Speed    
Google Trends    
semrush.com : consultable pr 2, 3 recherches / Jour   

Sources
==

Les 3 plus plébiscités. (Source Journal du Net, Mars 2016):

https://ahrefs.com > analyse des backlink reconnu   
https://fr.majestic.com >  outil préféré des SEO pour les indépendants, dont les developpeurs   
http://www.seobserver.com   

SEO pr Linux : http://www.advancedwebranking.com/download.html   
http://www.positeo.com   
http://www.allorank.com  
http://www.ranks.fr/fr/outil-backlinks  
http://socialcrawlytics.com  > état des lieux de l'activité sociale des pages d'un site web en prenant en compte les différents types de partages : Facebook, Twitter, Pinterest   
http://www.netstorming.fr  > boite à outil du SEO accessible sur une seule page   
http://peacockmedia.co.uk/integrity/   

Sécuriser son WordPress, notions.    
==

En 1er lieu, faire des MAJ régulières.   
Protégez sa page de connexion cad wp-login.php  
	> Avec les plugin « Login Lockdown », ou « WordFence »   
Ne pas utiliser « admin » comme nom d’utilisateur    
Choisir des mots de passe complexes   
	> générateur de mot de passe:  
	strongpasswordgenerator.com   
Protégez ses fichiers .htaccess    
	> depuis votre client FTP (Filezilla par exemple), ou avec le plugin WordPress SEO By Yoast, ou encore en suivant le tuto de -wpmarmite- (source)  
Sécurisez wp-includes   
	> ds le meme fichier .htaccess, ajouter un extrait du Codex WP (source -incremys-)  
Masquez votre version de WordPress   
Empéchez l’accès à son répertoire de fichiers  
Utilisez les bonnes permissions pour vos dossiers et fichiers pr mieux sécuriser WP   
Limitez le hotlinking de vos images  
Scannez son site, ou solution complète de nettoyage   
	> CodeGuard   
	> Sucuri  
	> Theme Authenticity Checker   
Utilisez une connexion SFTP plutôt que FTP  
Empechez ds utilisateurs fictifs de spammer votre site de membres   
Sauvegardez régulièrement son site:  
	> UpdraftPlus  
	> VaultPress  
	> BackUpBuddy  
	> WordPressBackup to Dropbox   

Conclusion
==
En somme, on peut sécuriser son site WP de l’installation, la MAJ, utilisateurs, plugins, thèmes, verrouiller l’éditeur de code, éviter les pièges du fichier wp-config, erreur de login.  

	> Tout les détails techniques pr effectuer ses étapes:  
	http://korben.info/securiser-wordpress-installation.html

Sources :  
http://www.incremys.com/securiser-wordpress-comment-renforcer-securite-site-wordpress/     
http://wpmarmite.com/htaccess-wordpress/

