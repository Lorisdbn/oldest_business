# World’s Oldest Businesses Analysis Project

![Staffelter Hof Winery](images/MKn_Staffelter_Hof.jpg)

## Overview
Ce projet analyse les entreprises les plus anciennes encore en activité à travers le monde, tel que compilé par BusinessFinancing.co.uk. L’objectif est de comprendre la longévité des entreprises selon les pays, les catégories et les périodes historiques.

## Objectifs
1. Identifier le nombre total d’entreprises dans la base.  
2. Déterminer l’entreprise la plus ancienne (année de fondation minimale).  
3. Analyser la répartition des entreprises anciennes par continent.  
4. Comparer la création de nouvelles entreprises (depuis 1900) avec la base historique.

## Structure du dépôt
```bash
├── data/                  # Fichiers CSV nettoyés
│   ├── businesses.csv     # Entreprises historiques
│   ├── new_businesses.csv # Entreprises créées depuis 1900
│   ├── countries.csv      # Référentiel des pays
│   └── categories.csv     # Référentiel des catégories
├── images/                # Illustrations et photos référencées
│   └── MKn_Staffelter_Hof.jpg
├── sql/                   # Requêtes SQL pour l’analyse
│   ├── 01_count_businesses.sql
│   ├── 02_oldest_business.sql
│   ├── 03_businesses_by_continent.sql
│   └── 04_new_vs_historical.sql
├── results/               # Résultats des requêtes et graphiques
├── README.md              # Documentation du projet
└── requirements.txt       # Dépendances Python (pour analyses complémentaires)
