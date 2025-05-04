
# 📊 **Análisis comparativo de actividades en museos de Montevideo (2023–2024)**

Este proyecto tiene como objetivo analizar y comparar las exposiciones realizadas en tres museos de Montevideo: **Museo del Azulejo**, **Centro de Exposiciones Subte** y **Museo de Historia del Arte (MuHar)**, durante los años 2023 y 2024. A través de este análisis, se pretende identificar patrones en la programación y diversidad cultural, y proyectar tendencias para el año 2025.

## 🎯 **Objetivo**

El objetivo principal de este proyecto es analizar la distribución y las características de las actividades culturales realizadas en tres importantes museos de Montevideo: el Museo del Azulejo, el Centro de Exposiciones Subte, y el Museo de Historia del Arte (MuHar), durante los años 2023 y 2024. Este análisis pretende identificar patrones de programación y diversidad cultural dentro de la oferta museística de Montevideo, y, a partir de ello, generar una predicción para el año 2025.

## 📂 **Origen de los Datos**

Los datos provienen del portal de **Datos Abiertos de la Intendencia de Montevideo**:
- [Dataset Museos](https://ckan.montevideo.gub.uy/dataset/museos)

Se utilizaron datasets en formato CSV correspondientes a las actividades realizadas en los años 2023 y 2024.

## 🔧 **Herramientas utilizadas**

- **Google Colab**: para análisis, limpieza y visualización de datos.
- **Pandas y NumPy**: para manipulación y procesamiento de datos.
- **Seaborn y Matplotlib**: para gráficos y visualización de relaciones.
- **Scikit-learn**: para el análisis predictivo, específicamente utilizando el modelo **k-Nearest Neighbors (kNN)**.
- **SciPy**: para aplicar las pruebas estadísticas, como **Chi-cuadrado**.

## 🧹 **Procesamiento y Análisis**
- Se eligio para trabajar las siguientes columnas **tipo de actividad**, **público destinatario** e **inciativa del museo**
El análisis incluyó:
- **Limpieza y Normalización de Datos:¨** Se estandarizaron las actividades,público destinatario e incitiva. Además, se corrigieron errores de codificación y ortografía en los dataset y se eliminaron los valores nulos.
- **Análisis Descriptivo**: Se generaron **tablas de contingencia** y gráficos de barras para explorar la relación entre **tipo de actividad** y **público destinatario**, así como **tipo de actividad** e **iniciativa del museo**. Las visualizaciones facilitaron la identificación de patrones y tendencias.
- **Análisis Predictivo**: Se aplicó el modelo **k-Nearest Neighbors (kNN)** para predecir la cantidad o tipo de actividades para el año 2025. Este modelo se entrenó utilizando los datos de 2023 y 2024 para proyectar las actividades más frecuentes y los públicos más propensos a asistir a ellas.
- **Evaluación de Modelos**: Para evaluar el rendimiento del modelo predictivo, se utilizó la **matriz de confusión**, que permite visualizar la precisión de las predicciones y los errores por clase.

- Posteriormente se analizaron las conclusiones correspondientes según lo obtenido en el punto anterior

## 📈 **Próximos pasos**

- Implementar más modelos predictivos y ajustar el **kNN** para mejorar la precisión en las proyecciones para 2025. 💻

---

**Realizado por Lucía Puppo[alerome897@gmail.com] en el marco del proyecto final de Data.Uy** 🚀

---

