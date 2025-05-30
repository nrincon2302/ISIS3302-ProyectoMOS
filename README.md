
# Proyecto ISIS-3302 (Modelado, Optimización y Simulación)  
## Planificación eficiente y óptima de rutas de transporte de **LogistiCo**

Este repositorio contiene el desarrollo teórico y computacional para la planificación óptima de rutas de transporte, en el contexto de la empresa **LogistiCo**, como parte del curso **ISIS-3302: Modelado, Optimización y Simulación**.

Se utilizan herramientas como **OSRM** para el cálculo de distancias reales en mapas, y **Pyomo** para la implementación de modelos de optimización.

---

## Estructura del Repositorio


```bash
.
├── Etapa2/
│   ├── cache/
│   ├── data/
│   │   ├── case_1_base/ # Archivos base del Caso 1
│   │   ├── case_2_base/ # Archivos base del Caso 2
│   │   └── case_3_base/ # Archivos base del Caso 3
│   └── out/
│       ├── results-1/   # Resultados del Caso 1
│       ├── results-2/   # Resultados del Caso 2
│       └── results-3/   # Resultados del Caso 3
├── Etapa3/
│   ├── assets/          # Imagenes guardadas de los mapas generados para cada caso
│   ├── cache/           # Caché de distancias para Caso base, 2 y 3 (OSRM) para GA y Pyomo
│   ├── calibracion/     # Datos e imagenes con los valores de estadisticas con la busqueda de parametros
│   ├── data/
│   │   ├── Proyecto_A_Caso2/    # Archivos base del Caso 2 Entrega 3
│   │   ├── Proyecto_A_Caso3/    # Archivos base del Caso 3 Entrega 3
│   │   └── Proyecto_A_CasoBase/ # Archivos base del Caso Base Entrega 3
│   ├── out/
│   │   ├── results-2/           # Archivos html del mapa y csv con la solcucion del caso 2
│   │   ├── results-3/           # Archivos html del mapa y csv con la solcucion del caso 3
│   │   ├── results-Base/        # Archivos html del mapa y csv con la solcucion del caso Base
│   │   ├── results-convergencia-2/    # Imagen del grafico de convergencia para el caso 2
│   │   ├── results-convergencia-3/    # Imagen del grafico de convergencia para el caso 3
│   │   └── results-convergencia-Base/ # Imagen del grafico de convergencia para el caso Base
│   ├── reexecution/
│   │   ├── metrics_Etapa2/      # csv con las metricas obtenidas al reejecutar el notebook de la etapa 2 con los nuevos datos
│   │   ├── results-1/           # Resultados para el caso 1 con los datos nuevos de la etapa 3 con Pyomo
│   │   ├── results-2/           # Resultados para el caso 2 con los datos nuevos de la etapa 3 con Pyomo
│   │   └── results-3/           # Resultados para el caso 3 con los datos nuevos de la etapa 3 con Pyomo
│   └── visualizacion_comparativa/ # Imagen con estadisticas para seccion 4.3
├── Entrega_1.ipynb              # Planteamiento teórico y formulación matemática
├── Entrega_2.ipynb              # Implementación en Pyomo de los modelos
├── Entrega_2_ReExecute.ipynb    # Copia de la Entrega 2 reejecutada con los datos de la etapa 3
├── Entrega_3.ipynb              # Implementación con GA.
├── README.md                    # El presente archivo README
├── __pycache__/
```

---

## Descripción de los Notebooks

- **Entrega_1.ipynb**:  
  Documento detallado con el planteamiento teórico, formulación de restricciones, variables de decisión, parámetros y objetivos para los casos de estudio.

- **Entrega_2.ipynb**:  
  Implementación práctica de los modelos usando **Pyomo**, junto con la lectura de los datos base, construcción del modelo matemático y visualización de los resultados.

- **Entrega_2_ReExecute.ipynb**:  
  Re-ejecución y validación de los modelos de la Entrega 2 con datos de la etapa 3.

- **Entrega_3.ipynb**:  
  Implementación práctica de los modelos usando **GA**. Tambien incluye experimentación avanzada, calibración y análisis comparativo de resultados.

---

## Resultados

Cada carpeta `results-X/` (donde X es el número del caso) contiene:

- Un archivo `.csv` con el informe de solución del modelo.
- Un archivo `.html` con un mapa interactivo visualizable desde cualquier navegador.

---

## Requisitos

- Python 3.x  
- Jupyter Notebook  
- Bibliotecas: `pandas`, `numpy`, `pyomo`, `matplotlib`, `osrm`, entre otras necesarias para análisis y visualización.

---

## Autores

- **Paulina Arrazola Vernaza** - 202020631  
- **Santiago Alejandro Jaimes Puerto** - 201912921  
- **Nicolás Rincón Sánchez** - 202021963
