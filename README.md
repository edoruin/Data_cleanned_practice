# Práctica de Limpieza de Datos - Dataset Titanic

Este repositorio contiene un ejercicio de limpieza y preprocesamiento de datos utilizando el famoso dataset del Titanic de Kaggle. El objetivo es preparar los datos para un posterior análisis o modelado estadístico.

[English version here](README.en.md)

## Contenido del Repositorio

- `Cleaning_TITANIC_2024.ipynb`: Jupyter Notebook con todo el proceso de limpieza de datos.
- `Titanic/`: Carpeta que contiene los datasets originales (`train.csv`, `test.csv` y `gender_submission.csv`).

## Descripción del Proceso

En el notebook se realizan las siguientes tareas:
1. **Estadística Descriptiva**: Exploración inicial de los datos.
2. **Eliminación de Columnas**: Remoción de variables que no aportan valor al modelo inicial (como el nombre).
3. **Imputación de Valores Faltantes**: Uso de `SimpleImputer` para variables categóricas.
4. **Tratamiento de Variables Numéricas**: Imputación de la media para la columna 'Age' y conversión a tipo entero.
5. **Codificación de Variables Categóricas**: Aplicación de One-Hot Encoding a las variables 'Sex' y 'Embarked'.
6. **Exportación de Datos**: Generación de archivos CSV con los datos ya limpios.

## Instrucciones de Uso

Para ejecutar el código localmente:
1. Clona este repositorio.
2. Asegúrate de tener instaladas las librerías necesarias (`pandas`, `numpy`, `scikit-learn`).
3. **Nota Importante**: En el notebook, deberás actualizar las rutas de carga y guardado de los archivos CSV para que coincidan con tu entorno local o de Google Colab.

## Tecnologías Utilizadas

- Python
- Pandas
- Numpy
- Scikit-learn (SimpleImputer, OneHotEncoder)
- Jupyter Notebook / Google Colab
