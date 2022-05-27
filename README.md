# My_Database-
Nous avons en place une base de données qui permet le suivi de la location de films d'une cinéma
Elle contient: 
- Une table pour les informations des clients (nom, prénom, telephone, ville);
- Une table pour les informations sur les films (titre, date de sortie, durée, réalisateur);
- Une table pour les catégories des films;
- Une table pour saisir les payments faits par les clients;
- La table Film loué, pemet de retrouver le type de film loué 
- Enfin, la table Historique permet de conserver la trace des entrées et sorties de chaque film et de la personne qui l'a loué.




1- Pour ajouter les information d'un film (Empire dans notre exemple), vous pourrez utiliser cette requête = " INSERT INTO film (name_film , realisateur , duree , date_sortie ) VALUES (Empire , Lee Daniels & Danny Strong , 2h18 , 2006/12/08 ) "

2- Vous souhaitez modifier les infos d'un film, par exemple au niveau du realisateur = " UPDATE film SET realisateur = 'Danny Strange' WHERE id=1 ; "

3- Supprimer un film 
DELETE FROM film WHERE id=1 ;

4- Ajouter un client = " INSERT INTO client (idclient , name , firstname , email , telephone , Ville)"

5- Si vous souhaitez afficher les 3 derniers film ajoutés = " SELECT * FROM filmdb.film ORDER BY idfilm ASC LIMIT 3; "
