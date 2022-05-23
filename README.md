# DATA_BASE
Creation de Base de données  relatonnelles pour la location de CD
 Quelques requêtes SQL 
 
INSERT INTO nom_table (colonne1, colonne4, colonne2)
VALUES ('data_colonne1', 'data_colonne4', 'data_colonne2');

DELETE FROM nom_table
[WHERE critères];

SELECT *
FROM films
WHERE format = 'mp4' OR format = 'webm'
ORDER BY id DESC;
LIMIT 3;

# on insert une donnée dans la table A
INSERT INTO Table_a (ma_colonne) VALUES ('ma donnée');

CREATE DATABASE nom_de_la_base

ALTER DATABASE nom_de_la_base CHARACTER SET character_set_name COLLATE collation_name;

DROP DATABASE nom_de_la_base;

RENAME TABLE ancien_nom TO nouveau_nom;
