
# Proyecto ISIS-3302 (Modelado, Optimización y Simulación)  
## Planificación eficiente y óptima de rutas de transporte de **LogistiCo**

Este repositorio contiene el desarrollo teórico y computacional para la planificación óptima de rutas de transporte, en el contexto de la empresa **LogistiCo**, como parte del curso **ISIS-3302: Modelado, Optimización y Simulación**.

Se utilizan herramientas como **OSRM** para el cálculo de distancias reales en mapas, y **Pyomo** para la implementación de modelos de optimización.

---

## Estructura del Repositorio

```bash
.
├── case_1_base/                  # Archivos base del Caso 1
├── case_2_base/                  # Archivos base del Caso 2
├── case_3_base/                  # Archivos base del Caso 3
├── results-1/                    # Resultados del Caso 1
├── results-2/                    # Resultados del Caso 2
├── results-3/                    # Resultados del Caso 3
│   └── (CSV + Mapa HTML interactivo con solución)
├── Entrega_1.ipynb               # Planteamiento teórico y formulación matemática
├── Entrega_2.ipynb               # Implementación en Pyomo de los modelos
├── osrm_cache_case1.json         # Caché de distancias para Caso 1 (OSRM)
├── osrm_cache_case2.json         # Caché de distancias para Caso 2 (OSRM)
├── osrm_cache_case3.json         # Caché de distancias para Caso 3 (OSRM)
└── .DS_Store                     # Archivo generado automáticamente por macOS (puede ignorarse)
```

---

## Descripción de los Notebooks

- **Entrega_1.ipynb**:  
  Documento detallado con el planteamiento teórico, formulación de restricciones, variables de decisión, parámetros y objetivos para los casos de estudio.

- **Entrega_2.ipynb**:  
  Implementación práctica de los modelos usando **Pyomo**, junto con la lectura de los datos base, construcción del modelo matemático y visualización de los resultados.

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
