# People Analytics: Estrategia de Retención de Talento & Diagnóstico de Fuga

## Resumen Ejecutivo
Este proyecto analiza la rotación de empleados en una compañía farmacéutica con sedes en Madrid, Barcelona y Bilbao. El objetivo principal fue identificar las causas raíz de las dimisiones y cuantificar su impacto financiero anual, estimado en un **coste real de rotación de 5.8M€**.

El análisis reveló que la **crisis de rotación se concentra geográficamente en la sede de Madrid**, donde la cultura local de sobrecarga laboral (horas extra) colisiona con una política corporativa de incentivos (Stock Options) insuficiente para retener al talento en este mercado, afectando tanto a juniors como a perfiles consolidados.

---

## Dashboard Overview
*(Vista general del cuadro de mando interactivo)*

![Dashboard General](img/dashboard_overview.png)
*(Asegúrate de subir la imagen a una carpeta 'img' o cambiar esta ruta)*

---

## Hallazgos Clave (Key Insights)

### 1. El "Efecto Madrid": Fallo Estructural
A diferencia de Barcelona y Bilbao, que logran estabilizar a su plantilla tras el segundo año, la sede de Madrid sufre una fuga continua que abarca los primeros 5 años.

* **La Anomalía:** Madrid pierde al **33%** de los perfiles de entrada (0-2 años) y mantiene una tasa crítica del **17%** en perfiles consolidados (2-5 años), duplicando a otras sedes.
* **Las Causas (El Doble Golpe):**
    1.  ** Burnout Temprano:** El **60%** de las dimisiones están vinculadas a horas extra, creando un fuerte deseo de salida.
    2.  ** Falta de Arraigo:** La política de incentivos no actúa como barrera. **En Madrid, casi 2 de cada 3 empleados que abandonan (66%) no poseen Stock Options**, lo que elimina el coste de oportunidad por irse.

### 2. Validación: El Poder de los Incentivos
Los datos globales confirman que las Stock Options actúan como una **herramienta de prevención eficaz**, reduciendo drásticamente el riesgo de fuga.

* **Tasa de Dimisión SIN Stock Options:** 🔴 **22,3%** (Riesgo Alto)
* **Tasa de Dimisión CON Stock Options:** 🟢 **8,7%** (Riesgo Bajo)

> ** La Oportunidad en Madrid:**
> Actualmente, la penetración de Stock Options en Madrid es idéntica a la de sedes con bajo riesgo. Dado que Madrid sufre una mayor presión laboral, **la herramienta está infrautilizada para este contexto**. No se usa el incentivo para fidelizar frente a la alta exigencia, dejando al talento expuesto a la competencia.

*(Espacio para gráfico comparativo opcional)*
`![Gráfico Impacto Incentivos](img/chart_incentivos.png)`

---

## 3. Caso de Negocio: Rentabilidad de la Inversión
Según estudios de mercado, el coste directo de reemplazo de un empleado equivale a entre **6 y 9 meses de salario**. Utilizando una estimación conservadora (6 meses) para el perfil en riesgo, el impacto financiero es el siguiente:

| Concepto | Impacto Financiero | Descripción |
| :--- | :--- | :--- |
| **Coste de Rotación** | **-465.000 € / año** | Coste estimado de reemplazar a los 15 empleados clave que se pierden anualmente (base 6 meses salario). |
| **Inversión (Solución)** | **-250.000 € / año** | Presupuesto para refuerzos de plantilla (reducir horas extra) y plan de Stock Options. |
| **AHORRO NETO ESTIMADO** | **+215.000 € / año** | **Beneficio directo anual tras descontar la inversión.** |

> **Conclusión Financiera:** Incluso en un escenario conservador (calculando solo costes directos de reemplazo), la inversión es rentable. Por cada **1€ invertido**, la empresa deja de perder **1,86€**, protegiendo la cuenta de resultados.

---

## Stack Tecnológico & Metodología
* **Herramientas:** Power BI (DAX, Modelado), Python (Pandas, Matplotlib para validación estadística).
* **Técnicas:**
    * ETL: Limpieza de datos y clasificación de variables.
    * Feature Engineering: Creación de columnas calculadas para segmentación (ej. *Status Stock*).
    * Análisis: Comparativo multidimensional (Sede vs. Antigüedad).

---

## Oportunidades de Mejora
Basado en los datos, se propone la siguiente hoja de ruta:

1.  **Programa "Semáforo Rojo" (Madrid):** Auditoría y limitación de horas extra para empleados hasta los 5 años de antigüedad.
2.  **Estrategia "Golden Handcuffs":** Adelantar la asignación de Stock Options al primer año para perfiles de alto potencial en Madrid, reduciendo su riesgo de fuga del 22% al 8%.

---
*Contacto: [https://www.linkedin.com/in/ivanbetriu/ / ivan.betriu@gmail.com]*
