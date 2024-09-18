# analyseCartesCredit

## Description du Projet

Ce projet consiste en une analyse des données issues de cartes de crédit en utilisant des techniques de machine learning et de traitement de données avec Python. Il utilise des bibliothèques populaires telles que `pandas`, `numpy`, `matplotlib`, `seaborn`, et `scikit-learn`. Les objectifs principaux incluent :

- Nettoyage et prétraitement des données
- Encodage des variables catégoriques
- Normalisation des données
- Application de modèles de machine learning pour la classification

### Données

Les données sont chargées depuis deux fichiers CSV : 
1. **Credit_card.csv** : contient les informations sur les individus et leurs transactions.
2. **Credit_card_label.csv** : contient les étiquettes indiquant si un individu est un bon ou un mauvais payeur.

### Étapes principales

1. **Nettoyage des données :** Gestion des valeurs manquantes en les remplissant avec des valeurs adéquates (moyennes, modes, etc.).
2. **Encodage des variables catégoriques :** Transformation des variables comme le sexe, le type de logement, et l'état civil en variables numériques.
3. **Normalisation des données :** Normalisation des caractéristiques numériques pour garantir que toutes les variables sont sur une même échelle.
4. **Modélisation :** Utilisation de modèles comme la régression logistique et les forêts aléatoires pour la prédiction.


## Prérequis

Vous devez avoir les bibliothèques Python suivantes installées :

- `numpy`
- `pandas`
- `matplotlib`
- `seaborn`
- `scikit-learn`

Vous pouvez les installer via `pip` avec la commande suivante :

'!pip install numpy pandas matplotlib seaborn scikit-learn'

## Exécution du projet

### Exemple d'exécution

1. Clonez ce projet.
2. Assurez-vous que les fichiers `Credit_card.csv` et `Credit_card_label.csv` sont présents dans le répertoire.
3. Exécutez le notebook `TP_HAKIMA_DJERMOUNI.ipynb` en suivant les étapes dans l'ordre.

Exemple de chargement des données et de prétraitement :

'import pandas as pd'

# Chargement des données
data = pd.read_csv('Credit_card.csv')
labels = pd.read_csv('Credit_card_label.csv')

# Affichage des premières lignes des données:
print("Les premières lignes des données:")
print(data.head())

# Affichage des premières lignes des étiquettes:
print(labels.head())


## Résultats attendus

Après avoir exécuté le notebook, vous pourrez :

- Visualiser les distributions des données sous forme de graphiques.
- Identifier et gérer les valeurs manquantes.
- Créer des modèles de classification pour prédire les étiquettes de paiement des individus.


## Auteur

Ce projet a été développé par **Hakima Djermouni**.

## License

Ce projet est sous licence MIT. Vous pouvez consulter la licence dans le fichier `LICENSE`.
