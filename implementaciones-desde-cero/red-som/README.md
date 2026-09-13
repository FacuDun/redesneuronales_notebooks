# Red SOM para la clasificación de animales

Implementación desde cero (sin frameworks de ML) de un Mapa Autoorganizado (SOM) para agrupar animales por similitud de características sin disponer de su etiqueta de especie durante el entrenamiento.

## Descripción del trabajo

Con el [Zoo Dataset de UCI](https://archive.ics.uci.edu/dataset/111/zoo) pero sin las etiquetas de qué animal es ni de su especie, se entrena un SOM que ubica cerca entre sí a los animales con atributos parecidos, en una grilla 2D. Sobre esa grilla (o mejor dicho sobre las neuronas que la componen) aplicamos DBSCAN para dividir las neuronas en clusters (las neuronas del mismo cluster quedan agrupadas). Luego, etiquetamos esos clusters según sus características principales, quedándonos un mapa 2D dividido en zonas de mamíferos, aves, reptiles, etc.

Está implementado desde cero: competencia por neurona ganadora, función de vecindad gaussiana y decaimiento de parámetros. Solo librerías para el manejo de datos, gráficos y scikit-learn para el clustering con DBSCAN.

## Créditos

Dataset: [Zoo Dataset, UCI Machine Learning Repository (donante: Richard S. Forsyth)](https://archive.ics.uci.edu/dataset/111/zoo), licencia CC BY 4.0.
