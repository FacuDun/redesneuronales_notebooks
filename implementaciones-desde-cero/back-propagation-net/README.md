# Back Propagation Net

Implementación desde cero (sin frameworks de ML) de una red neuronal multicapa entrenada mediante backpropagation (regla delta generalizada).

## Descripción del trabajo

Se construye una red para predecir qué alumnos están en riesgo de desaprobar Análisis Matemático I, a partir de variables como horas de estudio, presentismo y horas de sueño. Se entrena con datos de alumnos de UTN Buenos Aires y luego se evalúa sobre un dataset nuevo de alumnos de UTN FRCU, para identificar a quiénes conviene prestarles atención antes del próximo examen.

Está implementado desde cero: forward y backward propagation, funciones de activación (ReLU, Sigmoide) y sus derivadas, y actualización de pesos vía descenso por gradiente con tasa de aprendizaje decreciente. Solo se usan librerías para manejo de datos y gráficos.

## Créditos

- Dataset de alumnos de UTN Buenos Aires y FRCU: generado por el autor mediante Claude.
- Imagen de la estructura de la red: elaborada por el autor con Miro.
