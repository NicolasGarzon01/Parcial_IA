# Taller laboratorio agentes inteligentes - Parcial_IA
Este proyecto implementa y analiza distintos modelos de agentes inteligentes, desde una aspiradora autónoma hasta la simulación de la propagación de una enfermedad, evaluando mejoras y estrategias para el funcionamiento de un agente inteligente.
# Puntos implementados
Puntos Implementados:

1) Simulación de una Aspiradora Reactiva en NetLogo
Se desarrolló una aspiradora automática que limpia un tablero configurado con energía limitada. El agente se mueve de manera reflexiva, detectando y eliminando hojas dentro de su rango de sensores. Se ejecutó 50 veces para calcular el promedio de hojas recogidas y energía consumida.

2) Simulación de la Aspiradora con un Agente Basado en Modelo en NetLogo
Se mejoró la aspiradora agregando memoria para optimizar su recorrido. Ahora prioriza limpiar áreas detectadas con suciedad antes de explorar nuevas zonas, reduciendo el consumo de energía.

3) Simulación de la Aspiradora en Python
Se implementó una aspiradora autónoma en Python con ipywidgets, donde el agente:
- Detecta suciedad en celdas vecinas.
- Registra celdas visitadas para evitar recorridos innecesarios.
- Ejecuta 50 simulaciones para evaluar eficiencia.

4) Implementación de un Agente con Estado en Python
Se desarrolló una aspiradora con memoria y toma de decisiones óptimas, mejorando el rendimiento en comparación con modelos anteriores. Se analizaron métricas clave:
- Promedio de energía consumida en 50 simulaciones.
- Cantidad de hojas recogidas para evaluar eficiencia.

5) Simulación de Propagación de Enfermedades con Estrategias de Mitigación
Se creó un modelo de simulación basado en mesa para estudiar la propagación de una infección en una población. Se implementaron tres estrategias para reducir el contagio:
- Reducción de la probabilidad de transmisión (de 0.25 a 0.1).
- Menor tiempo de recuperación (de 21 a 14 días).
- Disminución de la tasa de mortalidad (de 0.01 a 0.005).

Las simulaciones muestran cómo estas medidas ayudan a reducir la cantidad de infectados y fallecidos.

# Ejecución
El parcial fue desarrollado en un notebook de Google Colab, se implementaron los puntos 3 y 4 en el notebook, en donde solo es necesario conecatarse a la red para poder ejecutar la implementación de estos puntos, mientras que para la ejecución del punto 5 fue necesario instalar Jupyter y MESA.

