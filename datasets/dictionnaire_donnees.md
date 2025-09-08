# 📘 Dictionnaire de données

Le but du projet est de fusionner les tables "erp", "web" et "caracteristiques_vins" en une seule table, "df_boutique_web". Je ne fournis ici que le dictionnaire des données de la table finale :

## Table `portefeuille_actifs`

| Champ                     | Type    | Contrainte   | Description                                                                                                |
|---------------------------|---------|--------------|------------------------------------------------------------------------------------------------------------|
| `adresse_numero`          | INTEGER | Clé Primaire | Identifiant unique pour chaque produit                                                                     |
| `adresse_nom_voie`        | FLOAT   |              | Prix de l'article                                                                                          |
| `code_postal`             | INTEGER |              | Quantité du produit dans le stock de la boutique                                                           |
| `code_commune`            | INTEGER |              | Statut des stocks pour le `product_id`                                                                     |
| `nom_commune`             | INTEGER |              | Identifiant unique pour chaque produit sur le site web                                                     |
| `surface_carrez`          | FLOAT   |              | Nombre de ventes                                                                                           |
| `code_type_local`         | INTEGER |              | Nom complet du produit                                                                                     |
| `type_local`              | INTEGER |              | Description du produit                                                                                     |
| `surface_reelle_bati`     | INTEGER |              | Nom du produit qui sert de clé pour une jointure                                                           |
|`nombre_pieces_principales`| INTEGER |              | Lien de la page produit de la boutique web                                                                 |
| `longitude`               | INTEGER |              | Type de publication web                                                                                    |
| `latitude`                | INTEGER |              | Masse du produit                                                                                           |

## Table `historique_immobilier_paris_2017_2021`

| Champ                     | Type    | Contrainte   | Description                                                                                                |
|---------------------------|---------|--------------|------------------------------------------------------------------------------------------------------------|
| `date_mutation`           | DATE    | Clé Primaire | Identifiant unique pour chaque produit                                                                     |
| `valeur_fonciere`         | FLOAT   |              | Prix de l'article                                                                                          |
| `adresse_numero`          | INTEGER |              | Quantité du produit dans le stock de la boutique                                                           |
| `adresse_nom_voie`        | STRING  |              | Statut des stocks pour le `product_id`                                                                     |
| `code_postal`             | INTEGER |              | Identifiant unique pour chaque produit sur le site web                                                     |
| `nom_commune`             | FLOAT   |              | Nombre de ventes                                                                                           |
| `code_type_local`         | FLOAT   |              | Nombre de ventes                                                                                           |
| `type_local`              | FLOAT   |              | Nombre de ventes                                                                                           |
| `surface_reelle`          | FLOAT   |              | Nombre de ventes                                                                                           |

## Table `echantillon_a_classer2`

| Champ                     | Type    | Contrainte   | Description                                                                                                |
|---------------------------|---------|--------------|------------------------------------------------------------------------------------------------------------|
| `valeur_fonciere`         | FLOAT   | Clé Primaire | Identifiant unique pour chaque produit                                                                     |
| `code_postal`             | FLOAT   |              | Prix de l'article                                                                                          |
| `nom_commune`             | STRING  |              | Quantité du produit dans le stock de la boutique                                                           |
| `surface_reelle`          | INTEGER |              | Statut des stocks pour le `product_id`                                                                     |
