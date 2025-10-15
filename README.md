# PERFILES DE DIGITALIZACIÓN EN MYPES PERUANAS: ANÁLISIS MULTIDIMENSIONAL MEDIANTE TÉCNICAS DE CLUSTERING EN RUTA DIGITAL (2021-2024)

## 📖 Resumen del Proyecto

Este repositorio contiene los archivos y el código fuente desarrollados para la Tesis de Maestría en Ciencia de Datos, cuyo objetivo es **segmentar e interpretar los perfiles de madurez digital de las Micro y Pequeñas Empresas (MYPEs) peruanas** que completaron el test de digitalización en la plataforma **Ruta Digital** entre 2021 y 2024.

## 🎯 Objetivos Específicos

El análisis se estructura en torno a los siguientes objetivos, que se desarrollan secuencialmente en el *notebook* principal:

| Objetivo | Descripción | Archivos Relevantes |
| :--- | :--- | :--- |
| **OE1** | Caracterizar las MYPEs peruanas de Ruta Digital mediante análisis exploratorio de datos, examinando la distribución y variabilidad de las puntuaciones en las seis dimensiones del test de digitalización. | `DS8_RUTADIGITAL2021al2024_anonimizado.csv` |
| **OE2** | Determinar la técnica de *clustering* más adecuada para segmentar las MYPEs, evaluando diferentes algoritmos y métricas de validación estadística. | `DS8_RUTADIGITAL2021al2024_anonimizado.csv` |
| **OE3** | Interpretar los perfiles digitales identificados mediante *clustering*, analizando sus fortalezas y debilidades, contextualizando los resultados con variables sectoriales y geográficas derivadas, para destacar necesidades específicas de intervención focalizada. | `df_cluster_final.csv` |

## 📁 Archivos Clave del Repositorio

| Archivo | Descripción | Uso Principal |
| :--- | :--- | :--- |
| **`TESIS_PERFILES_RUTA_DIGITAL.ipynb`** | **Código fuente principal.** *Notebook* de Python creado en Google Colab que contiene el código completo para el preprocesamiento de datos, Análisis Exploratorio de Datos (AED), el *Clustering* (OE2) y la interpretación de perfiles (OE3). | Reproducción total del análisis. |
| **`DS8_RUTADIGITAL2021al2024_anonimizado.csv`** | **Dataset principal (fijado).** Contiene los datos anonimizados de las MYPEs, incluyendo las puntuaciones en las dimensiones del test. Se incluye esta versión específica (fecha 17/03/2025) para garantizar la **reproducibilidad** de los OE1 y OE2. | **OE1** y **OE2**. |
| **`df_cluster_final.csv`** | **Dataset derivado.** Contiene el *dataset* utilizado específicamente para el OE3, el cual incluye **variables derivadas** y está listo para analizar los resultados del *clustering*. | **OE3**. |

## 🔗 Fuente de Datos Original

El *dataset* base fue obtenido de la plataforma **Datos Abiertos de Perú** y corresponde al registro de MYPEs que culminaron el test de digitalización en la plataforma Ruta Digital.

* **Enlace de la fuente original:** [https://datosabiertos.gob.pe/dataset/registro-de-mypes-que-culminaron-el-test-de-digitalizaci%C3%B3n-en-la-plataforma-ruta-digital](https://datosabiertos.gob.pe/dataset/registro-de-mypes-que-culminaron-el-test-de-digitalizaci%C3%B3n-en-la-plataforma-ruta-digital)

## ⚙️ Cómo Ejecutar el Proyecto

1.  **Clonar el Repositorio:** Descarga los archivos a tu entorno local.
2.  **Entorno de Ejecución:** Se recomienda usar **Google Colab** o un entorno de Jupyter Notebook/Lab con **Python 3.x**.
3.  **Preparación:** Asegúrate de que los dos archivos `.csv` estén en el mismo directorio de trabajo que el *notebook* `TESIS_PERFILES_RUTA_DIGITAL.ipynb`.
4.  **Librerías:** El *notebook* utiliza librerías comunes de Ciencia de Datos (ej. Pandas, NumPy, Scikit-learn, Matplotlib, Seaborn). Si alguna no está instalada, deberá ser instalada manualmente en el entorno local (ej. `pip install [nombre_librería]`).
5.  **Ejecutar el Notebook:** Ejecuta el código celda por celda para replicar el análisis completo de la tesis.
