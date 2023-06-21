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

