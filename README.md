# Modelo de predicción de planes de servicios de telecomunicación de Megaline

La compañía móvil Megaline no está satisfecha al ver que muchos de sus clientes utilizan planes heredados. Quieren desarrollar un modelo que pueda analizar el comportamiento de los clientes y recomendar uno de los nuevos planes de Megaline: Smart o Ultra. Tienes acceso a los datos de comportamiento de los suscriptores que ya se han cambiado a los planes nuevos.

Para esta tarea de clasificación vamos a crear un modelo que escoja el plan correcto.

Desarrollaremos un modelo con la mayor exactitud posible con al menos un umbral de exactitud del 75%. Usaremos el dataset para comprobar la exactitud.

## Objetivo
El objetivo es obtener un modelo capaz de predecir el tipo de plan Ultra o Smart que necesitan los usuarios.

## Contenido
  Introducción
  Iniciación de datos
    Examina datos
    Descripción de datos
  Machine Learning
    Segmentación de datos
    Entrenamiento
      Algoritmo DecisionTreeClassifier
      Algoritmo RandomForestClassifier
      Algoritmo LogisticRegression
    Calidad del modelo
    Prueba de cordura
  Conclusión general


## Librerías usadas
  pandas, numpy
  sklearn.model_selection import train_test_split
  sklearn.tree import DecisionTreeClassifier
  sklearn.ensemble import RandomForestClassifier
  sklearn.linear_model import LogisticRegression
  sklearn.metrics import accuracy_score
