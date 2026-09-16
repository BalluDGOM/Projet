_Installation_
Sur une page quelconque, ajouter ce widget en tant que URL personnalisée ("Ajouter une vue à la page" => "Personnalisée" en sélectionnant n'importe quelle table puis choisir "URL personnalisée" et coller https://balludgom.github.io/Projet/widget.html dans le champ de saisie)

Cela crée les tables suivantes avec toutes les colonnes nécessaires (on peut en rajouter si besoin) et les liens entre ces tables :
- Entites: regroupement d'utilisateurs (typiquement ce sont des entités d'une hiérarchie), une entité peut avoir un parent
- Projet: un projet peut un parent (dans ce cas c'est un sous-projet)
- Tache: les tâches composant un projet
- Utilisateurs : les utilisateurs qui seront liés aux tâches / un utilisateur est lié à une entité

_Usage_

La gestion des utilisateurs, des entités et des projets se fait via les tables Grist standard.

Les tâches sont à créer via le widget. Si elles ont une date de début et une durée ou une dépendance avec une tâche qui en a alors elles pourront être affichées dans la vue Gantt

