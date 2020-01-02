# Travail en groupe sur GitHub

La première étape est de créer un dépôt Git. Ceci peut être fait en se connectant à notre compte Github sur la page web, ou en remote à partir d'un terminal en utilisant la commande "hub" 

    hub create

Plus de détail dans la partie création d'un dépôt git.

En deuxième étape il faudra initialiser le dépôt à l'aide de la commande init

    git init

Pour se connecter à un dépôt il faut utiliser la commande remote

     git remote add nom_du_depot url_du_depot

Si le projet provient du "clonage" d'un remote existant c'est-à-dire colné à l'aide de
     git clone url_du_depot
le dépôt aura automatiquement comme nom "origin".
Pour connaître la liste des dépôts auxquel le projet est lié, il suffit d’utiliser la commande git remote sans aucun argument
    git remote
Pour ajouter, supprimer ou renommer un fichier on utilise les commandes suivantes, respectivement
    git add nom_du_fichier (ou . pour tout ajouter)
    git rm nom_du_fichier
    git mv nom_du_fichier nouveau_nom_du_fichier 
Il faudra ensuite enregistrer la modification du dépôt en faisant un "commit"
    git commit -m "commentaire bref sur action réalisée"
Cette modification pourrait être envoyée au repertoire distant avec la commande "push"
    git push nom_du_depot nom_de_la_branche
Puisque chacun est succeptible d’apporter des modifications au projet il est indispensable que tout le monde dispose en permanence du code le plus récent. Pour mettre à jour son projet à partir d'un dépôt, c'est la commande fetch qu'il faut utiliser
    git fetch nom_du_depot

