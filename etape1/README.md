# Étape 1 : Création de la base et de la table Livres

## 🎯 Objectif
Créer une base de données pour une bibliothèque et ajouter une table `Livres`.

## 📝 Instructions
1. Exécutez le script `etape1.sql` dans SQL Server.
2. Vérifiez que 5 livres ont bien été insérés.

## 📜 Script SQL à exécuter
```sql
CREATE DATABASE Bibliotheque;
GO

USE Bibliotheque;
GO

CREATE TABLE Livres (
    id INT PRIMARY KEY IDENTITY(1,1),
    titre NVARCHAR(255),
    auteur NVARCHAR(255),
    annee INT
);
GO

INSERT INTO Livres (titre, auteur, annee) VALUES
('1984', 'George Orwell', 1949),
('Le Petit Prince', 'Antoine de Saint-Exupéry', 1943),
('L\'Étranger', 'Albert Camus', 1942),
('Harry Potter à l\'école des sorciers', 'J.K. Rowling', 1997),
('Les Misérables', 'Victor Hugo', 1862);
GO

SELECT * FROM Livres;
GO
