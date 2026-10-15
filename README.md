# Pipeline ETL Retail — Power Query / Power BI

## Objectif
Construire un pipeline ETL No-Code dans Power BI Desktop à partir d'un 
dataset retail : chargement, transformation et restitution visuelle.

## Dataset
- 50 transactions sur 2 mois (janvier-février 2024)
- 6 produits, 3 magasins, 4 catégories

## Transformations Power Query
- Typage des colonnes (date, décimal, entier)
- Colonne calculée CA net : `quantite * prix_unitaire * (1 - remise)`
- Colonne calculée marge nette : `quantite * (prix_unitaire * (1 - remise) - cout_achat)`

## Rapport Power BI (3 visuels)
- CA net par région (histogramme)
- Marge nette par catégorie produit (barres horizontales)
- Évolution du CA par mois (courbe)

## Stack
Power BI Desktop, Power Query (M), CSV
