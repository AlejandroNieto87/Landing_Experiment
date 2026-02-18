# 📊 Landing Page A/B Testing: Optimización de Conversión con Enfoque CIPO

[cite_start]Este proyecto consiste en la validación estadística de un experimento A/B ejecutado en la página de inicio (landing page) de una empresa de ecommerce[cite: 3, 4]. [cite_start]El objetivo principal fue determinar qué versión (A o B) maximiza la tasa de conversión y el valor económico por usuario[cite: 5, 9].

## 🎯 Objetivo del Negocio
[cite_start]Identificar diferencias significativas entre las versiones de la página y traducir los resultados en recomendaciones accionables para optimizar la estrategia de marketing y el diseño web[cite: 9, 15].

## 🛠️ Stack Tecnológico
* **Python**: Análisis de datos y computación estadística.
* [cite_start]**Pandas**: Manipulación y limpieza de datos[cite: 25].
* [cite_start]**SciPy & Statsmodels**: Implementación de pruebas t de Student, Z-test para proporciones y Chi-cuadrado[cite: 19].
* [cite_start]**Seaborn & Matplotlib**: Visualización de métricas de negocio y comportamiento de usuarios[cite: 21, 57].

---

## 🚀 Metodología CIPO (Conocer, Identificar, Proponer, Optimizar)

### [cite_start]1. **C - Conocer (Validación de Datos)** [cite: 45]
* [cite_start]Exploración del dataset `landing_experiment.csv` con información de usuarios, región, dispositivo y fuente de tráfico[cite: 7, 25].
* [cite_start]Verificación de la integridad de la variable `gasto`, asegurando que solo existan valores mayores a cero en usuarios convertidos[cite: 34].

### [cite_start]2. **I - Identificar (Análisis Estadístico)** [cite: 47]
* [cite_start]**Comparación de Gasto Promedio**: Uso de la **Prueba t de Student** para muestras independientes para identificar qué versión genera más valor por cliente[cite: 11, 19].
* [cite_start]**Comparación de Tasa de Conversión**: Aplicación del **Z-test** para determinar la efectividad relativa entre la página A (control) y la página B (prueba)[cite: 12, 19].
* [cite_start]**Análisis de Segmentos**: Pruebas de **Chi-cuadrado** para evaluar si la conversión depende de la fuente de tráfico o del tipo de usuario (Nuevo vs. Recurrente)[cite: 13, 14, 19].

### [cite_start]3. **P - Proponer (Insights Ejecutivos)** [cite: 22, 45]
* [cite_start]Interpretación de valores $p$ (p-values) desde una perspectiva de impacto económico[cite: 20, 50].
* [cite_start]Identificación de canales de tráfico de alto rendimiento para optimizar la inversión[cite: 15, 45].

### [cite_start]4. **O - Optimizar (Recomendaciones)** [cite: 45]
* [cite_start]Definición de la versión de página a implementar basada en evidencia estadística sólida[cite: 42].
* [cite_start]Estrategias de segmentación para usuarios recurrentes vs. nuevos prospectos[cite: 38].

---

## 📂 Estructura del Proyecto
* [cite_start]`/datasets/landing_experiment.csv`: Información de usuarios expuestos al experimento[cite: 24].
* [cite_start]`Notebook_Analisis_AB.ipynb`: Proceso completo de limpieza, pruebas estadísticas y visualizaciones[cite: 43, 60].

---

## 🤝 Conecta conmigo
Si buscas transformar datos en decisiones estratégicas bajo el método CIPO:
* **LinkedIn**: [linkedin.com/in/alejandronieto-cipo-mentor-consultor](https://linkedin.com/in/alejandronieto-cipo-mentor-consultor)
* **Sitio Web**: [alejandronietoalvarez.com](https://alejandronietoalvarez.com)
* **Substack**: [CIPO para líderes](https://alejandronieto.substack.com/)
