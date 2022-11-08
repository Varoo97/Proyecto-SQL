# Proyecto-SQL

![IMG_20221107_220424_406](https://user-images.githubusercontent.com/114336696/200415423-8477d7d1-316a-4155-8450-27e1127e1492.jpg)

El objetivo de este proyecto es construir una base de datos a partir de varios archivos csv.

Para ello, en primer lugar, comenzamos limpiando la base de datos a través de pandas. Comprobando que no tengamos valores nulos, que no existan errores o informacion innecesaria, con el fin de eliminar información no relevante, y así poder manejar una base de datos mucho más manejable y sencilla.

Una vez limpia la base de datos, mediante el módulo SQLAlchemy, cargamos los 7 archivos ya limpios a nuestra interfaz gráfica MySQL Workbench.

Posteriormente, y una vez ya cargados los datos en Workbench, establecemos las conexiones entre las diferentes tablas.

![Modelo relacional](/img/model.jpg)

Finalmente, también con el módulo SQLAlchemy, se realizaron 10 consultas utilizando SQL.
