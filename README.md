# People Analytics: Estrategia de Retención de Talento & Diagnóstico de Fuga


## Resumen Ejecutivo

Este proyecto analiza la rotación de empleados en una compañía farmacéutica con sedes en Madrid, Barcelona y Bilbao. El objetivo principal fue identificar las causas raíz de las dimisiones y cuantificar su impacto financiero, que se estima con un **coste real de rotación que asciende a 5.8M€**.

El análisis reveló que la **crisis de rotación se concentra geográficamente en la sede de Madrid**, donde la cultura local de sobrecarga laboral (horas extra) colisiona con una política corporativa de incentivos (Stock Options) insuficiente para retener al talento en este mercado, afectando tanto a juniors como a perfiles consolidados.

---

## Dashboard Overview
*(Aquí inserta una captura general de tu dashboard principal en Power BI)*
![Dashboard General](img/dashboard_overview.png)

---

## Hallazgos Clave (Key Insights)

### 1. El "Efecto Madrid"
Mientras que Barcelona y Bilbao mantienen tasas de rotación estables, **Madrid presenta una tasa crítica del 33% en perfiles junior (0-2 años)**.
* **La Causa:** No es la antigüedad, es el "burnout". El **60%** de las personas que dimiten en Madrid realizaban horas extra habitualmente (vs solo 24% de los que se quedan).

### 2. La Brecha de los Incentivos (Stock Options)
Se descubrió una correlación directa entre la posesión de acciones y la retención.
* **Sin Stock Options:** 22.3% Tasa de Dimisión.
* **Con Stock Options (Nivel 1-4):** 8.7% Tasa de Dimisión.
* *Insight:* En Madrid, los perfiles que dimiten tienen un nivel de Stock Options de **0.5** (casi nulo) frente al **0.87** de los retenidos.

*(Aquí inserta tu gráfico de barras comparativo de Stock Options que diseñamos)*
![Impacto Stock Options](img/stock_options_chart.png)

### 3. El Perfil de Riesgo
El empleado con mayor probabilidad de fuga es:
* Sede: Madrid
* Antigüedad: 0 - 5 años
* Condición: Realiza Horas Extra + Sin Stock Options.

**El Impacto:** Este segmento representa el **[X]%** del total de las pérdidas financieras por rotación.
---

## Stack Tecnológico & Metodología
* **Herramientas:** Power BI (DAX, Modelado), Python (Pandas, Matplotlib para validación estadística).
* **Técnicas:**
    * Limpieza de datos y clasificación de variables (ETL).
    * Creación de columnas calculadas para segmentación (ej. *Status Stock*).
    * Análisis comparativo multidimensional (Sede vs. Antigüedad).

---

## Recomendaciones Estratégicas
Basado en los datos, se propuso al negocio un plan de acción de 3 puntos:

1.  **Programa "Semáforo Rojo" en Madrid:** Auditoría y limitación de horas extra para empleados hasta los 5 años de antigüedad.
2.  **Estrategia "Golden Handcuffs":** Adelantar la asignación de Stock Options al primer año para perfiles Junior de alto potencial en Madrid, reduciendo su riesgo de fuga del 22% al 8%.
3.  **Recálculo de Costes:** Ajuste del KPI de coste de rotación para reflejar el impacto real en el P&L y justificar la inversión en retención.

---
*Autor: [Tu Nombre]*
*Contacto: [Tu LinkedIn / Email]*
