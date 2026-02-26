# Analyse et Clustering de Données Nutritionnelles (Projet SY09)
Ce projet a été réalisé dans le cadre de l'unité d'enseignement SY09 (Analyse de données). L'objectif est d'explorer, de visualiser et de segmenter un jeu de données nutritionnelles afin d'identifier des groupes d'aliments cohérents et d'analyser leurs similarités structurelles.

## Présentation du Projet
Le projet repose sur l'étude d'un dataset (cleaned_nutrition_dataset.csv) contenant diverses caractéristiques nutritionnelles pour une large gamme d'aliments. À travers une démarche de Data Science rigoureuse, nous appliquons des techniques de réduction de dimension et de clustering pour extraire de la connaissance à partir de données multidimensionnelles.

Points clés de l'étude :
Nettoyage & Prétraitement : Normalisation des données pour garantir l'équité entre les variables.
Réduction de Dimension : Utilisation de l'ACP (Analyse en Composantes Principales) et du MDS (Multidimensional Scaling / AFTD) pour visualiser les données en 2D/3D.
Clustering (Segmentation) : Mise en œuvre de la CAH (Classification Ascendante Hiérarchique) avec analyse de dendrogrammes pour définir le nombre optimal de classes.
Visualisation Avancée : Utilisation de diagrammes de Shepard pour valider la qualité des projections MDS.

🛠️ Technologies & Bibliothèques
Langage : Python 3
Analyse de données : Pandas, NumPy
Machine Learning : Scikit-learn (PCA, MDS, AgglomerativeClustering)
Visualisation : Matplotlib, Seaborn


## Installation et Utilisation
1. Cloner le dépôt
Bash
git clone https://github.com/votre-utilisateur/votre-projet.git
cd votre-projet

2. Installer les dépendances
Il est recommandé d'utiliser un environnement virtuel :
Bash
pip install pandas numpy matplotlib seaborn scikit-learn

3. Lancer l'analyse
Ouvrez le fichier Jupyter Notebook pour visualiser les étapes de l'analyse :
Bash
jupyter notebook SY09_Jupyter.ipynb


## Structure du Projet
SY09_Jupyter.ipynb : Le notebook contenant l'intégralité du code, des analyses et des visualisations.
SY09_Projet_Rapport_Final.pdf : Le rapport détaillé expliquant les choix méthodologiques et l'interprétation des résultats.
cleaned_nutrition_dataset.csv : Le jeu de données utilisé pour l'étude.
utils : Fichier contenant des fonctions utilitaires (ex: plot_dendrogram, plot_Shepard).


## Résultats Principaux
L'analyse a permis de :

Identifier les corrélations entre les différents nutriments (ex: graisses vs calories).

Projeter les aliments dans un plan factoriel conservant plus de 80% de l'inertie (via ACP).

Dégager 7 classes d'aliments distinctes via la CAH, regroupant par exemple les produits laitiers, les viandes/poissons, ou encore les produits céréaliers.

Auteur : Tareq Derdaki, Ruoyang Wang, Tidiane Bengriche

Contexte : Université de Technologie de Compiègne (UTC) - UV SY09
