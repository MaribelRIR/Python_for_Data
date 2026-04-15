# Análisis de Campaña de Marketing Bancario

##  Descripción del proyecto

Este proyecto presenta un análisis exploratorio y explicativo de una campaña de marketing directo realizada por una institución bancaria portuguesa. La campaña se llevó a cabo mediante llamadas telefónicas con el objetivo de determinar si los clientes suscribirían un depósito a plazo bancario.

El objetivo principal es identificar los factores clave que influyen en la decisión de suscripción y extraer insights accionables para mejorar la efectividad de futuras campañas.

Datasets utilizados

Se utilizaron dos fuentes de datos que posteriormente fueron unificadas para el análisis.

### 1. Dataset principal (CSV: `bank-additional`)

Contiene información de clientes y de la campaña:

- age  
- job  
- marital  
- education  
- housing  
- loan  
- contact  
- duration  
- campaign  
- pdays  
- previous  
- poutcome  
- emp.var.rate  
- cons.price.idx  
- cons.conf.idx  
- euribor3m  
- nr.employed  
- y (variable objetivo: suscripción sí/no)  
- date  
- contact_month  
- contact_year  
- id_  



### 2. Dataset secundario (Excel con 3 hojas)

Las tres hojas contienen información similar de perfil del cliente:

- income  
- kidhome  
- teenhome  
- numwebvisitsmonth  
- Dt_customer  
- NumWebVisitsMonth
- ID


## Integración de datos

Ambos datasets fueron combinados para construir una base de datos analítica unificada. El proceso incluyó:

- Limpieza y transformación de datos  
- Tratamiento de variables categóricas  
- Ingeniería de variables (ej. antigüedad del cliente, conversión)  
- Estandarización de formatos  
- Gestión de valores nulos y preparación para análisis  

## Análisis realizado

El proyecto incluye:

- Análisis exploratorio de datos (EDA)  
- Estadística descriptiva  
- Visualización de datos (gráficos de barras, heatmaps, boxplots)  
- Análisis temporal de la campaña  
- Segmentación de clientes  
- Análisis de correlación con variables macroeconómicas  
- Estudio de tasas de conversión  

## Objetivos del proyecto

- Identificar los factores que influyen en la suscripción del producto  
- Evaluar la efectividad de la campaña telefónica  
- Analizar patrones de comportamiento de los clientes  
- Estudiar el impacto de variables temporales y económicas  
- Generar insights accionables para optimizar campañas futuras  

## Herramientas utilizadas

- Python 
- Pandas
- Seaborn
- Matplotlib
- Visual Studio Code
- Jupyter Notebook

## Principales áreas de análisis

- Duración de la llamada vs probabilidad de conversión  
- Antigüedad del cliente y comportamiento de suscripción  
- Rendimiento mensual y estacional de la campaña  
- Impacto de indicadores macroeconómicos  
- Historial de contacto (pdays, previous contacts)  
- Efectividad de canales de contacto  
