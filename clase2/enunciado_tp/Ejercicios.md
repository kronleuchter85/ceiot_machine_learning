# Ejercicio para entregar

Usando el dataset `winequality-red.csv`, el cual consiste en datos de vinos rojos basados en datos físico-químicos y una métrica de calidad de vino. Más info en [Kaggle](https://www.kaggle.com/datasets/uciml/red-wine-quality-cortez-et-al-2009). Queremos predecir la calidad del vino usando los atributos físico-químicos del mismo.
1. Lea el dataset como un DataFrame de Pandas. Realice un estudio de variables. Como se llaman y que están midiendo exactamente (vea la documentación del dataset). Además, analice que tipo de variables (incluido el target) son, cuál es el rango de estas variables y cómo se distribuyen (histograma). Además, realice una matriz de correlación, ¿cuáles variables parecen estar correlacionadas? y con respectos a la calidad del vino?
2. Realice si es necesario limpieza de datos y corrección de errores.
3. Construya un modelo de regresión lineal simple, el cual se intente predecir la calidad del vino usando el nivel de alcohol.
	1. Realiza la separación entre el dataset de entrenamiento y testeo. Utilice 80%-20%.
	2. Determine que métrica se va a usar para evaluar la calidad del modelo (MSE, MAE, etc.)
	3. Entrene el modelo con el set de entrenamiento.
	4. Evalúe el modelo con la métrica de evaluación y el coeficiente de Pearson.
4. Construya un modelo de regresión lineal múltiple, usando todos los atributos
	1. Realiza la separación entre el dataset de entrenamiento y testeo. Utilice 80%-20%.
	2. Entrene el modelo con el set de entrenamiento.
	3. Evalúe el modelo con la métrica de evaluación y el coeficiente de Pearson. Use la misma métrica que en el punto anterior.
5. En función de los resultados obtenidos, discuta los modelos, y que tan bien explican la calidad del vino.

Cree un notebook y realice los siguientes puntos (en el mismo notebook desarrolle el TP y vaya respondiendo las preguntas). OBS: Se ordenado/a y vaya respetando paso a paso los distintos puntos, creando las celdas necesarias. En el código, use buenas prácticas de programación. En el notebook no olvidar agregar a todos los miembros del grupo.

**Formulario de entrega**: [TP1](https://forms.gle/AtvewisLLD8SZvoj9)

**Fecha de entrega**: 26/11/2023 (hasta las 23:59)