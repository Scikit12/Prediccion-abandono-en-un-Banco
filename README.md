# Prediccion-abandono-en-un-Banco
Análisis de los datos y comparar diferentes modelos productivos, Árbol de decisión, Bosque aleatorio y Regresión logística.
Para una mejor experiencia usa Jupyter Notebook con la extension "toc".

Este proyecto se enfoca en predecir la probabilidad de que un cliente abandone un banco utilizando técnicas de aprendizaje automático. Se utilizará un conjunto de datos que contiene información sobre clientes bancarios, como su puntaje de crédito, país de residencia, saldo de la cuenta, entre otros, para entrenar modelos de clasificación.

## Instrucciones del Proyecto

1. Descarga y Preparación de Datos
2. Descarga el conjunto de datos desde /churn.csv.
3. Prepara los datos siguiendo el procedimiento detallado en el archivo data_preparation.ipynb.
4. Utiliza al menos dos enfoques para corregir el desequilibrio de clases.
5. Utiliza conjuntos de entrenamiento y validación para encontrar el mejor modelo y conjunto de parámetros.
6. Entrena diferentes modelos en los conjuntos de entrenamiento y validación y encuentra el mejor modelo.
7. Describe tus hallazgos en el archivo model_improvement.ipynb.
7. Prueba Final
8. ealiza la prueba final utilizando el mejor modelo y describe tus resultados en el archivo final_test.ipynb.


## Descripción de los Datos

RowNumber: Índice de cadena de datos.
CustomerId: Identificador de cliente único.
Surname: Apellido.
CreditScore: Valor de crédito.
Geography: País de residencia.
Gender: Sexo.
Age: Edad.
Tenure: Período durante el cual ha madurado el depósito a plazo fijo de un cliente (años).
Balance: Saldo de la cuenta.
NumOfProducts: Número de productos bancarios utilizados por el cliente.
HasCrCard: El cliente tiene una tarjeta de crédito (1 - sí; 0 - no).
IsActiveMember: Actividad del cliente (1 - sí; 0 - no).
EstimatedSalary: Salario estimado.
Exited: El cliente se ha ido (1 - sí; 0 - no).

Autor: Scikit12
