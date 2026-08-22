# TPG_Final - Aprendizaje de máquina

## Profesor@s
* María Carina Roldán
## Integrantes

* Diego Aníbal Vázquez

## Grupo
6

## Descripción

Este proyecto corresponde al Trabajo Práctico Grupal de Análisis de Datos. El objetivo es realizar un proceso completo de exploración, limpieza, análisis y preparación de datos utilizando información de denuncias policiales del Departamento de Policía de Nueva York (NYPD).

El trabajo incluye:

* Exploración y comprensión de los datos (EDA).
* Identificación de errores e inconsistencias.
* Análisis de valores faltantes.
* Detección y análisis de outliers.
* Transformación y preparación de variables.
* Selección de atributos relevantes.
* Construcción de modelos de clasificación.
* Evaluación del desempeño de los modelos obtenidos.

## Dataset

Se utiliza el conjunto de datos:

`NYPD_Complaint_Data_Current_(Year_To_Date)_20260504.csv` 

Para el desarrollo del trabajo se consideran únicamente los registros correspondientes al año 2025.

## Estructura del Proyecto

```text
.
├── TPG_Final.ipynb
├── datasets/
│   └── NYPD_Complaint_Data_Current_(Year_To_Date)_20260504.zip
└── README.md
```

## Requisitos

* Python 3.x
* Jupyter Notebook

Bibliotecas principales:

* pandas
* numpy
* matplotlib
* seaborn
* scikit-learn
* scipy
* missingno

## Ejecución

1. Clonar el repositorio:

```bash
git clone https://github.com/dvazquez1981/tp_final_AdD_g6
```

2. Ingresar al directorio:

```bash
cd tp_final_AdD_g6
```

3. Abrir Jupyter Notebook:

```bash
jupyter notebook
```

4. Ejecutar el archivo:

```text
TPG_Final.ipynb
```

## Contenido del Análisis

* Descripción general del dataset.
* Análisis de distribuciones y variables.
* Tratamiento de valores faltantes.
* Evaluación de mecanismos de ausencia (MCAR, MAR y MNAR).
* Identificación y análisis de outliers.
* Preparación de datos para modelado.
* Entrenamiento y evaluación de modelos de clasificación.

## Resultados

Los resultados obtenidos, gráficos, métricas y conclusiones se encuentran documentados dentro del notebook `TPG_Final.ipynb`.
