# 🧠 Trabajo Práctico: Algoritmos de Aprendizaje e Inducción de Reglas (FOIL)

Este repositorio contiene la resolución completa del Trabajo Práctico enfocado en el **Algoritmo FOIL** y la **Inducción de Reglas Lógicas** a partir de datos organizados en tablas.

---

## 📌 **Ubicación de las Resoluciones**

> 📓 **Nota Importante:**  
> Toda la resolución teórica, los cálculos manuales de **FOIL Gain** y el desarrollo del código interactivo en Python se encuentran explicados y listos para ejecutar en la notebook del proyecto:  
> 
> 📄 **`tp_3_Algoritmos_FOIL.ipynb`**

---

## 🚀 **Contenido del Trabajo Práctico**

### 🟢 **Ejercicio 1: Identificación de Empleados en Formación**
* 👥 **Procesamiento de Dataset:** Filtrado y división de ejemplos positivos (`en_formacion == True`) y negativos (`en_formacion == False`)
* 🔎 **Análisis de Atributos:** Detección de valores exclusivos para los atributos `edad`, `departamento` y `nivel_educativo`
* 💻 **Algoritmo FOIL en Python:** Implementación de un script para inducir automáticamente las reglas de clasificación

---

### 📊 **Ejercicio 2: Cálculo y Evaluación de FOIL Gain**
* 🧮 **Evaluación de Condición Textual (`nivel_educativo == 'terciario'`):**  
  * Cálculo automatizado en Python
  * Comprobación manual paso a paso con logaritmos en base 2 ($\text{FOIL Gain} = 3.000$)
* 🧮 **Evaluación de Condición Numérica (`edad <= 23`):**  
  * Script en Python para filtrado por rangos
  * Verificación manual de proporciones antes ($P, N$) y después ($p, n$) de aplicar el filtro
* 💡 **Interpretación de Resultados:** Análisis de la precisión y capacidad discriminativa de cada regla inducida

---

## 🛠️ **Tecnologías Utilizadas**

* 🐍 **Python 3.x**
* 📓 **Jupyter Notebook** (Entorno de desarrollo y presentación)
* 📐 **Math Library** (Cálculos de logaritmos e información)

