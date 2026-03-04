**Challenge Telecom X - Parte 2 - Alura Latam**

En este Challenge se aplicó y se pusieron a prueba los conocimientos adquiridos durante toda la segunda etapa del curso ONE de Alura Latam en conjunto con Oracle Next Education.

Para realizar el challenge utilice la base de datos del Challenge Telecom X - Parte 1.
A dicha base de datos se le realizaron distintas modificaciones, eliminando columnas irrelevantes o columnas numericas que tenian correlación, asi como tambien se eliminaron columnas categóricas con mucha similitud entre ellas y que no representaban una influencia importante sobre la variable de respuesta.

Luego se realizó un encode y division del conjunto de datos para continuar con el entrenamiento de dos modelos predictivos.
Los modelos entrenados fueron Regresión Logística y Random Forest. En un principio las métricas obtenidas con ambos fueron insuficientes. Luego se aplicó un balanceo para nuevamente aplicar el modelo de Regresión Logística con lo que se obtuvo un muy buen desempeño del modelo realizando predicciones sobre el conjunto de prueba.

A continuacion se adjunta la matriz de confusión de este ultimo modelo entrenado:

<img width="476" height="455" alt="image" src="https://github.com/user-attachments/assets/357082fc-7ac4-40a0-ba27-c8a69a81856e" />


