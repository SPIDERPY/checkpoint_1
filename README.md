# exercice_1
## 1-1
![capture_exercice_1_1](https://github.com/SPIDERPY/exercice_1/blob/main/Capture%20d%E2%80%99e%CC%81cran%202025-01-24%20a%CC%80%2012.26.45.png)
## 1-2
![capture_exercice_1_2](https://github.com/SPIDERPY/exercice_1/blob/main/Capture%20d%E2%80%99e%CC%81cran%202025-01-24%20a%CC%80%2012.23.21.png)

# exercice_2
![capture exercice 2](https://github.com/SPIDERPY/exercice_1/blob/main/Capture%20d%E2%80%99e%CC%81cran%202025-01-24%20a%CC%80%2014.51.43.png)

# exercice_3

1. **Donne une ligne de commande bash qui permet de lister la liste des utilisateurs d'un système Linux**

2. **Quelle commande bash permet de changer les droits du fichier myfile en rwxr-r- ?**

3. **Quelle est la différence entre une variable d'environnement et une variable locale dans un script Bash, et comment pouvez-vous les définir et les utiliser ? [Admin] - Wild Code School**

5. **Expliquez comment fonctionne la structure de contrôle "if" dans Bash. Donnez un exemple concret de son utilisation pour prendre une décision basée sur une condition dans un script Bash.**

**Structure de base** :

    if [ condition ]
        then
        # commandes à exécuter si la condition est vraie
    else
        # commandes à exécuter si la condition est fausse
    fi
**Exemple**

    #!/bin/bash

    fichier="monfichier.txt"

    if [ -e "$fichier" ]
    then
        if [ -r "$fichier" ]
        then
            echo "Le fichier existe et est lisible."
        else
            echo "Le fichier existe mais n'est pas lisible."
        fi
    else
        echo "Le fichier n'existe pas."
    fi
**Explication de l'exemple :**

    1. if [ -e "$fichier" ] : Vérifie si le fichier existe.

    2. if [ -r "$fichier" ] : Si le fichier existe, vérifie s'il est lisible.

    3. echo "Le fichier existe et est lisible." : Affiche un message si le fichier existe et est lisible.

    4. echo "Le fichier existe mais n'est pas lisible." : Affiche un message si le fichier existe mais n'est         pas lisible.

    5. echo "Le fichier n'existe pas." : Affiche un message si le fichier n'existe pas.
    
5. **Donne la (les) ligne(s) de commande(s) bash pour afficher le texte suivant :**

6. **La commande `jobs -1` donne le résultat ci-dessous**
 **Quelle commande te permet de mettre en avant le processus gedit ?**

7. **Quels matériels réseaux sont sur la couche 2 et la couche 3 du modèle OSI ? Donne leurs spécificités.**

8. **Quels sont les équivalents PowerShell des commandes bash `cd`, `cp`, `mkdir`, `ls` ?**

9. **Dans la trame Ethernet, qu'est-ce que le payload ?**

10. **Pourquoi les classes IP sont-elles remplacées par le CIDR ?**



