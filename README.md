# Proyecto-Video-Game-Predecitve-Model-
Por: Sergio González

En este proyecto se encontrará la predicción de ventas de videojuegos en Estados Unidos basado en el dataset obtenido en la página de Kaggle.
Este dataset se puede descargar y encontrar en el siguiente link: https://www.kaggle.com/datasets/migeruj/videogames-predictive-model
[![Video-Games-Sales.png](https://i.postimg.cc/yN6N9fHM/Video-Games-Sales.png)](https://postimg.cc/3k67QFW1)

Este proyecto utilizo la herramienta Visual Studio Code con un lenguaje de programación en Python, en donde se realizaron diferentes tipos de pruebas y módelos para obtener el mejor método de analisis.
1. El archivo fue creado en .ipynb
2. 

The project was made using Python and Colab. The code contains multiple tests on the data in order to obtain the best method for analysis. 
1. The code made in Colab has the steps listed in order to run the analysis properly.
2. Dataset was cleaned during the first steps. The following is the clean dataset:
[Datos procesados.csv](https://github.com/pazju/Chocolate-Ratings-Prediction/files/8750000/Datos.procesados.csv)
3. A classification and supervised method was selected based on the data, after this data was normalized.
4. The realization of PCA is discarded. The following image explains the reason: ![image](https://user-images.githubusercontent.com/98425571/169710216-60804549-8b84-468f-b3fb-67b21dd4dffc.png)
5. After doing a grid search and cross-validation using GridSearchCV to optimize the hiperparameters of different models, the model that best fits the data is a Linear Discriminant Analysis (LDA). The following shows the optimized model: ![image](https://user-images.githubusercontent.com/98425571/169710334-a3ea2846-94cc-4531-ae76-dc00ec39f508.png)
6. Finally the model is retrained with all the data and these are the results: ![image](https://user-images.githubusercontent.com/98425571/169710369-d054fa12-e67a-4e82-88ec-2d24f603ee19.png)

CONCLUSION:
The data given in the dataset is quite decorrelated to each other, demonstrating why the existence of chocolate tasters (people) and that the dataset can be improved if you want to analyze it using a machine learning model.

Link:
https://youtu.be/alCgHVV9Okg
