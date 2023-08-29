# -Application-de-la-Regression-en-machine learning
#in frensh

Simple Linear Regression

Ce script illustre comment effectuer une régression linéaire simple en utilisant la bibliothèque Python sklearn. La régression linéaire simple est utilisée pour prédire les salaires en fonction des années d'expérience.
Instructions

    Placez votre ensemble de données nommé Salary_data.csv dans le même répertoire que ce script.
    Exécutez le script à l'aide d'un interpréteur Python.

Étapes

    Le script commence par charger l'ensemble de données à partir du fichier CSV Salary_data.csv.
    Les caractéristiques (années d'expérience) et les étiquettes (salaires) sont extraites de l'ensemble de données.
    Les données sont divisées en ensembles d'entraînement et de test à l'aide de la fonction train_test_split.
    Un modèle de régression linéaire est créé à l'aide de la classe LinearRegression de sklearn.
    Le modèle est entraîné sur les données d'entraînement à l'aide de la méthode fit.
    Les salaires sont prédits à l'aide du modèle entraîné et des données de test.
    Les résultats réels et prédits sont affichés dans un tableau.
    Les résultats sont visualisés à l'aide de diagrammes de dispersion et de la ligne de régression.

Multiple Linear Regression with Categorical Data

Ce script illustre comment effectuer une régression linéaire multiple avec des données catégorielles en utilisant la bibliothèque Python sklearn. La régression linéaire multiple est utilisée pour prédire les profits des startups en fonction de diverses caractéristiques.
Instructions

    Placez votre ensemble de données nommé 50_Startups.csv dans le même répertoire que ce script.
    Exécutez le script à l'aide d'un interpréteur Python.

Étapes

    Le script commence par charger l'ensemble de données à partir du fichier CSV 50_Startups.csv.
    Les caractéristiques (variables indépendantes) et les étiquettes (profits) sont extraites de l'ensemble de données.
    Les variables catégorielles sont encodées en utilisant OneHotEncoder et la classe ColumnTransformer.
    Les données sont divisées en ensembles d'entraînement et de test à l'aide de la fonction train_test_split.
    Un modèle de régression linéaire est créé à l'aide de la classe LinearRegression de sklearn.
    Le modèle est entraîné sur les données d'entraînement à l'aide de la méthode fit.
    Les profits sont prédits à l'aide du modèle entraîné et des données de test.
    Les résultats réels et prédits sont affichés dans un tableau.

Polynomial Regression

Ce script illustre comment effectuer une régression polynomiale en utilisant la bibliothèque Python sklearn. La régression polynomiale est utilisée pour prédire les salaires en fonction des niveaux de poste.
Instructions

    Placez votre ensemble de données nommé Position_Salaries.csv dans le même répertoire que ce script.
    Exécutez le script à l'aide d'un interpréteur Python.

Étapes

    Le script commence par charger l'ensemble de données à partir du fichier CSV Position_Salaries.csv.
    Les caractéristiques (niveaux de poste) et les étiquettes (salaires) sont extraites de l'ensemble de données.
    Les caractéristiques sont transformées en caractéristiques polynomiales à l'aide de PolynomialFeatures.
    Un modèle de régression linéaire est créé à l'aide de la classe LinearRegression de sklearn.
    Le modèle est entraîné sur les données transformées à l'aide de la méthode fit.
    Les salaires sont prédits à l'aide du modèle entraîné et des données transformées.
    Les résultats réels et prédits sont affichés dans un tableau.
    Les résultats sont visualisés à l'aide de diagrammes de dispersion et de la courbe de régression polynomiale.

#in English 

Simple Linear Regression

This script demonstrates how to perform simple linear regression using the Python sklearn library. Simple linear regression is used to predict salaries based on years of experience.
Instructions

    Place your dataset named Salary_data.csv in the same directory as this script.
    Run the script using a Python interpreter.

Steps

    The script starts by loading the dataset from the Salary_data.csv CSV file.
    Features (years of experience) and labels (salaries) are extracted from the dataset.
    Data is split into training and testing sets using the train_test_split function.
    A linear regression model is created using the LinearRegression class from sklearn.
    The model is trained on the training data using the fit method.
    Salaries are predicted using the trained model and the test data.
    Real and predicted results are displayed in a table.
    Results are visualized using scatter plots and the regression line.

Multiple Linear Regression with Categorical Data

This script demonstrates how to perform multiple linear regression with categorical data using the Python sklearn library. Multiple linear regression is used to predict startup profits based on various features.
Instructions

    Place your dataset named 50_Startups.csv in the same directory as this script.
    Run the script using a Python interpreter.

Steps

    The script starts by loading the dataset from the 50_Startups.csv CSV file.
    Features (independent variables) and labels (profits) are extracted from the dataset.
    Categorical variables are encoded using OneHotEncoder and the ColumnTransformer class.
    Data is split into training and testing sets using the train_test_split function.
    A linear regression model is created using the LinearRegression class from sklearn.
    The model is trained on the training data using the fit method.
    Profits are predicted using the trained model and the test data.
    Real and predicted results are displayed in a table.

Polynomial Regression

This script demonstrates polynomial regression using the Python sklearn library. Polynomial regression is used to predict salaries based on position levels.
Instructions

    Place your dataset named Position_Salaries.csv in the same directory as this script.
    Run the script using a Python interpreter.

Steps

    The script starts by loading the dataset from the Position_Salaries.csv CSV file.
    Features (position levels) and labels (salaries) are extracted from the dataset.
    Features are transformed into polynomial features using PolynomialFeatures.
    A linear regression model is created using the LinearRegression class from sklearn.
    The model is trained on the transformed data using the fit method.
    Salaries are predicted using the trained model and the transformed data.
    Real and predicted results are displayed in a table.
    Results are visualized using scatter plots and the polynomial regression curve.
