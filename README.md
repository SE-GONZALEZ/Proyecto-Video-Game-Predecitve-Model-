# Proyecto-Video-Game-Predecitve-Model-
Por: Sergio González

En este proyecto se encontrará la predicción de ventas de videojuegos en Estados Unidos basado en el dataset obtenido en la página de Kaggle.
Este dataset se puede descargar y encontrar en el siguiente link: https://www.kaggle.com/datasets/migeruj/videogames-predictive-model
[![Video-Games-Sales.png](https://i.postimg.cc/yN6N9fHM/Video-Games-Sales.png)](https://postimg.cc/3k67QFW1)

Este proyecto utilizo la herramienta Visual Studio Code con un lenguaje de programación en Python, en donde se realizaron diferentes tipos de pruebas y módelos para obtener el mejor método de analisis el cual este problema de aprendizaje correspondía a uno de no supervisado y de regresión.
1. El archivo fue creado en .ipynb
2. Se procedio hacer la limpieza respectiva del dataset.
3. Se normalizaron los datos donde posteriormente se realizo PCA
4. Al comprobar los datos obtenidos en PCA fue necesario utilizar los 5 pliegues ya que cada una de los componentes de la variable X aportan información importante en la predicción que se va a desarrollar durante el código.
[![PCA.png](https://i.postimg.cc/x8173zCT/PCA.png)](https://postimg.cc/tZ82X7WL)
6. Después se realizó un gridsearch y cross-validación utilizando GridSearchCV para optimizar los hiperparametros de los diferentes módelos para R2, arrojando los mejores parametros del módelo seleccionado para obtener el mejor Score.
7. Los módelos utilizados fueron KNN donde se varió la métrica y peso de la distancia, Decision Tree se varió el criterio y profundidad de los árboles y para finalizar se utilizo Maquina de vectores de soporte "SMV"
[![SVM.png](https://i.postimg.cc/Qth5Pgcs/SVM.png)](https://postimg.cc/R3pNJHPb)
[![KNN.png](https://i.postimg.cc/FRpcQfxS/KNN.png)](https://postimg.cc/Q9BVQdwN)
[![Decision-TREE.png](https://i.postimg.cc/d08r4Nk4/Decision-TREE.png)](https://postimg.cc/yJ8DNPTZ)

Los datos proporcionados en el conjunto de datos están bastante descorrelacionados entre sí, para obtener un mejor resultado el conjunto de datos puede mejorar si desea analizarlo mediante de un modelo de aprendizaje automático.

Link:https://www.youtube.com/watch?v=9gelV7wpy8Q

