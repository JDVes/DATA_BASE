# DATA_BASE
Creation d'une Base de données  relatonnelles pour la location de CD
 Quelques requêtes SQL 
 
 Requete pour la table Film
 
 Ajouter un film
 
INSERT INTO Film(titre, date de sortie,durée, Réalisateur,)
VALUES ('power',2022/05/25','50min' 'Curtis Carter',);

ou

ALTER TABLE Film ADD Titre Varchar;
 

Supprimer un film

DELETE FROM Film
[WHERE id=3];

ou


ALTER TABLE Film
DROP COLUMN realisateur

Modifier le titre d'un film

ALTER TABLE Film
MODIFY Titre Varchar


UPDATE Film SET Titre = 'SEE' WHERE id = 2.

Requete pour la table Clients


 Ajouter un client
 
INSERT INTO clients(Nom ,prénoms,Email,)
VALUES ('power','2022/05/25','50min' 'Curtis Carter',);

ou

ALTER TABLE Clients ADD Nom Varchar;
 

Supprimer un Clients

DELETE FROM Clients
[WHERE id=3];

ou


ALTER TABLE Clients
DROP COLUMN realisateur

Modifier le Nom d'un Client

ALTER TABLE Clients
MODIFY email Varchar


UPDATE clients SET nom = 'raoul' WHERE id = 2.




une requête pour afficher les 3 derniers films ajouté

SELECT *
FROM films
WHERE format = 'mp4' OR format = 'webm'
ORDER BY id DESC;
LIMIT 3;



Fichier Sql











