# proyecto_final_IDO
# APLICACIÓN DE HEURÍSTICAS PARA LA RESOLUCIÓN DEL PROBLEMA DEL AGENTE VIAJERO

![Red de Grafos](heuristica.png)

## Descripción del Proyecto

El problema del agente viajero (TSP) es uno de los problemas más estudiados en la optimización combinatoria debido a su relevancia en aplicaciones como la planificación logística y el diseño de redes de telecomunicaciones. Este proyecto presenta una comparación entre el algoritmo del **Vecino Más Cercano** y un enfoque **híbrido** que combina dicho algoritmo con la heurística **2-opt**, utilizando tres conjuntos de datos con coordenadas correspondientes a Qatar, Uruguay y Zimbabwe.

## Resultados Principales

- **Vecino Más Cercano**:
  - Eficiente para instancias pequeñas o cuando el tiempo de ejecución es un factor crítico.
  - Genera soluciones rápidas pero con rutas de mayor costo.

- **Enfoque Híbrido (Vecino + 2-opt)**:
  - Adecuado para instancias más grandes o cuando la calidad de la solución es prioritaria.
  - Encuentra rutas de menor costo a expensas de un mayor tiempo de ejecución.

Este trabajo resalta la importancia de elegir la estrategia adecuada dependiendo del balance requerido entre tiempo de ejecución y calidad de la solución.


## Cómo Usar este Repositorio

1. **Clonar el repositorio**:
   ```bash
   git clone https://github.com/maariaroomero/proyecto_final_IDO.git
