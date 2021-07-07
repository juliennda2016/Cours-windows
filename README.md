# Cours-windows
 5 ) Les services et processus.
Un service est un programme qui commence en arrière plan et qui s’exécute au démarrage de windows , un service n’a aucune interface utilisateur et fonctionne à tout moment. 
Pour lister les processus on utilise en general  le gestionnaire de tâche, chaque processus à un indique. Chaque processus à un indique , 
Pour lister les processus , on a la commande get-service. 
Avec get-service, on obtient l’ensemble des services., on obtient leur etat , leur nom d’affichage. 
Pour recuperer , un service particulier on va taper la commandlet : Nous permet d’avoir des informations fondamentaux sur les différents services .
 get-service themes | select-object*
Ainsi s’affichera tous les propriété le concernant, le thème sélectionné.




 

Ensuite aller sur un autre service et récupérer les dépendance de ces services . 
On va sur le service Win RM et recouper le service. 

