# Clasificador de Nivel de Obesidad 
Sistema de análisis predictivo diseñado para determinar el estado nutricional de una persona a partir de múltiples factores conductuales y de estilo de vida. A diferencia de los modelos tradicionales basados únicamente en el Índice de Masa Corporal (IMC), este clasificador incorpora características más completas que permiten una evaluación más precisa y personalizada.

<img width="800" height="300" alt="Niveles de obesidad" src="https://github.com/user-attachments/assets/67233b11-82d7-4685-9938-7e276eb51019" />


## Autores
Laura Vanesa Rosas, Justin David Galvis, Gabriel Vera Moreno


## Objetivo
Desarrollar una herramienta accesible que, a partir de los hábitos de vida y características físicas de cada persona, permita identificar su nivel de obesidad y fomentar la toma de decisiones responsables para mejorar su salud y bienestar.

## Dataset (Kaggle)

[Dataset](https://www.kaggle.com/datasets/adeniranstephen/obesity-prediction-dataset) 

<br/>

Este conjunto de datos está diseñado para estimar y clasificar los niveles de obesidad a partir de información relacionada con los hábitos alimentarios, antecedentes familiares y condición física de las personas. Contiene 2,111 registros provenientes de individuos de México, Perú y Colombia, e incluye 16 características asociadas al estilo de vida y la salud.

Las etiquetas corresponden a distintos niveles de obesidad, desde bajo peso hasta diferentes grados de obesidad.

Una parte de los datos fue generada mediante técnicas sintéticas, mientras que otra proviene de información recopilada directamente mediante una plataforma web. Esto lo convierte en un recurso versátil para tareas de clasificación, regresión y agrupamiento en el ámbito del análisis de salud.

<br/>

Descripción de las variables:

- Género: Masculino o femenino

- Edad: Edad en años

- Altura: En metros

- Peso: En kilogramos

- Family History: Antecedentes familiares de sobrepeso (sí/no)

- FAVC: Consumo frecuente de alimentos altos en calorías (sí/no)

- FCVC: Frecuencia de consumo de verduras (1–3)

- NCP: Número de comidas principales diarias

- CAEC: Consumo de alimentos entre comidas (nunca, a veces, con frecuencia, siempre)

- SMOKE: Hábito de fumar (sí/no)

- CH2O: Cantidad diaria de agua ingerida (1–3)

- SCC: Control de ingesta calórica (sí/no)

- FAF: Frecuencia de actividad física semanal (0–3)

- TUE: Uso diario de tecnología en horas (0–3)

- CALC: Consumo de alcohol (nunca, a veces, con frecuencia, siempre)

- MTRANS: Medio de transporte principal (automóvil, bicicleta, moto, transporte público, caminar)

- NObeyesdad: Nivel de obesidad (Peso insuficiente, Normal, Sobrepeso I/II, Obesidad I/II/III)
  
## Modelos

### Machine Learning - Clasificación

Supervisados:
<br/>

- Gaussian Naive Bayes
- Decision Tree Classifier
- Random Forest Classifier
- Support Vector Machine (Mejor modelo supervisado para el proyecto)

No Supervisados:

<br/>

- K-Means (Mejor modelo no supervisado para el proyecto)
- DBSCAN

Reducción de dimensionalidades:

<br/>

- PCA
- t-SNE (Mejor tecnica para el proyecto)
  
## Enlaces
[Código](https://drive.google.com/drive/folders/1-g9FQp0KWUW1HhyO0EJcQYdX-Y5W8S8X?usp=sharing)
<br/>
[Video](https://youtu.be/qjmbn-60c9E)
<br/>
[Repositorio](https://github.com/LauraRosas10/Clasificador---Niveles-de-Obesidad)


