# Machine-learning-detection--malweres



## Titre du Projet: Intégration MLOps pour la Détection de Malware

## Introduction
Ce projet vise à intégrer les principes des opérations de machine learning (MLOps) avec des systèmes de détection de malware basés sur des signatures et des images. Nous  adopterons une approche pratique pour rechercher des ensembles de données contenant des échantillons de malware sous forme d'images et de signatures. En suivant un pipeline de machine learning structuré, nous prétraiterons les données, entraînerons plusieurs modèles et évaluerons leurs performances en fonction de divers métriques.Nous utiliserons des modèles SVM pour la classification d'images et Random Forest pour la classification de fichiers, en automatisant le processus de développement, de déploiement et de maintenance avec Jenkins et Docker.

## Objectif
L'objectif principal est d'intégrer les principes MLOps avec les systèmes de détection de malware basés sur des signatures et des images et d'évaluer les performances de divers modèles de machine learning. En appliquant les pratiques MLOps tout au long du processus, nous gérerons efficacement le cycle de vie du développement des modèles de machine learning pour les applications de cybersécurité.





## Choisi de model
pour la partie choisi de modèle on a testé plusieurs modèles soit dans la partie de classification selon l'image et la partie classification selon la signature du fichier .pour la première partie nous avons  testé plusieurs algorithmes de classification et notamment et  random Forest , naïf bises et SVM mais cette dernière est et a donné le la meilleure accuracy  de 95 % toutes en faisant suivant une démarche de pré-traitement des données et enregistrer les processus de pré-traitment et notre modèle sous forme pkl et la même chose pour la classification selon file ou nous avons tester l'approche de grid search avec l'ensemble de parametre possible pour plusieurs modèle tel que random forest régression logistique et svm ,mais en fin de compte, nous avons choisi le modèle random forest qui nous a donné les meilleurs résultats .

## Configuration et Installation

Prérequis
 
   Docker
   
   Node.js et npm

## Étapes d'Installation

1.Clonez le dépôt :

git clone https://github.com/machine-learning-detection--malweres/mlops-malware-detection.git
cd mlops-malware-detection

2.Construisez et lancez les conteneurs Docker (pour chaque image):
docker build -t nom-image .

3.Accédez à l'application Angular dans votre navigateur web à l'adresse http://localhost:4200.



## Utilisation

Naviguez vers l'interface de l'application Angular.
Utilisez les composants de téléchargement de fichiers pour télécharger des images ou des fichiers pour la classification.
Consultez les résultats affichés à l'écran.


##Captures d'écran



