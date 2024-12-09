# Informe de Evaluación y Conclusiones

## Introducción

En este informe, evaluaremos y compararemos los modelos RNN y LSTM desarrollados para la clasificación de noticias en categorías especializadas como deportes, cultura, economía y justicia. Excluimos otras categorías no especializadas para enfocarnos en temas con un discurso específico y relevante.

## Evaluación de los Modelos

### Modelo RNN

Para la clase 0:

- Precisión: (0.40): el 40% de esta clase es correcto.
- Recall: (0.26): identifica correctamente ejemplos en un 26%
- F1: (0.32): Rendimiento moderado.

para la clase 1:

- precisión: (0.34): solo el 32% de predicciones son correctas paa esta clase.
- Recall:(0.31): esta clase identifica correctamente ejemplos en un 31%.
- F1:(0.33):Rendimiento moderado.

Para la clase 2:

- Precisión:(0.29): Esta clase solo realiza predicciones correctas en un 29%
- Recall:(0.49): casi que la mitad de las veces identifica correctamente ejemplos.
- F1:(0.37): de todas las clases es la más alta

Para la clase 3:

- Precisión:(0.25): solo el 25% de esta clase es correcto.
- Recall:(0.18): no tiene relevancia su capacidad para identificar en esta clase.
- F1:(0.21): rendimiento bajo.

### Modelo LSTM

Para la clase 0:

- Precisión: (0.84): el 84% de esta clase es correcto.
- Recall: (0.94): identifica correctamente ejemplos en un 94%
- F1: (0.88): Rendimiento destacado

para la clase 1:

- precisión: (1.0): El 100% de predicciones son correctas paa esta clase.
- Recall:(0.92): esta clase identifica correctamente ejemplos en un 92%
- F1:(0.96):Rendimiento superior.

Para la clase 2:

- Precisión:(0.91): Esta clase realiza predicciones correctas en un 91%
- Recall:(0.88): En un 88% de las veces identifica correctamente ejemplos.
- F1:(0.90): Rendimiento destacado.

Para la clase 3:

- Precisión:(0.94): El 93% de esta clase es correcto.
- Recall:(0.92): Tiene relevancia significativa su capacidad para identificar en esta clase.
- F1:(0.93): rendimiento Superior.


## Conclusiones

El modelo LSTM integrado con CNN exhibe un rendimiento superior en comparación con los modelos anteriores, reflejando métricas significativamente elevadas y un comportamiento robusto en general. Esta configuración representa una base sólida para implementación en entornos de producción o como punto de partida para optimizaciones ulteriores.

