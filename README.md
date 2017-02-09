Sublime Text 3 Settings
=======================

Backup of my own Sublime Text 3 settings.  
This repo allows you to quickly install a fully configured Sublime Text 3 with:

 - the awesome [Package Control](https://github.com/wbond/sublime_package_control) 
 - the [AfterGlow](https://github.com/YabataDesign/afterglow-theme) theme

Windows
-------

    cd %APPDATA%/Sublime Text 3
    git init
    git remote add origin git@github.com:joffroy59/st3-settings.git
    git fetch
    git checkout -t origin/master

Linux
-----

    cd ~/.config/sublime-text-3
    git init
    git remote add origin git@github.com:joffroy59/st3-settings.git
    git fetch
    git checkout -t origin/master

OS X
----

    cd ~/Library/Application Support/Sublime Text 3
    git init
    git remote add origin git@github.com:joffroy59/st3-settings.git
    git fetch
    git checkout -t origin/master

INITIALISATION
----

    git remote add origin git@github.com:joffroy59/st3-settings.git
    git add --all
    git commit -m "Ma sauvegarde Sublime Text 3"
    git push origin master
