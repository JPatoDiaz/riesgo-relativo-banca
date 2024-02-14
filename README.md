# Análisis del riesgo relativo para el sector financiero

## Contexto


El riesgo relativo es una medida estadística utilizada en epidemiología y en otras diversas áreas para evaluar la asociación entre la exposición a un factor de riesgo específico y la aparición de un resultado particular, como una enfermedad o un evento adverso. Se calcula como la proporción de la incidencia de dicho resultado en el grupo expuesto al factor de riesgo en comparación con la incidencia en el grupo no expuesto.

En otras palabras, el riesgo relativo proporciona una indicación de cuánto más probable es que ocurra un resultado en el grupo expuesto en comparación con el grupo no expuesto. 

En este proyecto se uso el calculo del riesgo relativo como una herramienta para identificar que variables pueden influir en que un cliente sea de alto riesgo o no. 

## ¿Cuál fue el objetivo? 

Analizar una base de datos bancaria con información de los créditos concedidos por el Banco y el comportamiento de pago; además de calcular el riesgo relativo para algunas variables que permitan identificar que cliente puede ser de alto riesgo o no. 

Adicional, se busco validar las siguientes hipótesis: 

-   Los más jóvenes tienen un mayor riesgo de impago.
-   Las personas con más cantidad de préstamos activos tienen mayor riesgo de ser malos pagadores.
-   Las personas que han retrasado sus pagos por más de 90 días tienen mayor riesgo de ser malos pagadores.


## ¿Qué insumos/herramientas usamos para el análisis?  

### Insumos
- Set de datos con la información de los usuarios y clientes del banco.
- Set de datos con la información de prestamos (por tipo).
- Set de datos la información del comportamiento de pago de los prestamos.
- Set de datos con la identificación de clientes con tag morosos.


### Herramientas

- BigQuery
- Looker Studio
- GoogleColab
- Google Slides

### Lenguajes

- SQL
- Phyton

## ¿Cuál fue el proceso de trabajo?  

El desarrollo del proyecto se llevo a través de las siguientes fases

-   Procesar y preparar los datos con consultas en SQL 
-  Análisis exploratorio (AED).
-   Aplicar técnicas de análisis cómo:
    - Calculo de riesgo relativo por variables seleccionadas
    - Correlación de variables 
-   Construcción de dashboard.
-   Presentación de resultados con stakeholders.


## Archivos

- Consultas SQl realizadas en GoogleCloud. Disponibles en: https://console.cloud.google.com/bigquery?project=proyecto03-408116&ws=!1m0
