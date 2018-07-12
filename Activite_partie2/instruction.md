# Activité_Partie 2
C’est maintenant à vous de jouer. Votre but est de créer la base de données d’un site de blog basique.


## Informations nécessaires
Voici les informations nécessaires à la création de la base de données :

Il s’agit donc d’un blog. Sur ce blog sont publiés des articles, composé d’un titre, d’un texte et d’un résumé (ou extrait). Ils sont écrits par des utilisateurs (pseudo, email, mot de passe).
Les articles doivent appartenir à au moins une catégorie. Chaque catégorie est composée d’un nom et d’une description.
Il est possible de commenter les articles. Si le commentateur est un utilisateur enregistré, le commentaire est lié à son compte. Il est possible de commenter un article sans être connecté, sans même avoir de compte.
Sur la page d’accueil, les articles sont affichés (titre, date, auteur et résumé). Ils sont triés par date de publication.
En dehors de la page principale, il existe trois type de pages : une page utilisateur, reprenant les articles écrits par un utilisateur triés par date, une page catégorie, qui affiche les articles d’une catégorie, également triés par date, et enfin une page article, qui affiche un article complet ainsi que ses commentaires par ordre chronologique.


## Votre mission

Créez les tables nécessaires pour contenir toutes les données de ce blog. Choisissez le type des colonnes intelligemment. N’oubliez pas d’ajouter des index et/ou des clés lorsque c’est nécessaire. Pensez à garantir l’intégrité des données, mais aussi éventuellement à améliorer la performance des requêtes nécessaires pour afficher les différentes pages.

Pour vous aider, les requêtes de création de la base de données, ainsi que de deux tables vous sont fournies. Il s’agit des tables Categorie et Categorie_article, qui contiennent respectivement les information sur les catégories, et les liens entre les catégories et les articles.

Cette table de liaison est indispensable, étant donné que chaque article peut appartenir à plusieurs catégorie et chaque catégorie peut bien sûr contenir plusieurs articles.

Si l’article 2 appartient aux catégories 3 et 7, on aura donc deux lignes dans la table Categorie_article

Notez qu’à l’exception de la clé primaire, aucune clé et aucun index n’est créé pour ces deux tables. N’hésitez pas à en rajouter si vous le jugez nécessaire (sans modifier les requêtes fournies).


## Fichier à renvoyer

Vous devez renvoyer un fichier zip contenant le fichier .sql contenant les requêtes de création de toutes les tables de la base de données (y compris les tables fournies), ainsi que les éventuelles requêtes de création de clés et/ou d’index.