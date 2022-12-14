# <h1 align=center> **PROYECTO INDIVIDUAL Nº2** </h1>

# <h1 align=center>**'Machine Learning'**</h1>

## **Introducción**

Este proyecto busca poner a prueba las habilidades adquiridas y desarrolladas a lo largo de la cursada de en la carrera de Data Science en Henry.

Como estudiante debo destacar el nivel de código requerido, además de las habilidades de búsqueda e interpretación de código requeridas para el desarrollo de cada una de sus etapas.

## **Objetivo del Proyecto**

El objetivo del proyecto es simular un entorno de trabajo donde se presenta un caso de estudio:
Un importante Centro de Salud necesita predecir si un paciente tendrá una estancia hospitalaria prolongada o no. Utilizando la información provista (una muestra histórica de sus pacientes) se debe elaborar un modelo predictivo para poder administrar la demanda de camas en el hospital según la condición de los pacientes recientemente ingresados.

## **Trabajo realizado**

Como primer paso relicé un análisis del dataset provisto, en busca de errores o faltantes de datos. Verificado lo anterior, procedí a modificar las variables categóricas para convertirlas en números que el modelo pueda interpretar.
El siguiente paso fue entrenar el modelo utilizando la totalidad de las variables y analizar su resultado usando las métricas de Recall y Accuracy.
En busca de una mejora en los resultados obtenidos, apliqué un análisis de correlación de variables, quedándome sólo con aquellas que tenían mayores índices.

Abro aquí un paréntesis: la elección de features puede realizarse analíticamente o por criterios subjetivos al usuario. En este caso, creo que las variables elegidas representan un criterio simplificador, pero que en segunda instancia implican también a varias de las que fueron dejadas de lado. Por ejemplo: la gravedad del paciente y la especialidad estarán fuertemente ligadas al médico que lo atienda.

Luego de aplicar los cambios pude observar una mejora en las métricas del modelo, procediendo así a la última etapa del Proyecto.
La última instancia era hacer que el modelo trabaje sobre el dataset de Test y exportar las predicciones para luego ser evaluadas.

## **Contenido del repositorio**

La raiz del contenedor está compuesta por un archivo con las consignas del Proyecto, un notebook con el código del EDA y el modelo, también los datasets (train y test), el archivo csv generado con las predicciones y el Readme.