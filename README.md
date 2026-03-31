<p align="center"> <img src="https://img.shields.io/badge/Python-3.10-blue?logo=python"> <img src="https://img.shields.io/badge/Machine%20Learning-Scikit--Learn-orange"> <img src="https://img.shields.io/badge/Modèle-XGBoost-green"> <img src="https://img.shields.io/badge/Statut-Terminé-success"> <img src="https://img.shields.io/badge/Licence-MIT-lightgrey"> </p>
 Description

Ce projet a pour objectif de prédire les prix des biens immobiliers à l’aide de techniques de Machine Learning.

Il s’appuie sur :

une analyse approfondie des données (EDA)
une ingénierie des caractéristiques (feature engineering)
plusieurs modèles de régression performants

 Le système permet d’estimer automatiquement le prix d’un bien immobilier en fonction de ses caractéristiques.

 Objectifs
Identifier les facteurs influençant les prix immobiliers
Réaliser une analyse exploratoire complète
Construire et comparer plusieurs modèles de Machine Learning
Optimiser les performances du modèle
Fournir un outil d’aide à la décision
 Description des données

Le dataset contient les variables suivantes :

Variable	Description
 Localisation	Ville / Quartier
 Superficie	Surface en m²
 Chambres	Nombre de chambres
 Salles de bain	Nombre de salles de bain
 Parking	Disponibilité de parking
 Type de bien	Appartement, maison, etc.
 Année	Année de construction
 Prix	Variable cible
 Méthodologie <br>
1️⃣ Analyse exploratoire (EDA)
Visualisation des données
Détection des valeurs aberrantes
Analyse des corrélations <br>
2️⃣ Prétraitement des données
Gestion des valeurs manquantes
Encodage des variables catégorielles
Normalisation / Standardisation <br>
3️⃣ Modélisation

Modèles testés :

Régression Linéaire
Random Forest
Gradient Boosting
XGBoost (meilleur modèle 🚀) <br>
4️⃣ Évaluation

Métriques utilisées :

RMSE
MAE
R² Score
 Résultats

 Le modèle XGBoost offre les meilleures performances avec :

Une précision élevée
Une bonne capacité de généralisation
 Technologies utilisées
Python 🐍
Pandas / NumPy
Matplotlib / Seaborn
Scikit-learn
XGBoost <br>

 Installation et utilisation <br>
1️⃣ Cloner le projet
git clone https://github.com/ton-username/real-estate-price-prediction.git
cd real-estate-price-prediction <br>
2️⃣ Créer un environnement virtuel
python -m venv venv
source venv/bin/activate   # Linux / Mac
venv\Scripts\activate      # Windows <br>
3️⃣ Installer les dépendances
pip install -r requirements.txt <br>
4️⃣ Lancer le modèle
python src/train.py <br>




YIMFACK MORINO
 Étudiant en Informatique (Développement & Data Science)
 Douala, Cameroun

 Support

Si ce projet vous plaît :

 Mettez une étoile au repo
 Forkez le projet

