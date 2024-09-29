# Analyse des Ventes d'une Entreprise

Ce projet consiste à analyser les ventes mensuelles d'une entreprise à partir de plusieurs fichiers CSV. L'objectif principal est de consolider les données, d'identifier les tendances de vente, et de calculer des indicateurs clés tels que le chiffre d'affaires par mois.

## Table des matières
- [Description du projet](#description-du-projet)
- [Données utilisées](#données-utilisées)
- [Fonctionnalités](#fonctionnalités)
- [Technologies utilisées](#technologies-utilisées)

## Description du projet

Ce projet exploite des données de vente mensuelles provenant de fichiers CSV pour effectuer une analyse approfondie. L'analyse comprend :
- La consolidation des ventes sur plusieurs mois.
- Le nettoyage des données pour éliminer les valeurs manquantes.
- Le calcul du chiffre d'affaires mensuel afin de déterminer le mois le plus performant.
- L'identification des tendances de ventes par produit et région (à intégrer dans des versions futures).

## Données utilisées

Les données sont fournies sous forme de fichiers CSV représentant les ventes mensuelles de l'entreprise. Chaque fichier contient les colonnes suivantes :
- **Order ID** : Identifiant unique pour chaque commande.
- **Product** : Produit vendu.
- **Quantity Ordered** : Quantité commandée.
- **Price Each** : Prix unitaire du produit.
- **Order Date** : Date de la commande.
- **Purchase Address** : Adresse de livraison de la commande.

### Exemple de nettoyage des données
- Suppression des valeurs manquantes pour obtenir des données propres.
- Vérification et gestion des types de données (`dtypes`).
  
## Fonctionnalités

- Importation et consolidation des données de vente mensuelles.
- Nettoyage des données (suppression des valeurs manquantes).
- Analyse du chiffre d'affaires mensuel pour identifier le mois le plus performant.
- Visualisation des ventes (à ajouter dans les prochaines étapes).

## Technologies utilisées

- **Python** : Pour l'analyse et le traitement des données.
- **Pandas** : Pour la manipulation des données.
- **Matplotlib** et **Seaborn** : Pour la création de visualisations de données.
- **Jupyter Notebook** : Pour le développement et l'exécution du projet.

