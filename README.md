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

## 1. El "Efecto Madrid"

A diferencia de Barcelona y Bilbao, que logran estabilizar a su plantilla tras el segundo año, la sede de Madrid sufre un fallo estructural de fidelización que abarca los primeros 5 años.

* **La Anomalía:** Madrid pierde al **33%** de los perfiles de entrada (0-2 años) y mantiene una tasa crítica del **17%** en perfiles consolidados (2-5 años), duplicando a otras sedes en esta franja.
* **Las Causas (El Doble Golpe):**
    1.  **Burnout Temprano:** El **60%** de las dimisiones están vinculadas a horas extra, creando un fuerte deseo de salida.
    2.  **Falta de Arraigo:** La política de incentivos no está actuando como barrera. **En Madrid, casi 2 de cada 3 empleados que abandonan (66%) no poseen Stock Options**, lo que elimina cualquier coste de oportunidad por irse.

---

## 2. Validación: El Poder de los Incentivos

Los datos globales confirman que las Stock Options actúan como una herramiento de prevención eficaz contra la rotación, reduciendo drásticamente el riesgo de fuga.

* **Tasa de Dimisión SIN Stock Options:** 🔴 **22,3%** (Riesgo Alto)
* **Tasa de Dimisión CON Stock Options:** 🟢 **8,7%** (Riesgo Bajo)

** La Oportunidad en Madrid:**
Actualmente, la penetración de Stock Options en Madrid es idéntica a la de sedes con bajo riesgo (Bilbao/Barcelona). Dado que Madrid sufre una presión laboral mayor (horas extra), **la herramienta está infrautilizada para este contexto de riesgo**. No se está usando el incentivo para compensar el desgaste ("Burnout"), dejando al talento expuesto a ofertas de la competencia.

*(Aquí puedes insertar tu gráfico de barras comparativo de Tasa de Dimisión: Con Stock vs Sin Stock)*

---

## 3. Caso de Negocio: El Coste de la Inacción

Si no se inerviene en el perfil crítico (**Madrid / 0-5 años**), el impacto financiero se mantendrá. A continuación, se detalla el ROI estimado de la intervención propuesta.

| Concepto | Impacto Financiero | Descripción |
| :--- | :--- | :--- |
| ** Coste Actual ** | **-930.000 € / año** | Pérdida anual por rotación del colectivo objetivo (Reemplazo + Productividad). |
| ** Inversión ** | **-250.000 € / año** | Coste estimado de refuerzos para reducir horas extra y plan de Stock Options. |
| ** BENEFICIO NETO** | **+680.000 € / año** | **Ahorro real capturado al frenar la fuga de talento.** |

> **Conclusión Financiera:** Por cada euro invertido en retención en Madrid, la compañía recupera **3,7€** en costes de rotación evitados.

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
