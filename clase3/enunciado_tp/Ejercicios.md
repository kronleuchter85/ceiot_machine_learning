# Ejercicio para entregar

Sos un Data Scientist que trabaja para una empresa de publicidad que lanzo una campaña de publicidad en una red social. Se registró cada usuario al que se le mostró la publicidad, y se pudo obtener datos de la persona tales como `genero`, `edad` y `salario estimado`. Además se registró si el usuario luego compró el producto que la publicidad hacia referencia. Los datos están en `Social_Network_Ads.csv`. Se busca poder predecir dado un usuario con datos socioseconomicos si va a comprar o no el producto.

1. Lea el dataset como un DataFrame de Pandas. Realice un estudio de variables. Como se llaman y que están midiendo exactamente. Además, analice que tipo de variables son, cuál es el rango de estas variables y cómo se distribuyen (histograma). 
2. Genere gráficos de cajas de los diferentes atributos separando por clase (compro o no el producto). Entre los atributos, se observa alguna diferencia en lo gráficos de cajas?
3. Analize las clases, estan balanceadas, o no? Qué clase nos parece mas importante de las dos?
4. Separe el dataset en entrenamiento y validación. Utilice 70%-30%.
5. Determine que métrica se va a usar para evaluar la calidad de los modelos. Tenga en cuenta el balanceo de clases, y que objetivo se busca tener (por ejemplo, queremos predecir las mayor cantidad de personas que compran a expensas de tener falsos positivos o tener mucha seguridad a la hora de decir que una persona compra a expensa de tener falsos negativos).
6. Construya un modelo de regresión logística, el cual se intente predecir si una persona compró el producto o no.
	1. Entrene el modelo con el set de entrenamiento.
	2. Evalúe el modelo con la métrica de evaluación.
    3. (Opcional) Cree una curva ROC para evaluar el modelo para ver la calidad del modelo, sin depender del valor umbral. Elija un valor umbral que considere más optimo (usando AUC) y vuelva a clasificar usando ese valor.
7. Construya un modelo de KNN, el cual se intente predecir si una persona compró el producto o no.
	1. Este modelo se debe definir el numero de vecinos. Cree 4 modelos con K = 1, 3, 5 y 13 
    2. Entrene los modelos con el set de entrenamiento.
	3. Evalúe los modelos con la métrica de evaluación.
    4. Elija el mejor modelo de los cuatro en función de la metrica.
5. Compare el mejor modelo de regresión logistica y el mejor modelo de KNN. Cual fue el mejor modelo? Discuta los resultados.

Cree un notebook y realice los siguientes puntos (en el mismo notebook desarrolle el TP y vaya respondiendo las preguntas). OBS: Se ordenado/a y vaya respetando paso a paso los distintos puntos, creando las celdas necesarias. En el código, use buenas prácticas de programación. En el notebook no olvidar agregar a todos los miembros del grupo.

**Formulario de entrega**: [TP2](https://forms.gle/Pkosid46vb8sG6yz7)

**Fecha de entrega**: 03/12/2023 (hasta las 23:59)

----
**Formulario de entrega de correcciones**: [Correcciones](https://forms.gle/3bXegAQawU5EeSFx8)

**Fecha de entrega máxima**: 15/12/2023 (hasta las 23:59)