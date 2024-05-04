À l'aide de ce programme en fait la gestion d'une bibliothèque en langage C. Notre programme offre plusieurs fonctionnalités pour gérer des livres, à titre d’exemple : l'ajout, la modification, la suppression, l'affichage, la recherche, le tri et l'enregistrement des livres.

On citera notamment les fonctionnalités principales du programme :

Une fonction pour ajouter un livre : Ajouter un nouveau livre à la bibliothèque à l'aide de son titre, auteur, description, prix, catégorie, etc. Une fonction pour la modification d'un livre : Modifier les détails d'un livre existant en se basant sur son ID. L'utilisateur peut du coup mettre à jour le titre, l'auteur, la description, le prix et la catégorie du livre.

Fonction pour supprimer un livre : Supprimer un livre de la bibliothèque en entrant son ID.

Fonction pour afficher la liste des livres : Cette fonction affiche tous les livres présents dans la bibliothèque avec leurs détails : l'ID, le titre, l'auteur, la description, le prix, la catégorie, etc.

Fonction pour rechercher un livre : Rechercher un livre par son titre ou son auteur, le programme ensuite affiche les livres correspondants aux critères de recherche de l'utilisateur.

Fonction pour trier les livres : Possibilité de trier les livres par titre ou par catégorie.

Fonction pour enregistrer les livres : Cette fonction se contente d'enregistrer les détails des livres dans un fichier CSV nommé "livres.csv".

Charger les livres : Lors du démarrage du programme cette fonction charge les livres à partir du fichier CSV qu'on a déjà nommé "livres.csv". Maintenant pour expliquer comment utiliser le programme voici quelque informations :

Au démarrage, l'utilisateur est appelé à saisir son nom, sa saisie lui poussera de suite à se diriger vers un menu qui sera affiché en proposant les différentes actions qui peuvent être effectuées sur la bibliothèque. L'utilisateur peut choisir une option en entrant le numéro correspondant à l'action souhaitée, selon l'action choisie, l'utilisateur est guidé à travers les étapes nécessaires pour effectuer l'action désirée, ce programme continue à s'exécuter jusqu'à ce que l'utilisateur choisisse l'option "Quitter" ( fonction ) .