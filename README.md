# "Credit Card Fraud Detection Predictive Models" 
- Utilisation des modèles de machine learning pour la détection des fraudes
- https://github.com/users/FRANCESO222/projects/1


# Projet en cours de réalisation par :
- Omar Abdallaoui alaoui Groupe E.
- Aya Lazrak Groupe E.

# Fonctionnalités proposé:
- Problematique et description du sujet
- La collection des données
- pre-trairtement des données avec Python et les Biblistiques de la science des données
- Faire une présentation détaillée sur le domaine de la science des données et son rôle dans le domaine de la finance


# Technologies
- [MongoDb](https://www.mongodb.com/)
- [jupyter](https://jupyter.org/install)
  

# Outils et  Technologies:
- Python
- Pandas
- sklearn
- NumPy
- Matplotlib
- Jupyter Notebook
- Scikit-learn
- seaborn
- inline 

# Installation et Execution de l'application 
- Dans le lien suivant https://github.com/FRANCESO222/PFAO/blob/main/BACKEND  nous avons mis un code python qui utilise la bibliothèque Pandas pour manipuler les données de notre base de donnee tout d'abord, On a chargé les données du fichier CSV spécifié dans un DataFrame. Ensuite, On a remplacé toutes les occurrences de la valeur 0 dans le DataFrame par des valeurs NaN (non disponibles). Après cela,On a  supprimé toutes les lignes du DataFrame contenant au moins une valeur NaN, ce qui nettoie efficacement les données en éliminant les valeurs manquantes. Ensuite,On a  remplacé les valeurs NaN restantes par 999, une approche courante pour gérer les valeurs manquantes dans les données numériques. Enfin, On a  affiché les lignes du DataFrame où la valeur de la colonne 'Time' est égale à 0, offrant ainsi un aperçu spécifique des données. En résumé, ce code permet de charger, nettoyer et explorer un ensemble de données tabulaires de manière efficace .
- https://github.com/FRANCESO222/PFAO/blob/main/BD.csv Dans ce lien j'ai publié une partie de la base de données qu'on utilise, en raison de sa volumétrie importante. Cette décision a été prise pour faciliter l'accès aux données et pour assurer une meilleure gestion des ressources.
# Description de la base de données
- Cette base de données contient des informations sur des transactions financières, principalement des paiements par carte de crédit. Elle a été utilisée dans le cadre de la détection de fraudes et contient des transactions frauduleuses ainsi que des transactions légitimes pour l'entraînement de modèles de détection.
## Description des Colonnes :
- Time : Temps écoulé depuis la première transaction en secondes.
- V1-V28 : Variables de transformation résultant d'une analyse en composantes principales (ACP) pour protéger la confidentialité des données.
- Amount : Montant de la transaction.
- Class : Indicateur de classe, où 1 indique une transaction frauduleuse et 0 une transaction légitime.
## Contexte :
- Cette base de données est souvent utilisée dans la recherche et le développement de modèles de détection de fraudes, en particulier dans le domaine des transactions par carte de crédit. Elle a été collectée et analysée dans le cadre de la sécurité des systèmes de paiement.
# Explication du Backend 
- Dans le lien suivant https://github.com/FRANCESO222/PFAO/blob/main/BACKEND , on a réalisé un projet de détection de fraude par carte de crédit en utilisant Python dans un environnement Jupyter. Notre objectif est de développer des modèles prédictifs pour identifier les transactions frauduleuses dans un ensemble de données de transactions par carte de crédit. Actuellement, le code n'est pas encore complet, mais on a déjà réalisé une partie de l'analyse exploratoire des données et on a  commencé à développer les premiers modèles de prédiction. Demain, on prévoit de poursuivre le développement du code et en même temps de commencer le travail sur le frontend pour rendre l'application conviviale.
-  Le projet utilise plusieurs bibliothèques Python telles que Pandas, NumPy, Matplotlib, Seaborn et Plotly pour l'analyse exploratoire des données et la visualisation. On commence par charger les données à partir d'un fichier CSV nommé "BD.csv" ensuite, on examine les premières lignes du jeu de données pour comprendre sa structure.
-  Les données comprennent des transactions effectuées par des titulaires de cartes de crédit européennes en septembre 2013. Il y a un total de 284 807 transactions avec 492 cas de fraude, ce qui représente une faible proportion de 0,172% les caractéristiques des données sont principalement des composantes principales obtenues par une transformation en composantes principales (PCA) les seules caractéristiques qui n'ont pas été transformées avec PCA sont "Time" et "Amount" l a caractéristique "Time" représente les secondes écoulées entre chaque transaction et la première transaction dans l'ensemble de données, tandis que "Amount" représente le montant de la transaction.
-   Le projet explore également la distribution temporelle des transactions, en analysant les montants de transaction en fonction du temps. On utilise divers algorithmes de machine learning pour développer les modèles prédictifs, y compris RandomForrestClassifier, AdaBoostClassifier, CatBoostClassifier, XGBoost et LightGBM. On effectue une validation croisée pour évaluer les performances des modèles et on ajuste les hyperparamètres pour améliorer la précision de la prédiction. Enfin, on évalue les modèles et on conclut sur les résultats obtenus, en mettant en évidence les perspectives futures pour améliorer davantage la détection de fraude par carte de crédit.
-  Ensuite, on évalue les performances du modèle en utilisant une matrice de confusion et en calculant l'aire sous la courbe ROC (ROC AUC) ensuite, on répète le processus avec un modèle XGBoost en définissant des paramètres tels que le taux d'apprentissage, la profondeur maximale de l'arbre, et d'autres. On visualise également l'importance des fonctionnalités à l'aide d'un graphique.
-  De meme, on utilise le modele LightGBM en specifiant ses parametres et en visualisant l'importance des fonctionnalités.
-  Enfin, on effectue une validation croisée (cross-validation) avec plusieurs plis (folds) pour évaluer les performances globales des modèles,chaque pli est utilisé à la fois comme ensemble d'entraînement et de validation  et les prédictions sont agrégées pour obtenir une estimation plus robuste des performances du modèle.
-   En fin de compte, on obtient une évaluation complète de la performance de notre modèle de détection de fraudes par cartes bancaires.



