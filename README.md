# 🚑 Proyecto de Predicción de Riesgo de ACV con Apache Spark

## 📝 Descripción

Este proyecto se centra en el análisis y modelado de un conjunto de datos clínicos con el fin de predecir el riesgo de accidente cerebrovascular (ACV) en pacientes. A partir de un archivo CSV cargado desde un repositorio de GitHub, se realiza un proceso de limpieza y exploración de los datos, transformación de la información categórica mediante indexación, y construcción de un modelo de clasificación basado en Árboles de Decisión utilizando Apache Spark. El rendimiento del modelo se evalúa a través de métricas clave, con especial énfasis en la precisión clínica para identificar correctamente a los pacientes con riesgo de ACV.

---

## 🛠️ Tecnologías Utilizadas

- **Apache Spark (PySpark)**: Para la manipulación, transformación y modelado de datos en gran escala.
- **NumPy**: Para realizar cálculos numéricos auxiliares.
- **Matplotlib & Seaborn**: Para la visualización gráfica de datos y resultados.
- **pyspark.sql**: Para trabajar con DataFrames distribuidos y realizar consultas estructuradas.

---

## ⚙️ Proceso Realizado

1. **Carga y Renombrado de Columnas**  
   Se cargó el dataset desde GitHub y se estandarizaron los nombres de las columnas para mejorar su manejo.

2. **Verificación del Esquema del DataFrame**  
   Se revisaron los tipos de datos y la estructura del DataFrame para garantizar su correcta interpretación.

3. **Exploración de Categorías y Datos Faltantes**  
   Se analizaron las variables categóricas, se identificaron valores nulos y se procedió con la limpieza de datos.

4. **Cálculo del Promedio de IMC**  
   Se implementó una función para calcular el Índice de Masa Corporal (IMC) promedio y detectar anomalías en los valores.

5. **Visualización Gráfica**  
   Se generaron gráficos para comprender la distribución de las variables y su relación con el riesgo de ACV.

6. **Preparación y Transformación de Datos**  
   Las variables fueron indexadas y ensambladas en un pipeline de Spark para facilitar el entrenamiento del modelo.

7. **Construcción del Modelo de Clasificación (Árbol de Decisión)**  
   Se entrenó un modelo supervisado utilizando un Árbol de Decisión para predecir la variable objetivo (riesgo de ACV).

8. **Evaluación del Modelo**  
   Se evaluó el rendimiento del modelo utilizando métricas como accuracy, precision, recall, F1 score y AUC-ROC, además de la matriz de confusión.

---

## 📈 Resultados y Beneficios

Este proyecto proporciona una herramienta predictiva capaz de identificar a pacientes con alto riesgo de sufrir un ACV. Esta herramienta puede ser utilizada en entornos clínicos para priorizar evaluaciones y tratamientos preventivos, ayudando a optimizar el uso de recursos médicos y mejorar la atención al paciente. Además, al balancear la detección efectiva de casos reales y minimizar las falsas alarmas, contribuye a una mayor eficiencia en la toma de decisiones clínicas.

---

## 🧑‍💻 **Autor**

**[Juan Pablo Arias](https://github.com/JuanParias29/Perfil_GitHub)**

---

## 📅 **Curso**

**Procesamiento de Datos a Gran Escala**  
* Pontificia Universidad Javeriana
* Docente: [John Corredor, PhD](https://github.com/corredor-john)
