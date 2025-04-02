# Étape 2 : Ajout des utilisateurs (Niveau intermédiaire)

## Question :

Ajoutez deux tables à votre base de données :
1. **Utilisateurs** avec les colonnes : 
   - `id` (entier, clé primaire)
   - `nom` (texte)
   - `email` (texte)

2. **Emprunts** avec les colonnes : 
   - `id` (entier, clé primaire)
   - `id_livre` (clé étrangère vers Livres)
   - `id_utilisateur` (clé étrangère vers Utilisateurs)
   - `date_emprunt` (texte au format 'YYYY-MM-DD')

Insérez 3 utilisateurs et 3 emprunts. 

### Question :
Quel est le nom de l’utilisateur qui a emprunté le premier livre inséré dans la table **Livres** ?

## Objectif :
Comprendre les relations entre tables et les clés étrangères.

## Critère de validation :
Les tables doivent être correctement liées, avec 3 utilisateurs et 3 emprunts.
