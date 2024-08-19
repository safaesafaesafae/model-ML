****Prédiction de la Demande dans le Secteur Retail****

**Description du Projet**
Ce projet a pour objectif de développer et d'évaluer un modèle de machine learning pour la prédiction de la demande dans le secteur retail.
Le projet se concentre sur l'évaluation de plusieurs modèles de séries temporelles (ARIMA, SARIMA, Prophet) dans un script Jupyter unique. Après les tests,
le modèle SARIMA a été sélectionné pour sa performance supérieure selon plusieurs métriques d’évaluation.

**Structure du Projet**

test1.ipynb : Notebook Jupyter contenant toutes les étapes du projet : exploration des données, évaluation et visualisation des résultats.

test_pres1.pdf : Présentation résumant les choix méthodologiques, les résultats obtenus et les recommandations finales.

file_out2.csv : fichier csv contenant les jeux de données utilisés (si applicable).


**Modèles Testés**

=>ARIMA : Modèle linéaire pour les séries temporelles sans saisonnalité.

=>SARIMA : Version saisonnière d’ARIMA, adaptée aux données présentant des cycles récurrents.

=>Prophet : Modèle flexible développé par Facebook, qui capte les tendances, la saisonnalité et les jours spéciaux.

Choix Final : Le modèle SARIMA a été retenu pour ses meilleures performances après évaluation des métriques RMSE, MAE et MAPE.

**Évaluation des Modèles**

L'évaluation des modèles a été réalisée en utilisant les métriques suivantes :

=>RMSE (Root Mean Squared Error) : Cette métrique évalue la racine carrée de la moyenne des erreurs au carré. Elle est sensible aux grandes erreurs et est utile pour minimiser les écarts importants dans les prédictions.

=>MAE (Mean Absolute Error) : Le MAE calcule l’erreur moyenne absolue entre les valeurs réelles et prédites. Il est simple à interpréter et robuste face aux outliers.

=>MAPE (Mean Absolute Percentage Error) : Le MAPE exprime l'erreur moyenne en pourcentage par rapport aux valeurs réelles, ce qui permet de comprendre l'erreur relative en termes de pourcentage. Cependant, il peut être biaisé si les valeurs réelles sont proches de zéro.

Résultats des Modèles :
Après comparaison des résultats sur ces métriques, SARIMA a montré les valeurs les plus faibles en RMSE, MAE et MAPE, ce qui indique qu'il offre les prévisions les plus précises pour la demande.

**Visualisations**

Les visualisations des résultats ont été réalisées en deux étapes :

=>Python (Matplotlib) : Génération de graphiques pour comparer les prédictions des modèles et visualiser les tendances détectées.

=>Power BI : Création de tableaux de bord interactifs pour explorer les données initiales et identifier les tendances avant la modélisation.

**Résultats**

Le modèle SARIMA a fourni les prévisions les plus précises, contribuant à une meilleure gestion des stocks et à une optimisation des ressources dans le secteur retail.
