
# Análisis Dataset Amazon Top 50 Bestselling Books 2009 - 2019

Análisis de datos reales de un dataset con los 50 libros mas vendidos por año.


## Authors

- Link del dataset utilizado -> https://www.kaggle.com/datasets/sootersaalu/amazon-top-50-bestselling-books-2009-2019


## Información de la tabla

Dataset on Amazon's Top 50 bestselling books from 2009 to 2019. Contains 550 books, data has been categorized into fiction and non-fiction using Goodreads


## Columnas

### Name - String
Nombre del libro
### Author - String
 Nombre del autor del libro
### User Rating - Number
 Puntuación del usuario del libro en el rango del 1-50
### Reviews - Number
 Cantidad de reviews que ha recibido el libro por usuarios
### Price - Moneda
 Precio Individual del libro
### Year - General 
 Año donde fué Bestseller
### Genre - String
 Divididos en 2, Fiction y non fiction
### Sales_Per_Reviers - Moneda
Estimación de ventas de cada libro, multiplicando su precio por la                      cantidad de reviews
### Recommended - General
Dato que nos dará recommended si User Rating > 40
## Ejemplo tabla y claraciones


![Descripción](https://raw.githubusercontent.com/Bootcamp-Data-Analyst/p1-analisis-descriptivo-excel-andres/main/img/ejemplo%20de%20tabla.png)



En esto ejemplo de mi tabla me gustaría explicar dos cosas que hay que tener en cuenta.


![Descripción](https://raw.githubusercontent.com/Bootcamp-Data-Analyst/p1-analisis-descriptivo-excel-andres/main/img/Ejemplo%20registros%20repetidos.png)

1- "Libros repetivos" como se puede observar un mismo libro puede estar repetido en diferentes años, esto es debido a que el estudio está basado en los 50 libros mas vendidos por año, y en estos casos quiere decir que el libro se encuentra como top seller en diferentes años, sin un orden en particular


![Descripcion](https://raw.githubusercontent.com/Bootcamp-Data-Analyst/p1-analisis-descriptivo-excel-andres/main/img/Libros%20best%20seller%20con%20baja%20user%20rate.png)

2-Aquí se puede observar un error en la captura de datos
Como se puede apreciar un dato que me llamó la atención fue que dentro de los best seller se encontraban libros con un User Rating muy por debajo

Para entenderlo miré en internet estos libros y para mi sorpresa sus valoraciones eran alrededor de 40, con lo que mi conclusión es que se guardaron de forma incorrecta, y le solo se guardó el 4 cuando debía estar en un rango entre 40-50.