
<div style="text-align: center;">
  <img src="https://github.com/Hack-io-Data/Imagenes/blob/main/01-LogosHackio/logo_naranja@4x.png?raw=true" alt="logo" />
</div>

# Proyecto: Predicción de Retención de Empleados 🏢


## Introducción

Esta vez te toca trabajar en Recursos Humanos y te enfrentas a uno de los mayores dolores de cabeza de cualquier empresa: la rotación de empleados. ¿Por qué algunas personas deciden quedarse mientras otras se van? ¿Será el salario? ¿Las horas extra? ¿La relación con su jefe?

En este proyecto, usarás datos recopilados de una empresa ficticia (sí, no te preocupes, no es información confidencial) que incluye desde encuestas de satisfacción hasta métricas de desempeño y horarios laborales. Tu tarea será desentrañar patrones, analizar tendencias y construir un modelo que pueda predecir si un empleado permanecerá o decidirá decir adiós.

Pero esto no es solo sobre números y gráficos; se trata de entender cómo las decisiones empresariales impactan la vida de las personas y cómo, con un poco de análisis, podríamos ayudar a las empresas a ser mejores lugares para trabajar. Así que prepárate para explorar datos, ensuciarte las manos con algoritmos y, quién sabe, tal vez descubrir el secreto para mantener a los empleados felices y comprometidos.

Este proyecto no solo es un ejercicio técnico, también es un entrenamiento toma de decisiones basadas en datos. 

## Objetivo del Proyecto

El principal desafío de este proyecto es abordar una de las preguntas más importantes para cualquier departamento de Recursos Humanos: ¿qué empleados tienen más probabilidades de quedarse en la empresa y cuáles podrían decidir irse? Para lograr esto, tu trabajo será construir un modelo de machine learning capaz de predecir si un empleado permanecerá en la empresa o decidirá marcharse. 

El enfoque no solo será técnico. A través del análisis de los datos, deberás identificar cuáles son los factores más influyentes en la retención o rotación del personal. Por ejemplo (estos son solo algunos ejemplos, pero puedes hacerte todas las preguntas que quieras para entender bien los datos e identificar los factores más influyentes):

- ¿Es la satisfacción laboral un predictor clave?

- ¿Tienen más probabilidades de irse quienes trabajan largas horas o aquellos con relaciones tensas con sus jefes?

- ¿Qué papel juegan las promociones o los aumentos de salario?

Tu modelo debe ser capaz de responder estas preguntas y ofrecer predicciones precisas que puedan usarse para tomar decisiones informadas. Esto significa que, además de construir un modelo que funcione, **deberás interpretar sus resultados y proponer estrategias basadas en ellos**.

## Descripción de los Datos

- `employee_survey_data.csv`: Contiene datos de encuestas sobre la satisfacción y percepción de los empleados.

- `general_data.csv`: Información demográfica y general de los empleados

- `manager_survey_data.csv`: Encuestas realizadas por los supervisores sobre desempeño y satisfacción.

**NOTA** Dentro de la carpeta de datos, encontrarás un archivo `diccionario-datos` donde encontrarás la descripción detallada de todos los datos aportados. 

## Estructura del Proyecto

Este proyecto está dividido en varias etapas las cuales son: 

1. **1-Eda-Pre.ipynb**: Eda, preprocesado.

2. **2-Modelos.ipynb**: Creacion de modelos.

3. **3-Pred.ipynb**: Test prediccion del modelo seleccionado.

## Conclusiones - Mejor Modelo: **XGBoost**

Entrenamiento (train):

-   Accuracy, Precision, Recall, F1: 0.91

-   Kappa: 0.83

-   AUC: 0.96

Prueba (test):

-   Accuracy, Precision, Recall, F1: 0.89-0.90

-   Kappa: 0.79

-   AUC: 0.95

XGBoost da un resultado parecido Gradient Boosting, por temas de rendimiento nos quedamos con XGBoost.

#### Propuestas de Mejora:
   - visualizacion streamlit.
  
## Construido con 🛠️

* [Pyhton](https://www.python.org/) - Lenguaje utilizado
* [Numpy](https://numpy.org/doc/stable/) - Numpy
* [seaborn](https://seaborn.pydata.org/tutorial.html) - Seaborn
* [matplotlib](https://matplotlib.org/stable/users/index) - matplotlib
* [pandas](https://pandas.pydata.org/docs/) - pandas
* [Visual Studio Code](https://code.visualstudio.com/) - IDE desarrollo
  
## Autores ✒️

* **Santiago Rodriguez** - [santiagorodriguez-dev](https://github.com/santiagorodriguez-dev)
