Projet Data scientist

1/ Big Data

#Méthode 1
La méthode ".length" permet de calculer le nombre de handle présent dans la valeur "handle_twitter"

#Méthode 2
La méthode ".select" permet de sélectionner les handle dans la valeur "handle_twitter", nous précisons n otre demande de selectionner le handle le plus court de la liste avec l'integer "<5"

#Méthode 3
La méthode ".select" permet de sélectionner les handle dans la valeur "handle_twitter", nous précisons n otre demande de selectionner les handle ayant 5 caractères avec l'integer "==5"

#Méthode 4
La méthode ".select" permet de sélectionner les handle dans la valeur "handle_twitter", nous précisons n otre demande de selectionner les handle commençant par une majuscule avec le string "=~ /@([A-Z])/"

#Méthode 5
La méthode ".sort_by" permet de trier les handle dans la valeur "handle_twitter", nous précisons notre demande de les trier par ordre alphabétique avec le string ".last.downcase"

#Méthode 6
La méthode ".sort_by" permet de trier les handle dans la valeur "handle_twitter", nous précisons notre demande de les trier par taille (du plus petit au plus grand) avec le string "str.length"

#Méthode 7
La méthode ".index" permet de parcourir les handle de la valeur "handle_twitter", nous précisons notre demande de trouver la position de la personne "@epenser" avec le string "("@epenser")
