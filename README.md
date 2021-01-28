# FMS

Ce projet est à destination d'un machine fonctionnant sous Ubuntu 20.04.1 LTS, 64 bits avec un version GNOME 3.36.8 et un système de fenêtrage X11.

Il est necessaire d'avoir installer :

- python3 
- java 
- postgresql

En premier, il est necessaire d'installer la base de donnée 

Toute les commandes suivante suppose que vous vous trouver dans le repertoire /FMS

[Lien vers le document d'installation de la base de donnée](/NavDB/execution.txt)
[Lien vers le document de remplissage de la base de donnée](/NavDB/install.txt)

Pour lancer le système de gestion du vol

$ chmod 777 ./run.sh
$ ./run.sh

Les fenêtres s'ouvrent, pour fermer l'integralité des fenêtres : 

$ q

dans le terminal initial.
Un nouveau terminal s'ouvre de manière à relancer le FMS.
