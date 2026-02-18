# 🚀 Proyecto 8: Validando Hipótesis de Negocio con Pruebas Estadísticas

![A/B Testing](https://img.shields.io/badge/A%2FB_Testing-Validation-red) ![Python](https://img.shields.io/badge/Python-3.9+-green) ![Ecommerce](https://img.shields.io/badge/Ecommerce-Analysis-yellow)

## 🎯 Objetivo del Proyecto
[cite_start]El objetivo es evaluar un experimento A/B ejecutado en la página de inicio (landing page) de una empresa de ecommerce para identificar diferencias significativas entre dos versiones (A y B)[cite: 4]. [cite_start]Se busca optimizar la tasa de conversión y el valor económico por usuario mediante decisiones basadas en evidencia estadística sólida, considerando el comportamiento por canal y tipo de usuario[cite: 5, 9].

## 📊 Datasets Utilizados
[cite_start]Se trabajó con un conjunto de datos centralizado que representa la exposición de los usuarios[cite: 27]:
* [cite_start]**`landing_experiment.csv`**: Información de usuarios incluyendo región, dispositivo, fuente de tráfico, tipo de usuario, conversión y gasto[cite: 7, 25].
* [cite_start]**Variable Objetivo**: `converted` (binaria) e ingresos generados (`gasto`), validando que el gasto solo sea > 0 cuando existe una compra exitosa[cite: 31, 34].

## 🛠️ Metodología de Análisis (CIPO)
[cite_start]El flujo de trabajo se alineó con la metodología CIPO para garantizar impacto de negocio[cite: 45]:

1.  [cite_start]**Conocer:** Carga y validación de datos para asegurar la calidad del experimento y confirmar que los grupos están balanceados[cite: 39, 45].
2.  [cite_start]**Identificar:** * Comparación de **gasto promedio** por usuario convertido mediante pruebas estadísticas de diferencia de medias[cite: 11, 45].
    * [cite_start]Evaluación de la **tasa de conversión** entre versiones A y B para identificar la más efectiva[cite: 12, 45].
3.  [cite_start]**Proponer:** Análisis de la influencia de la **fuente de tráfico** y el **tipo de usuario** (nuevo vs. recurrente) en la conversión[cite: 13, 14, 45].
4.  [cite_start]**Optimizar:** Generación de visualizaciones e **insights ejecutivos** para respaldar recomendaciones de inversión y diseño[cite: 15, 45, 57].

## 📈 Hallazgos Clave
* [cite_start]**Valor Económico:** Determinación de si una versión de la landing page genera un ticket promedio mayor por cliente[cite: 11].
* [cite_start]**Efectividad de Conversión:** Validación de qué página atrae un mayor volumen de usuarios convertidos con significancia estadística[cite: 12].
* [cite_start]**Eficiencia de Canales:** Identificación de las fuentes de tráfico más rentables para optimizar el presupuesto de marketing[cite: 13, 15].

## 🚀 Cómo Ejecutar el Proyecto
Para reproducir este análisis:
1. Clona el repositorio: `git clone https://github.com/tu-usuario/landing-page-ab-analysis.git`
2. Abre el notebook estructurado en **Jupyter** o **Google Colab**.
3. [cite_start]Asegúrate de que el archivo `/datasets/landing_experiment.csv` esté disponible en el entorno[cite: 7].
4. [cite_start]Ejecuta las celdas secuencialmente para validar supuestos y observar las conclusiones estadísticas[cite: 61].

---

## 🤝 Conecta conmigo
Si buscas transformar datos en decisiones estratégicas bajo el método CIPO:
* **LinkedIn**: [linkedin.com/in/alejandronieto-cipo-mentor-consultor](https://linkedin.com/in/alejandronieto-cipo-mentor-consultor)
* **Sitio Web**: [alejandronietoalvarez.com](https://alejandronietoalvarez.com)
* **Substack**: [CI PO demos avanzar](https://alejandronieto.substack.com/)
