# Imperium Clan

Welcome to Pack Imperium Symfony  VS Code Extension Pack

Un package Extension pour développer sous Symfony 3,4 & 5

This is package extension For Work Symfony :

Symfony: le nécessaire au développemnt pour Symfony quelque soit sa version.
Docker, Git, git lens, git Graph, IntelliSense Debuggeur...
Pack extension CSS, HTML, PHP, PHPUnit TestResolver...
Des outils pour le JavaScript, le Json...
color Manager, colorfulComment...
Npm
markdownlint
PHPUnit Test Explorer


Pour le réglage de base des extension du pack, ce référer à l'extension elle même.

Réglage particulier:

Réglage de php-cs-fixer pour VisualStudio Code

 0. Afficher la palette de commande et tapez  : settings.json
 1. Dans la barre de recherche : indiquer php-cs-fixer
 2. Ouvrir le settings.json>php-cs-fixer.rules et rajouter les lignes suivantes:

     1. "php-cs-fixer.autoFixBySemicolon": true
     2. "php-cs-fixer.documentFormattingProvider": true
     3. "php-cs-fixer.executablePath": "C:\\phpTools\\php-cs-fixer-v2.phar"
     4. "php-cs-fixer.executablePathWindows": "C:\\phpTools\\php-cs-fixer.bat"
     5. "php-cs-fixer.formatHtml": true,
     6. "php-cs-fixer.onsave": true,
     7. "[php]": {
                   "editor.defaultFormatter": "junstyle.php-cs-fixer"
                   },
     8. "php-cs-fixer.rules": "@Symfony"

Enjoy