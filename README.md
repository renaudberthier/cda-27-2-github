## Commandes

- git status : Permet de savoir où on en est : quels fichiers ont été modifiés/créés/supprimés en local par rapport à la copie distante

- git add : Permet de dire à Git "ce fichier doit être suivi, on doit l'ajouter au contrôle de version : je veux pouvoir revenir en arrière ou repartir en avant sur ce fichier plus tard".

- git rm --cached : Permet d'annuler un git add quand on a fait une bêtise

- git commit -m "Le message" : Réalise un point d'étape du projet, qui servira de point dans le temps auquel on pourra revenir dans le futur (sauf exceptions).

- git branch -c nom_branche : Crée une nouvelle branche

- git switch nom_branche : Change pour la branche "nom_branche"