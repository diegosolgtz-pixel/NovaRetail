## Descripción del proyecto

Este proyecto analiza los factores clave que determinan e impactan los ingresos anuales de la plataforma de e-commerce **NovaRetail+**. A través de un análisis exploratorio de datos y modelado estadístico, se evaluaron variables sociodemográficas y de comportamiento de compra para desmitificar supuestos de negocio, identificar los verdaderos motores de ventas (*revenue drivers*) y proponer estrategias de segmentación de alto impacto.

---

## Objetivos principales

1. **Identificación de drivers de ingreso:** Analizar la correlación entre variables socioeconómicas, campañas de publicidad dirigida y patrones de consumo frente al ingreso anual total.
2. **Desmitificación de variables:** Evaluar el impacto real del nivel socioeconómico y el gasto publicitario en la conversión e ingresos finales.
3. **Estrategia de segmentación:** Desarrollar una propuesta de segmentación conductual (tipo RFM) basada en la recurrencia para maximizar el retorno de inversión (ROI) en marketing.

---

## Estructura del repositorio

* `data/` : Datasets de transacciones, perfiles de usuario y rendimiento de campañas. *(Ajusta según tus carpetas)*
* `notebooks/` : Notebooks con el análisis exploratorio de datos (EDA), análisis de correlación y modelos.
* `scripts/` : Funciones auxiliares para procesamiento y prueba de hipótesis.
* `reports/` : Gráficos clave y resúmenes ejecutivos de los hallazgos.

---

## Tecnologías utilizadas

* **Python:** Análisis exploratorio de datos (EDA), pruebas de correlación y modelado.
* **Pandas & NumPy:** Limpieza, manipulación y agregación de variables transaccionales.
* **Matplotlib & Seaborn:** Visualización de distribuciones, mapas de calor (*heatmaps*) y relaciones bivariadas.
* **Estadística Aplicada:** Análisis de regresión y correlación para identificación de variables predictoras.

---

## Visualizaciones clave y hallazgos

### Principales Hallazgos
* **Determinante crítico:** La **frecuencia de compra mensual** demostró ser el factor clave del negocio, explicando aproximadamente el **97% del ingreso anual**.
* **Mito del nivel socioeconómico:** Se determinó que el nivel socioeconómico presenta una correlación prácticamente nula con el ingreso total generado en la plataforma.
* **Retorno publicitario:** La publicidad dirigida mostró un impacto positivo pero débil en los ingresos finales, sugiriendo que el enfoque publicitario actual no ataca directamente a los usuarios con mayor potencial de recurrencia.

### Recomendaciones / Lecciones
* **Foco en retención (RFM):** Priorizar campañas y programas de fidelización orientados a aumentar la frecuencia de compra mensual por encima de la adquisición masiva.
* **Optimización de pauta:** Reestructurar la segmentación publicitaria para impactar a usuarios con hábitos de compra recurrentes en lugar de basar la pauta únicamente en criterios sociodemográficos.

> *(Aquí puedes insertar una captura de tus mapas de calor o gráficos de correlación)*
> `![Mapa de correlación NovaRetail](link-o-ruta-de-tu-imagen.png)`
