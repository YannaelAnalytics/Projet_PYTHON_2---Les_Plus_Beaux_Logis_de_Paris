# Projet_PYTHON_2---Les_Plus_Beaux_Logis_de_Paris

L'entreprise possède près d'un millier de biens en IDF. Mais l'entreprise doit aujourd'hui se séparer des certains de ses actifs pour se garantir un niveau suffisant de trésorerie. Nous devons donc optimiser la détention des actifs de la société entre des biens à destination des particuliers et des biens à destination des entreprises et collectivités. Nous devons donc analyser les données sur l'évolution des prix de l'immobilier parisien pour déterminer le segment le plus porteur. Nous devrons ensuite entraîner un modèle de regression linéaire sur ces données pour qu'il puisse établir des prédictions sur l'évolution des prix de l'immobilier pour chacun des segments. Cela nous permettra de choisir dans quel segment vendre des actifs pour récupérer de la trésorerie et se couvrir des risques sur le marché de l'immobilier. 

L'entreprise achète des biens immobiliers au meilleur prix pour les revendre ensuite. Leur enjeu est d'agir rapidement lorsqu’une opportunité d’achat se présente pour éviter que les prix ne montent. Quand elle reçoit des opportunités par différents canaux, au-delà de la localisation, de la surface et du prix potentiel, elle n’a pas l’information sur la nature du bien (est-ce un local commercial, un ancien cabinet médical, une agence, un logement particulier ?). Ses conseillers sont obligés d’investiguer, souvent par téléphone, pour obtenir cette information. Celle-ci est capitale car l'entreprise adapte sa stratégie selon la nature du bien (capacité de revente, reconversion nécessaire…). Grâce à notre modèle de prédiction, nous allons effectuer un clustering des données afin de classer automatiquement les opportunités par type de bien.

Enfin, grâce à notre modèle de prédiction, nous prédirons la valorisation future de chaque segment (particulier & professionnel) pour que l'entreprise puisse anticiper et adapter sa stratégie vis-à-vis du segment le moins porteur et vendre une partie de se actifs pour récupérer de la trésorerie et se couvrir des risques sur le marché de l'immobilier. 

# Les Plus Beaux Logis de Paris 🏙️

## Description du projet

Ce projet Python vise à aider une entreprise immobilière parisienne à optimiser la gestion de son portefeuille de biens en Île-de-France. Avec près d’un millier de propriétés, l’entreprise cherche à identifier quels actifs vendre ou conserver afin de sécuriser sa trésorerie et réduire les risques liés aux fluctuations du marché immobilier.

Le projet s’articule autour de deux axes principaux :

### **Analyse et prédiction des prix immobiliers**
Nous analysons l’évolution des prix de l’immobilier à Paris pour déterminer quel segment (particuliers ou entreprises/collectivités) est le plus porteur. Ensuite, nous entraînons un modèle de régression linéaire pour prédire l’évolution des prix dans chaque segment. Cela permet à l’entreprise de décider quels biens vendre pour optimiser sa trésorerie.

### Classification automatique des biens
L’entreprise reçoit régulièrement des opportunités d’achat mais ne connaît pas toujours la nature exacte des biens (logement particulier, local commercial, ancien cabinet médical, agence, etc.). Actuellement, cette information est obtenue manuellement, souvent par téléphone, ce qui ralentit la prise de décision.
Grâce à notre modèle de clustering, nous classons automatiquement les biens par type, permettant à l’entreprise d’adapter sa stratégie rapidement selon la nature du bien (revente rapide, reconversion nécessaire, etc.).

## Objectifs du projet

Optimiser la détention des actifs de l’entreprise entre biens pour particuliers et biens professionnels.

Prédire l’évolution des prix immobiliers pour chaque segment.

Classer automatiquement les opportunités d’achat par type de bien.

Aider l’entreprise à anticiper la valorisation future de chaque segment et à vendre les biens du segment le moins porteur.

## Technologies utilisées

Python 3.x

Pandas & NumPy pour la manipulation des données

Scikit-learn pour la régression linéaire et le clustering

Matplotlib & Seaborn pour la visualisation
