# Redes de base radial (RBF)

Implementación desde cero (sin frameworks de ML) de una red RBF para aproximar una función desconocida a partir de datos con ruido.

## Descripción del trabajo

Se simula un dataset de pares (x, y) generados a partir de la función sen(x) con ruido, como si se desconociera la función real detrás de esos datos. Se entrena una red RBF con activación Gaussiana en la capa oculta para aproximar esa función, y se evalúa comparando la salida de la red contra la función real.

Está implementado desde cero: activación Gaussiana, inicialización de centros y desviaciones por vecino más cercano, y ajuste de pesos por método analítico (pseudoinversa). Solo se usan librerías para manejo de datos, gráficos y el cálculo de la pseudoinversa.

## Créditos

Imagen de la función Gaussiana: generada por el autor mediante Gemini.
