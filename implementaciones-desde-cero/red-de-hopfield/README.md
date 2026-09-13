# Red de Hopfield

Implementación desde cero (sin frameworks de ML) de una red de Hopfield como memoria asociativa.

## Descripción del trabajo

Se memorizan tres patrones binarios (las letras A, T y L, representadas como matrices 6x6) calculando la matriz de pesos de la red. Luego se ingresan versiones ruidosas de esos patrones y se verifica que la red converja al patrón original almacenado.

Está implementado desde cero: cálculo de la matriz de pesos, función de suma neta y función de activación con recuperación iterativa hasta convergencia. Solo se usan librerías para manejo de datos y gráficos.
