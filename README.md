# TFM - Predicción del antecedente de infarto de miocardio mediante aprendizaje automático sobre datos clínicos NHANES

Este repositorio contiene el material computacional asociado al Trabajo de Fin de Máster titulado **“Predicción del antecedente de infarto de miocardio mediante aprendizaje automático sobre datos clínicos NHANES”**.

El objetivo del repositorio es facilitar la revisión del código, las salidas generadas y la trazabilidad del análisis desarrollado en la memoria del TFM.

## Contenido del repositorio

* `index.html`: versión HTML ejecutada del notebook, con el código y las salidas visibles.
* `Codigo_TFM_NHANES.ipynb`: notebook principal del análisis.
* `requirements.txt`: listado de librerías principales utilizadas en el entorno de ejecución.

## Versión HTML ejecutada

La versión HTML ejecutada del análisis puede consultarse en:

https://jaimefmorin.github.io/Mi-TFM-NHANES/

Esta versión permite revisar el código, las tablas, las figuras y las salidas generadas durante la ejecución del notebook sin necesidad de abrir Jupyter Notebook localmente.

## Entorno técnico principal

El análisis se desarrolló en Python mediante Jupyter Notebook. Las principales versiones utilizadas fueron:

* Python 3.13.2
* pandas 2.2.3
* NumPy 2.1.3
* scikit-learn 1.6.1
* matplotlib 3.10.0
* XGBoost 3.0.0
* seaborn 0.13.2
* SciPy 1.15.2

## Datos

Los datos utilizados proceden de **NHANES 2017–March 2020 Pre-pandemic**, fuente pública desarrollada por el National Center for Health Statistics, perteneciente a los Centers for Disease Control and Prevention de Estados Unidos.

Este repositorio documenta el flujo de análisis utilizado en el TFM, pero la descarga de los ficheros originales debe realizarse desde la fuente oficial de NHANES.

## Reproducibilidad

El notebook principal recoge el flujo completo de construcción de la cohorte analítica, preprocesamiento, comparación de modelos, selección de variables, calibración, evaluación final y generación de salidas complementarias.

La versión HTML ejecutada se aporta como evidencia documental del código ejecutado y de las salidas obtenidas durante el análisis.

Para reproducir el entorno principal, se pueden instalar las dependencias indicadas en `requirements.txt`.
