# Análisis del comportamiento de los clientes del banco Beta Bank y su tasa de cancelación de clientes (Churn Rate) por Carlos Horta (carlosgim@gmail.com)

## Análisis de la retención de clientes en Beta Bank

El objetivo de este proyecto es determinar si un cliente dejará el banco pronto, utilizando el análisis del comportamiento pasado de los clientes y la terminación de contratos con el banco. La dirección general ha determinado que es más rentable retener a los clientes existentes que atraer nuevos.

En este proyecto, se desarrollará un modelo para identificar el máximo valor posible de F1 (con un mínimo de 0.59) y se evaluará esta métrica utilizando el conjunto de prueba. Además, se medirá la métrica AUC-ROC y se comparará con el valor de F1.

Las características disponibles en el conjunto de datos son las siguientes:

- RowNumber: índice de cadena de datos.
- CustomerId: identificador único del cliente.
- Surname: apellido del cliente.
- CreditScore: valor de crédito del cliente.
- Geography: país de residencia del cliente.
- Gender: género del cliente.
- Age: edad del cliente.
- Tenure: período durante el cual ha madurado el depósito a plazo fijo del cliente (en años).
- Balance: saldo de la cuenta del cliente.
- NumOfProducts: número de productos bancarios utilizados por el cliente.
- HasCrCard: indica si el cliente tiene una tarjeta de crédito (1 - sí; 0 - no).
- IsActiveMember: indica si el cliente está activo (1 - sí; 0 - no).
- EstimatedSalary: salario estimado del cliente.

El objetivo del proyecto es predecir la variable "Exited", que indica si el cliente ha dejado el banco (1 - sí; 0 - no).

-----

# Customer Retention Analysis in Beta Bank

The objective of this project is to determine if a customer will leave the bank soon by analyzing their past behavior and contract terminations. The management has determined that retaining existing customers is more profitable than attracting new ones.

In this project, a model will be developed to identify the maximum possible value of F1 (with a minimum of 0.59), and this metric will be evaluated using the test set. Additionally, the AUC-ROC metric will be measured and compared with the F1 score.

The available features in the dataset are as follows:

- RowNumber: index of the data row.
- CustomerId: unique customer identifier.
- Surname: customer's surname.
- CreditScore: customer's credit score.
- Geography: customer's country of residence.
- Gender: customer's gender.
- Age: customer's age.
- Tenure: duration of the customer's fixed-term deposit maturity (in years).
- Balance: customer's account balance.
- NumOfProducts: number of bank products used by the customer.
- HasCrCard: indicates if the customer has a credit card (1 - yes; 0 - no).
- IsActiveMember: indicates if the customer is an active member (1 - yes; 0 - no).
- EstimatedSalary: estimated salary of the customer.

The project aims to predict the "Exited" variable, indicating if the customer has left the bank (1 - yes; 0 - no).
