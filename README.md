# KMeansProyect
Proyecto para implementacion de KMeands

## Info Data Set

[Data Kaggle](https://www.kaggle.com/arjunbhasin2013/ccdata)

Este caso requiere desarrollar una segmentación de clientes para definir la estrategia de marketing. El
conjunto de datos de muestra resume el comportamiento de uso de aproximadamente 9000 titulares activos de tarjetas de crédito durante los últimos 6 meses. El archivo está a nivel de cliente con 18 variables de comportamiento.

El siguiente es el diccionario de datos para el conjunto de datos de tarjetas de crédito: -

- **CUSTID** : Identificación del titular de la Tarjeta de Crédito (Categórica)
- **BALANCE**  : Monto de Saldo que queda en su cuenta para realizar compras
- **BALANCEFREQUENCY** : Frecuencia con la que se actualiza el Saldo, puntuación entre 0 y 1 (1 = actualizado frecuentemente, 0 = actualizado poco)
- **PURCHASES** : Importe de las compras realizadas a cuenta 
- **ONEOFFPURCHASES** : Importe máximo de las compras realizadas de un solo pago 
- **INSTALLMENTSPURCHASES** : Importe de la compra realizada a plazos 
- **CASHADVANCE** : Anticipo de efectivo entregado por el usuario 
- **PURCHASESFREQUENCY**: Con qué frecuencia se realizan las compras, puntuación entre 0 y 1 (1 = compra frecuente, 0 = compra no frecuente)
- **ONEOFFPURCHASESFREQUENCY** : Con qué frecuencia se realizan las compras de una sola vez (1 = compra frecuente, 0 = compra no frecuente)
- **PURCHASESINSTALLMENTSFREQUENCY** : Frecuencia con que se realizan las compras a plazos (1 = frecuente, 0 = no frecuente)
- **CASHADVANCEFREQUENCY** : Frecuencia con la que se paga el anticipo 
- **CASHADVANCETRX** : Número de Transacciones realizadas con "Efectivo en Adelantado"
- **PURCHASESTRX** : Número de transacciones de compra hecho
- **CREDITLIMIT** : límite de tarjeta de crédito para
- **PAYMENTS**: Cantidad de pago realizada por el usuario
- **MINIMUM_PAYMENTS** : Cantidad mínima de pagos realizados por el usuario
- **PRCFULLPAYMENT** : Porcentaje del pago total pagado por el usuario
- **TENURE** : Tenencia del servicio de tarjeta de crédito para el usuario
