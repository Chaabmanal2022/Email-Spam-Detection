Email Spam Detection
📚 Introduction
Ce projet consiste à créer un système capable de détecter les spams dans les emails. En utilisant des techniques de machine learning et de traitement du langage naturel, nous classifions les emails comme étant soit ham (légitimes), soit spam (non désirés).

🧠 Project Overview
Les emails sont devenus un moyen de communication essentiel, mais les spams restent un problème majeur. Ce projet vise à fournir une solution efficace en utilisant un modèle de machine learning entraîné sur un jeu de données contenant des exemples d'emails classifiés.

🚀 Features

Prétraitement des données textuelles pour éliminer le bruit.
Extraction de caractéristiques textuelles à l'aide de TF-IDF.
Classification des emails en utilisant la régression logistique.
Évaluation du modèle pour mesurer la précision et les performances.
Interface simple pour prédire si un email est un spam ou ham.
📁 Dataset

Le jeu de données utilisé contient deux colonnes principales :
Message : Texte de l'email.
Category : Classe de l'email (spam ou ham).
Ce fichier de données est inclus dans le projet sous le nom mail_data.csv.
🛠️ Technologies Used
Le projet utilise les technologies suivantes :

Python : Langage principal pour le développement.
pandas : Pour la manipulation des données.
scikit-learn : Pour les algorithmes de machine learning et l'extraction des caractéristiques.
NumPy : Pour les opérations numériques.
⚙️ Workflow

Chargement et nettoyage des données (remplacement des valeurs manquantes par des chaînes vides).
Transformation des textes en caractéristiques numériques à l'aide de TF-IDF.
Entraînement d'un modèle de régression logistique.
Évaluation des performances du modèle sur les ensembles d'entraînement et de test.
Prédiction de la catégorie d'un nouvel email.
