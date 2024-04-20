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

- ## N.B
- Bonsoir  monsieur
- nous allons commencer la redaction du cahier de charfe il nous sera rendu le mardi 8 avril 2024 avant 00h
- je vous l ai mis sur le KanBan 
- 

