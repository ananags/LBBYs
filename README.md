# LBBYs
Competición de Machine Learning para clasificar el riesgo de préstamos a PYMEs. Análisis de datos, desarrollo de modelo y envíos a Kaggle.

Este repositorio contiene el trabajo realizado por el equipo **LBBYs** 


## Objetivo

Construir un clasificador que, a partir de los datos financieros e históricos de una empresa, determine si es conveniente concederle o no un préstamo. La métrica de evaluación es **Macro F1-Score**, lo que obliga a maximizar la precisión y el recall en ambas clases.

---

## Estructura del repositorio

```bash
LBBYs/
│
├── data/                         # Datos originales y procesados
│   ├── raw/                      # train.csv, test_nolabel.csv
│   └── processed/                # df_train_clean.csv, df_test_clean.csv
│
├── notebooks/                    # Notebooks organizados por fases
│   ├── 1_analisis/               # Análisis exploratorio de datos
│   ├── 2_preprocesado/           # Limpieza, encoding, normalización
│   ├── 3_modelado/               # Modelos: SVM, Árboles, XGBoost, Secreto, ... Con evalucion incluida
│   ├── 4_submission/             # Subidas a Kaggle
│   └── 5_documentacion/          # Tablas de autoría y valoraciones
│
├── scripts/                      # Funciones reutilizables (preprocesado, entrenamiento…)
│
├── submissions/                  # CSVs subidos a la competición en Kaggle
│
├── doc/                          # Documentación final del proyecto
│   ├── memoria_equipo.pdf
│   ├── partes_individuales/
│   └── presentacion_equipo.pdf
│
├── requirements.txt              # Lista de librerías necesarias
├── README.md                     # Este archivo
└── .gitignore
