# Proyecto-Mecanica-Celeste

Proyecto académico del curso de Mecánica Celeste enfocado en el modelado numérico de trayectorias orbitales, con énfasis en el asteroide **99942 Apophis** y su evolución dinámica bajo un modelo de N-cuerpos.

<img src="GIF apophis.gif" alt="Modelación de la trayectoria de 99942 Apophis">

## Contexto del repositorio

Este repositorio reúne notebooks y recursos para estudiar, simular y visualizar sistemas gravitacionales en el marco de la mecánica celeste newtoniana. El trabajo combina formulación teórica, integración numérica y visualización de resultados para analizar la dinámica orbital de objetos cercanos a la Tierra.

## Notebook principal

El notebook principal es **`Apophis1.ipynb`**, donde se desarrolla el flujo completo del proyecto:
- construcción del problema de N-cuerpos,
- obtención de condiciones iniciales (efemérides),
- integración numérica del sistema dinámico,
- análisis y visualización de la trayectoria de Apophis.

## Objetivo general

Modelar y analizar la trayectoria del asteroide 99942 Apophis mediante técnicas de mecánica celeste y simulación numérica de N-cuerpos.

## Objetivos específicos

- Formular el problema dinámico gravitacional usando un enfoque de N-cuerpos.
- Implementar simulaciones numéricas para la evolución temporal del sistema.
- Integrar datos astronómicos para condiciones iniciales realistas.
- Visualizar de forma estática y animada la dinámica orbital de Apophis.
- Interpretar los resultados obtenidos desde el punto de vista físico-matemático.

## Estructura del repositorio

- **`Apophis1.ipynb`**: notebook principal del proyecto (simulación y análisis de Apophis).
- **`mecanica_celeste_setup.ipynb`**: notebook base para preparar entorno y dependencias.
- **`GIF apophis.gif`**: animación de referencia de la trayectoria modelada.
- **`requirements.txt`**: dependencias Python del proyecto.
- **`pyproject.toml`**: configuración de empaquetado del proyecto.
