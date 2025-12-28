# desafio_dic
# Telecom X – Análisis de Evasión de Clientes (Churn)

##Descripción del proyecto
Este proyecto corresponde al desafío **Telecom X** del programa **Oracle ONE – Data Science (Alura LATAM)**.  
El objetivo principal es analizar la evasión de clientes (**Churn**) a partir de datos proporcionados por una empresa de telecomunicaciones, identificando patrones y factores asociados al abandono del servicio.
A través de técnicas de limpieza, exploración y análisis de datos, se busca generar **insights accionables** que permitan apoyar la toma de decisiones estratégicas orientadas a la retención de clientes.
---

##Objetivo 
- Comprender el comportamiento de los clientes que abandonan el servicio.
- Identificar variables demográficas, contractuales y económicas asociadas al Churn.
- Generar visualizaciones que faciliten la interpretación de los datos.
- Proponer recomendaciones basadas en evidencia para reducir la evasión.
---

## Dataset
- **Fuente:** API en formato JSON (GitHub)
- **Contenido:**  
  - Información demográfica de clientes  
  - Servicios contratados  
  - Tipo de contrato y método de pago  
  - Cargos mensuales y totales  
  - Variable objetivo: `churn` (evasión)
---

## Tecnologías y herramientas utilizadas
- **Python**
- **Google Colab**
- **Pandas**
- **Matplotlib / Seaborn**
- **GitHub**

---

## Proceso de análisis
### Carga de datos
- Importación de datos directamente desde una API en formato JSON.
- Conversión a DataFrame de Pandas.

### Limpieza y tratamiento de datos
- Normalización de columnas anidadas (diccionarios).
- Revisión y tratamiento de valores nulos.
- Corrección de formatos numéricos.
- Limpieza de inconsistencias en variables categóricas.
- Creación de nuevas variables como **Cuentas_Diarias**.
- Estandarización de valores binarios (Sí / No → 1 / 0).

### Análisis Exploratorio de Datos (EDA)
- Análisis descriptivo de variables numéricas.
- Distribución de la variable `churn`.
- Análisis de evasión según:
  - Género
  - Tipo de contrato
  - Método de pago
  - Servicios contratados
- Comparación de variables numéricas (gasto total, permanencia) entre clientes con y sin evasión.
- Visualizaciones para identificar patrones relevantes.



