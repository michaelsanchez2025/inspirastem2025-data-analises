<!-- README.md -->
# InspiraSTEM2025 - Ciencia Computacional y Análisis de Datos 

| | |
|---|---|
| **Título** | *Ciencia Computacional y Análisis de Datos* |
| **Fechas** | *Julio 23-25, 2025* |
| **Instructor** | **Michael Sánchez** — masanche@nrao.edu 
| **Bio** | *[Completar]* |

---

## Sobre el instructor  
Soy analísta de datos científicos para el Observatorio Nacional de Radio Astronomía (NRAO) en Charlottesville, Virginia. Investigue una variedad de temas astrofisicas poblaciones de estrellas jóvenes en Orión, fuentes de rayos-X extra-galácticos, radioastronomía de bajo presupuesto. Durante mi Maestría, investigue el contenido de carbono monóxido en discos protoplanetarios y como afectara el desarrollo de planetas en estos discos. Tengo 7 años de experiencia analizando y visualizando datos astrofísicos en Python y divulgación científica del publico.

---

## Descripción del curso  
Este curso de ciencia de datos está diseñado para proporcionar una comprensión integral de los conceptos y técnicas fundamentales necesarios para **organizar, analizar y interpretar** grandes conjuntos de datos. En este curso, los estudiantes aprenderán estrategias y técnicas para manejar datos usando librerías de **Python (pandas, numpy, matplotlib, scipy, statsmodels)** y realizarán análisis gráficos con los cuales aprenderán maneras para mostrar datos, interpretarlos y tomar decisiones de manera significativa. Con estos objetivos, los participantes podrán reducir grandes conjuntos de datos a información manejable para analizar de forma sucinta.

---

## Perfil de estudiantes  
| Requisito | Nivel recomendado |
|-----------|-------------------|
| Excel y Python | Básico |
| Álgebra, geometría, álgebra lineal | Básico–intermedio |
| Estadísticas y Probabilidades | Básico–Intermedio |

---

## Objetivos generales  
1. Entender como y cuando usar paquetes de Python. 
2. Desarrollar .  
3. Emplear integración de Gauss y bases de **Lagrange**.  
4. Analizar estabilidad y estimar errores numéricos.  
5. Transferir las técnicas a problemas astrofísicos de mayor complejidad.

---

## Plan diario y syllabus detallado  

| Día | Objetivos clave | Contenidos y actividades | Software |
|-----|-----------------|--------------------------|----------|
| **1** | • Rol del CFD en ciencia e ingeniería<br>• Generación de cuadrículas<br>• Condiciones iniciales | 1. Presentación del curso<br>2. Proyecto de grupo: *«Agua en un guacal 1-D»*<br>3. **Ejercicio 1** — función Python para generar cuadrículas<br>4. **Ejercicio 2** — codificar condiciones iniciales | Jupyter, NumPy, Matplotlib, IPython |
| **2** | • Bases de Lagrange y aproximación funcional<br>• Forma débil 1-D<br>• Integración numérica (Gauss) | 1. Galerkin continuo vs discontinuo<br>2. **Ejercicio 3** — polinomio de Lagrange evaluado en *x*<br>3. Forma débil de las ecuaciones<br>4. **Ejercicio 4** — matriz de masa por cuadratura de Gauss | Jupyter, NumPy, Matplotlib |
| **3** | • Solución temporal con RK4 / Newton<br>• Forma débil completa<br>• Cierre del proyecto | 1. Forma débil (parte II)<br>2. Método de Newton; RK4<br>3. **Ejercicio 5** — implementar Euler o RK4 para la evolución temporal | Jupyter, NumPy, Matplotlib |

> **Nota:** Cada día combina micro-exposiciones (~20 min), bloques de codificación supervisada (~90 min) y *debrief* (~30 min).

---

## Estructura del repositorio  

| Carpeta / archivo | Descripción |
|-------------------|-------------|
| `notebooks/` | Cuadernos paso a paso (Día 1-3). |
| `src/` | Módulos Python del solver DG. |
| `data/` | Resultados y conjuntos de prueba. |
| `docs/` | Diapositivas y material de referencia. |
| `requirements.txt` | Dependencias mínimas. |

---

## Material de estudio pre-conferencia  

| Recurso | Tipo | Enlace |
|---------|------|--------|
| **CFD Python** (Lorena Barba) — Lecciones 1-3 | Videos + notebooks | <https://github.com/barbagroup/CFDPython> |
| Capítulos 1–3 de **«An Introduction to Computational Fluid Dynamics»** (Versteeg & Malalasekera) | PDF/Libro | *[link institucional]* |
| Tutorial: **NumPy para científicos** | Notebook | `docs/prework_numpy.ipynb` |
| Cuaderno interactivo: **Método de Euler y RK4** | Notebook | `docs/prework_rk.ipynb` |
| Artículo corto: **Discontinuous Galerkin Overview** | PDF | `docs/DG_overview.pdf` |

> **Sugerencia:** Revisa al menos los videos de CFD Python y ejecuta el notebook de NumPy antes del Día 1 para aprovechar al máximo el taller.

---

¡Nos vemos pronto en InspiraSTEM 2025!
