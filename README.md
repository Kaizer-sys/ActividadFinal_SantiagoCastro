# SISTEMA KAIZER LEGENDARIO

## Descripción del Proyecto

Este proyecto es una aplicación de consola en Python diseñada para **analizar números enteros positivos** y determinar si cumplen con las propiedades de ser un **Número de Armstrong** o un **Número Perfecto**.

La aplicación incluye un menú interactivo y genera patrones visuales en la terminal para representar cada tipo de número.

## Características Principales

* **Análisis de Propiedades:**
    * Verifica si un número es **Perfecto** (igual a la suma de sus divisores propios).
    * Verifica si un número es **Armstrong** (igual a la suma de sus dígitos elevados a la potencia del número de dígitos).
* **Interactividad:** Posee un menú simple para seleccionar entre análisis de números o explicaciones de las propiedades.
* **Salida Visual:** Utiliza la librería `colorama` y funciones de pausa (`time.sleep`) para ofrecer una salida con colores y animaciones de patrones (`patron_armstrong`, `patron_perfecto`).

---

## Inspiración y Origen

El desarrollo de este sistema surgió de la integración y mejora de conceptos vistos en ejercicios previos, específicamente:

* **Ejercicio 24:** Proporcionó la base para la función **`numero_perfecto(n)`**, enfocándose en la lógica de sumar los divisores propios de un número para verificar su perfección.
* **Ejercicio 29:** Inspiró la creación de la función **`numero_armstrong(n)`**, implementando la lógica de descomposición de dígitos y el cálculo de potencias para verificar la propiedad de Armstrong.
* **Ejercicio 28:** Inspiración para construir patrones visuales numéricos.

El resultado es un sistema más sólido, atractivo y funcional que combina **matemáticas, lógica y visualización**.

---
