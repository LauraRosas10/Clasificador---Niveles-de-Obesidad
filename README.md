# Clasificador de Nivel de Obesidad 
Sistema de análisis predictivo diseñado para determinar el estado nutricional de una persona a partir de múltiples factores conductuales y de estilo de vida. A diferencia de los modelos tradicionales basados únicamente en el Índice de Masa Corporal (IMC), este clasificador incorpora características más completas que permiten una evaluación más precisa y personalizada.

<img width="800" height="300" alt="Niveles de obesidad" src="https://github.com/user-attachments/assets/67233b11-82d7-4685-9938-7e276eb51019" />


## Autores
Laura Vanesa Rosas, Justin David Galvis, Gabriel Vera Moreno


## Objetivo
Desarrollar una herramienta accesible que, a partir de los hábitos de vida y características físicas de cada persona, permita identificar su nivel de obesidad y fomentar la toma de decisiones responsables para mejorar su salud y bienestar

## Dataset (Kaggle)

[Dataset](https://www.kaggle.com/datasets/adeniranstephen/obesity-prediction-dataset) 

<br/>

Este conjunto de datos ayuda a estimar los niveles de obesidad según los hábitos alimentarios, los antecedentes familiares y la condición física. Incluye datos de personas en México, Perú y Colombia, que abarcan 16 características relacionadas con el estilo de vida y la salud, con 2111 registros. Las etiquetas clasifican los niveles de obesidad, desde bajo peso hasta diferentes tipos de obesidad.

<br/>
La mayoría de los datos se generaron mediante técnicas sintéticas, mientras que algunos se recopilaron directamente de los usuarios a través de una plataforma web. Resultan útiles para tareas de clasificación, regresión y agrupamiento.

<br/>

Inspiración:

Comprender los factores del estilo de vida que contribuyen a la obesidad puede ayudar con la intervención temprana, las recomendaciones de salud y las aplicaciones de aprendizaje automático en la atención médica.

<br/>

Descripciones de las variables:

Género: masculino o femenino.
Edad: la edad de la persona en años.
Altura: altura en metros.
Peso: peso en kilogramos.
Antecedentes familiares con sobrepeso: si la persona tiene antecedentes familiares de sobrepeso (sí/no).
FAVC: si la persona consume alimentos ricos en calorías con frecuencia (sí/no).
FCVC: frecuencia de consumo de verduras (escala del 1 al 3).
NCP: número de comidas principales al día.
CAEC: frecuencia de consumo de alimentos entre comidas (nunca, a veces, con frecuencia, siempre).
SMOKE: si la persona fuma (sí/no).
CH2O: ingesta diaria de agua (escala del 1 al 3).
SCC: si la persona controla su ingesta de calorías (sí/no).
FAF: frecuencia de actividad física (escala del 0 al 3).
TUE: tiempo dedicado al uso de tecnología (escala del 0 al 3).
CALC: frecuencia de consumo de alcohol (nunca, a veces, con frecuencia, siempre).
MTRANS - Principal medio de transporte (Automóvil, Bicicleta, Moto, Transporte Público, Caminar).
NObeyesdad - Nivel de obesidad (Peso insuficiente, Peso normal, Sobrepeso nivel I, Sobrepeso nivel II, Obesidad tipo I, Obesidad tipo II, Obesidad tipo III).
Este conjunto de datos proporciona una visión estructurada de cómo los diferentes factores del estilo de vida se relacionan con los niveles de obesidad, lo que lo hace útil para el análisis y la toma de decisiones permitiendo construir un modelo predictivo que clasifique a los individuos en diferentes niveles de obesidad, facilitando la identificación de riesgos y la implementación de estrategias de prevención y tratamiento.

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


