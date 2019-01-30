# README POUR THE MOOCADEMY 

Deux gems supplémentaires ont été installé : gem table_print et la gem faker

## Projet de Lutz Jonathan, Wenger Marylis et Maxime Smolis


### Présentation du projet :

Tu dois créer une plateforme d'apprentissage en ligne. Il y a plein de cours. Chaque cours a un titre et une description. Enfin, chaque cours a plusieurs leçons, qui ont un titre et un body.


#### Résolution :

On a crée une base de donnée avec deux tables : d'une part la table `Lectures`(= les cours) et d'autre part la table `Lessons`. Relation 1,N. 
Il faut donc inclure la foreign key de `Lessons` dans `Lectures`.


#### Fonctionnement du projet :

Dans un fichier seeds.rb, on a généré automatiquement des éléments à l'aide d'une boucle `times do` pour chaques tables grâce à la gem faker. Pour voir le resultat, se rendre dans `rails c` et utiliser la commande `tp NomTable.all`. Enjoy ;) 
