# Welcome to Pack Imperium Symfony  VS Code Extension Pack

## What's in the folder

This is package extension For Work Symfony :
Symfony: le nécessaire au développemnt pour Symfony quelque soit sa version.
Docker, Git, git lens, git Graph, IntelliSense Debuggeur...
Pack extension CSS, HTML, PHP, PHPUnit TestResolver...
Des outils pour le JavaScript, le Json...
color Manager, colorfulComment...

## Get up and running straight away

* Press `F5` to open a new window with your extension loaded.
* Open `Extensions Viewlet` and check your extensions are installed.

## Make changes

* You can relaunch the extension from the debug toolbar after making changes to the files listed above.
* You can also reload (`Ctrl+R` or `Cmd+R` on Mac) the VS Code window with your extension to load your changes.
Npm
markdownlint
PHPUnit Test Explorer

## Install your extension

* To start using your extension with Visual Studio Code copy it into the `<user home>/.vscode/extensions` folder and restart Code.
* To share your extension with the world, read on https://code.visualstudio.com/docs about publishing an extension.

Réglage de php-cs-fixer pour VisualStudio Code

 0. Afficher la palette de commande et tapez  : settings.json
 1. Dans la barre de recherche : indiquer php-cs-fixer
 2. Ouvrir le settings.json>php-cs-fixer.rules et rajouter les lignes suivantes:

     1. "php-cs-fixer.autoFixBySemicolon": true
     2. "php-cs-fixer.documentFormattingProvider": true
     3. "php-cs-fixer.executablePath": "C:\\phpTools\\php-cs-fixer-v2.phar"
     4. "php-cs-fixer.executablePathWindows": "C:\\phpTools\\php-cs-fixer.bat"
     5. "php-cs-fixer.formatHtml": true,
     6. "php-cs-fixer.onsave": true
     7.  "[php]": {
                   "editor.defaultFormatter": "junstyle.php-cs-fixer"
                   },
     8. "php-cs-fixer.rules": "@Symfony"
