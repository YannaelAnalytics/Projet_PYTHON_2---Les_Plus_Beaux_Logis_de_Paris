# Les Plus Beaux Logis de Paris 🏙️

## Description du projet

Ce projet Python vise à aider une entreprise immobilière parisienne à optimiser la gestion de son portefeuille de biens en Île-de-France. Avec près d’un millier de propriétés, l’entreprise cherche à identifier quels actifs vendre ou conserver afin de sécuriser sa trésorerie et réduire les risques liés aux fluctuations du marché immobilier.

Le projet s’articule autour de deux axes principaux :

### 1) Analyse et prédiction des prix immobiliers
Nous analysons l’évolution des prix de l’immobilier à Paris pour déterminer quel segment (particuliers ou entreprises/collectivités) est le plus porteur. Ensuite, nous entraînons un modèle de régression linéaire pour prédire l’évolution des prix dans chaque segment. Cela permet à l’entreprise de décider quels biens vendre pour optimiser sa trésorerie.

### 2) Classification automatique des biens
L’entreprise reçoit régulièrement des opportunités d’achat mais ne connaît pas toujours la nature exacte des biens (logement particulier, local commercial, ancien cabinet médical, agence, etc.). Actuellement, cette information est obtenue manuellement, souvent par téléphone, ce qui ralentit la prise de décision.
Grâce à notre modèle de clustering, nous classons automatiquement les biens par type, permettant à l’entreprise d’adapter sa stratégie rapidement selon la nature du bien (revente rapide, reconversion nécessaire, etc.).

## Objectifs du projet

- Optimiser la détention des actifs de l’entreprise entre biens pour particuliers et biens professionnels.

- Prédire l’évolution des prix immobiliers pour chaque segment.

- Classer automatiquement les opportunités d’achat par type de bien.

- Aider l’entreprise à anticiper la valorisation future de chaque segment et à vendre les biens du segment le moins porteur.

## Technologies utilisées

- Python 3

- Pandas & NumPy pour la manipulation des données

- Scikit-learn pour la régression linéaire et le clustering

- Matplotlib & Seaborn pour la visualisation
