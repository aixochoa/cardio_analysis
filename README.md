# cardio_analysis
Análisis exploratorio de datos clínicos — Heart Disease UCI Dataset
# Análisis Exploratorio de Enfermedad Cardíaca

Análisis exploratorio de datos clínicos utilizando el dataset Heart Disease UCI, combinando herramientas de análisis de datos con interpretación clínica.

## Objetivo

Identificar qué variables clínicas se asocian más fuertemente con la presencia de enfermedad cardíaca, y evaluar si los factores de riesgo "clásicos" (colesterol, presión arterial) son tan predictivos como variables relacionadas al comportamiento del corazón durante el esfuerzo.

## Herramientas

- Python
- Pandas
- Matplotlib
- Seaborn
- Google Colab

## Dataset

303 pacientes, 14 variables clínicas, sin valores faltantes. Fuente: [Heart Disease UCI Dataset](https://raw.githubusercontent.com/sharmaroshan/Heart-UCI-Dataset/master/heart.csv).

## Principales hallazgos

- Los factores de riesgo clásicos (colesterol, presión arterial) mostraron correlación débil o nula con la enfermedad confirmada.
- Las variables relacionadas al esfuerzo físico (frecuencia cardíaca máxima, depresión del ST, tipo de dolor de pecho) resultaron mucho más predictivas.
- Combinando frecuencia cardíaca máxima y oldpeak se logró una separación visual clara entre pacientes con y sin enfermedad.

Las conclusiones completas están documentadas dentro del notebook.

## Próximos pasos

Entrenar un modelo de clasificación (regresión logística o árbol de decisión) para cuantificar formalmente el poder predictivo de estas variables.
