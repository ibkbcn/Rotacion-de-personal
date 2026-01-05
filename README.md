# People Analytics: Fuga y Retención de Talento

## Resumen Ejecutivo
Este proyecto analiza la rotación de empleados en una compañía farmacéutica con sedes en Madrid, Barcelona y Bilbao. El objetivo principal fue identificar las causas raíz de las dimisiones y **cuantificar el riesgo de fuga de talento en los colectivos críticos.**

El análisis reveló que la **crisis de rotación se concentra geográficamente en la sede de Madrid**, donde la cultura local de sobrecarga laboral (horas extra) colisiona con una política corporativa de incentivos (Stock Options) insuficiente para retener al talento en este mercado, afectando tanto a juniors como a perfiles consolidados.

---

## Dashboard Overview

<img width="1939" height="1090" alt="image" src="https://github.com/user-attachments/assets/f098ea88-0b62-47e5-a9a1-0e28cadffd9b" />



---

## Hallazgos Clave 

### 1. El "Efecto Madrid": Fallo Estructural
A diferencia de Barcelona y Bilbao, que logran estabilizar a su plantilla tras el segundo año, la sede de Madrid sufre una fuga continua que abarca los primeros 5 años.

* **La Anomalía:** Madrid pierde al **33%** de los perfiles de entrada (0-2 años) y mantiene una tasa crítica del **17%** en perfiles consolidados (2-5 años), duplicando a otras sedes.
* **Factores Determinantes:**  
      ** Burnout Temprano:** El **60%** de las dimisiones están vinculadas a horas extra.  
      ** Falta de Arraigo:** La política de incentivos no actúa como barrera. **En Madrid, casi 2 de cada 3 empleados que abandonan (66%) no poseen Stock Options**, lo que elimina el coste de oportunidad por irse.

### 2. Validación: El Poder de los Incentivos
Los datos globales confirman que las Stock Options actúan como una **herramienta de prevención eficaz**, reduciendo drásticamente el riesgo de fuga.

* **Tasa de Dimisión SIN Stock Options:** 🔴 **22,3%** (Riesgo Alto)
* **Tasa de Dimisión CON Stock Options:** 🟢 **8,7%** (Riesgo Bajo)

> ** La Oportunidad en Madrid:**
> Actualmente, la penetración de Stock Options en Madrid es idéntica a la de sedes con bajo riesgo. Dado que Madrid sufre una mayor presión laboral, **la herramienta está infrautilizada para este contexto**. No se usa el incentivo para fidelizar frente a la alta exigencia, dejando al talento expuesto a la competencia.

---

## Stack Tecnológico & Metodología
* **Herramientas:** Power BI (Power Query para ETL, DAX para análisis, Modelado de datos).
* **Técnicas:**
    * ETL: Limpieza de datos y clasificación de variables.
    * Feature Engineering: Creación de columnas calculadas para segmentación (ej. *Status Stock*).
    * Análisis: Comparativo multidimensional (Sede vs. Antigüedad).

---

## Oportunidades de Mejora
Basado en los datos, se propone la siguiente hoja de ruta:

1.  ** Iniciativa de Control de Carga Crítica (Sede Madrid): Implementación de auditorías preventivas y limitación de horas extra para la estabilización del talento en fase de consolidación (0-5 años).
2.  **Programa de Aceleración de Incentivos (Equity Acceleration): Anticipación de la oferta de Stock Options para perfiles de alto potencial, orientada a reducir la probabilidad de fuga del 22% al 8% en el primer ciclo.

---
*Contacto: [https://www.linkedin.com/in/ivanbetriu/ / ivan.betriu@gmail.com]*
