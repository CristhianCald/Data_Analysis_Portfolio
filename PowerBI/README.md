Descripción

Dashboard interactivo desarrollado en Power BI para analizar el comportamiento de las ventas de una empresa minorista. El proyecto integra información de clientes, productos y transacciones para facilitar el análisis comercial mediante visualizaciones dinámicas.

Objetivo

Desarrollar un dashboard que permita explorar el comportamiento de las ventas desde diferentes perspectivas, facilitando el análisis por clientes, productos, regiones y periodos de tiempo.

Dataset

El conjunto de datos está compuesto por tres tablas relacionadas mediante un modelo dimensional.

Customers

CustomerID
CustomerName
Region
SignupDate

Products

ProductID
ProductName
Category
Price

Transactions

TransactionID
CustomerID
ProductID
TransactionDate
Quantity
Price
TotalValue
Proceso ETL

Se realizó el proceso de preparación de datos utilizando Power Query.

Las principales actividades fueron:

Validación de tipos de datos.
Conversión de fechas.
Revisión de registros duplicados.
Identificación de valores nulos y blancos.
Eliminación de espacios y caracteres innecesarios.
Validación de consistencia entre tablas.
Verificación de integridad de claves.
Revisión estadística de variables numéricas (promedio, mediana y moda).
Creación del modelo relacional entre Customers, Products y Transactions.
Dashboard

El dashboard está dividido en tres vistas principales:

Clientes

Distribución de clientes por región.
Cantidad de clientes registrados.
Ventas por categoría y región.
Detalle de clientes.

Productos

Ventas por categoría.
Análisis de influencia sobre precios.
Comparación entre categorías.
Visualización de tendencias comerciales.

Transacciones

Evolución mensual del valor total de ventas.
KPIs
Total de ventas
Cantidad de clientes
Ventas por categoría
Ventas por región
Evolución mensual
Valor total de transacciones

Tecnologías utilizadas

Power BI
Power Query
DAX
Modelo Estrella
Microsoft Excel
