# Optimización de Campañas de Telemercadeo para Venta de CDTs

**Resumen**

Una entidad financiera realiza campañas de telemercadeo para ofrecer Certificados de Depósito a Término (CDTs) a sus clientes. Sin embargo, contactar y ofrecer el producto a todos los clientes indiscriminadamente resulta costoso e ineficiente. Por esta razón, se ve la necesidad de identificar el perfil de clientes que presenten una mayor probabilidad de adquirir el producto y así optimizar los recursos del call center. Para lograr esto, se desarrolló un modelo de clasificación a partir de datos con características demográficas, financieras y de comportamiento de contacto. En primer lugar, se realizó un análisis exploratorio de datos que permitió identificar variables clave y obtener insights preliminares sobre las tendencias de clientes propensos a adquirir un CDT. Posteriormente, se entrenaron tres modelos: una Regresión Logística, un XGBoost y una Red Neuronal. Se comparó el desempeño de estos en un conjunto de prueba y se seleccionó al XGBoost como la solución óptima para este objetivo dado que demostró una mayor precisión operativa, permitiendo filtrar significativamente las llamadas improductivas y focalizar la fuerza de ventas en el perfil de cliente ideal.

---

## Objetivos

- Comprender cuáles son las variables que aportan mayor información al momento de predecir el interés de un cliente en adquirir un CDT.
- Identificar el tipo de clientes que se debería priorizar en una campaña de tele-mercadeo.
- Construir un modelo capaz de detectar clientes con mayor probabilidad de adquirir un CDT con el banco, a fin de priorizar los esfuerzos y optimizar el costo del call center.

---

## Tecnologías utilizadas

- `Python` como lenguaje de programación
- `Visual Studio Code` como entorno de desarrollo

---

##  Descripción de archivos

- `Script_CDT.ipynb`: Notebook en Python con todo el flujo de trabajo (análisis exploratorio, limpieza de datos, modelado y evaluación).  
- `Reporte_CDT.pdf`: Informe con los resultados.  

