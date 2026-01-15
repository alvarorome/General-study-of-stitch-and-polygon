# General-study-of-stitch-and-polygon

## Descripción general

Este repositorio contiene el desarrollo del **Proyecto final de Geometría Computacional**, cuyo objetivo es el análisis geométrico de un polígono simple generado aleatoriamente y la relación de un punto con dicho polígono.

El proyecto combina **algoritmos clásicos de geometría computacional** con una **visualización interactiva**, permitiendo explorar de forma intuitiva conceptos como convexidad, tangentes, diagonales y pertenencia de puntos a polígonos.

---

## Autores

- Javier Mendoza Guerrero  
- Luis Bertrán Vidal Campos  
- Álvaro Rodríguez Mesa  

---

## Contenidos y funcionalidades

El sistema implementa y visualiza los siguientes aspectos:

- Generación aleatoria de polígonos simples.
- Cálculo del **área signada**.
- Determinación de si un polígono es **convexo o no convexo**.
- Clasificación de vértices:
  - Convexos
  - Cóncavos
  - Colineales
- Determinación de si un punto es **interior o exterior** al polígono mediante el **algoritmo del rayo**.
- Cálculo de:
  - Tangentes desde un punto exterior al polígono.
  - Diagonales internas y externas.
  - Área total del polígono.
- Cálculo y visualización de la **envolvente convexa** mediante el algoritmo de **Graham Scan**.
- Representación gráfica con **convenciones de color** para facilitar la interpretación.

---

## Convenciones de colores en la visualización

- Punto interior: azul claro  
- Punto exterior: morado  
- Vértices convexos: verde  
- Vértices cóncavos: rojo  
- Vértices colineales: naranja  
- Tangentes desde un punto exterior: amarillo  
- Diagonales internas: azul oscuro  
- Diagonales externas: rojo  
- Envolvente convexa: relleno morado claro  

---

## Interactividad

El proyecto incluye una **aplicación interactiva** desarrollada con **SageMath**, accesible desde un entorno web:

- El usuario puede seleccionar el **número de vértices** (entre 3 y 12).
- El polígono y el punto se generan de forma aleatoria.
- La visualización se actualiza automáticamente mostrando:
  - Clasificación de vértices.
  - Diagonales.
  - Tangentes.
  - Envolvente convexa.
  - Información textual de los resultados geométricos.

---

## Complejidad algorítmica (resumen)

- Área signada: **O(1)**
- Clasificación de vértices: **O(n)**
- Punto en polígono (algoritmo del rayo): **O(n)**
- Cálculo de tangentes: **O(n²)**
- Cálculo de diagonales: **O(n³)** en el peor caso
- Generación de polígono simple: **O(n log n)**
- Área total del polígono: **O(n)**

---

## Aplicaciones

Este proyecto tiene aplicaciones directas en:

- **Robótica y navegación autónoma** (detección de colisiones y planificación de rutas).
- **Optimización geométrica** y análisis de regiones.
- **Arquitectura y diseño urbano**.
- **Visión por computador** (análisis de contornos).
- **Inteligencia artificial y simulación de entornos**.

---

## Tecnologías utilizadas

- **Python**
- **SageMath**
- **HTML / CSS**
- **JavaScript (SageCell)**

---

## Estructura del repositorio

- Proyecto_Final_Geometria_Javier_Bertran_Alvaro.ipynb
- Web_Javier_Bertran_Alvaro.html
- README.md
