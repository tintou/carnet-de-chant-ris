# Carnet de Chant de Ris-Orangis
## Télécharger la dernière version
La dernière version est disponible directement [dans le git](commun.pdf)
## Compilation
Le carnet de chant doit être compilé après chaque modification, pour ce faire, il faut avoir quelques paquets d'installés :

    sudo apt install python3.5 python3-pip texlive texlive-latex-base texlive-latex-recommended texlive-latex-extra texlive-fonts-extra texlive-lang-french texlive-luatex fonts-lmodern texlive-xetex texlive-lang-french lilypond
    sudo pip3 install patacrep

Puis, pour compiler le carnet de chant :

    songbook commun.yaml

## Ajouter un chant
Pour ajouter un chant, il faut ajouter un fichier correspondant dans le répertoire `songs`, il y a déjà plein d'exemples dans le répertoire.
Lorsque le fichier est prêt, il faut l'ajouter à la liste dans `commun.yaml`
