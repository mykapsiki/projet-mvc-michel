# Projet MVC Michel

Auteur : Leonella

# A propos de ce projet

Projet exemple en Java se basant sur le design pattern MVC pour enregistrer un produit en base.

## La vue 
Un formulaire HTML avec les champs suivant :
* Nom du produit
* Description du produit
* Date de création
* Prix du projet

## Controller
Une servlet qui traite les données du formulaire. La servlet appelle une Dao pour sauvegarder les données en base de données.

## Model
Le produit reprenant les champs de la vue.

# Comportement
Développer une internet ProduitDao et son implémentation ProduitDaoImpl avec 2 méthodes. Une méthode qui engistre le produit en base et une autre qui modifier les informations d'un produit existant déjà en base.
Base de données à utiliser = MySQL

