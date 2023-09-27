# MySQL

* Lenguaje de consulta estructurado (SQL) "Structured Query Language"
*  SQL es el lenguaje para interactuar con un DBMS y realizar acciones específicas en una base de datos, como consultas y actualizaciones.
*  MySQL  es un software de manejo de base de datos. Es un Sistema de Gestión de Bases de Datos (DBMS)

## BASE DE DATOS RELACIONAL
* Los elementos se organizan como un conjunto de tablas con columnas y filas.
* Cada fila representa un registro.  __(f = r)__
* Cada columna representa un atributo o campo. __(c = a/c)__
* Cada fila de la tabla es un registro único que posee un identificador específico llamado clave primaria o llave primaria.

## ¿QUÉ ES UN MODELO DE BASE DE DATOS?
* es la estructura lógica que adopta la base de base datos.
* Determina cómo se manipulan y qué tipo de operaciones se pueden realizar con los datos.

## RESUMEN:

#### ¿QUÉ ES UNA BASE DE DATOS?
Una tabla que posee filas y columnas que estructuran la información.

#### ¿QUÉ ES UNA TABLA?
a. Las tablas constituyen la base de datos y organizan la información.
b. Una tabla es una estructura organizada para almacenar información.
c. Una tabla posee filas y columnas, en apariencia, es similar a una hoja de cálculo.

#### TIPOS DE BASE DE DATOS: 
a. Base de datos no relacional
b. Base de datos relacional
d. Base de datos orientada a objetos

#### VENTAJA DE ALMACENAR DATOS EN UNA BADE DE DATOS:
En las bases de datos, es posible establecer permisos y controles de acceso para limitar quién puede ver, modificar o eliminar datos. Esto ayuda a garantizar la seguridad y la integridad de los datos.

#### ¿CÓMO SE LLAMA EL ELEMENTO QUE IDENTIFICA A CADA REGISTRO O FILA Y LA HACE ÚNICA?
Llave primaria 

********************************************************************

## ¿QUÉ ES UN MODELO RELACIONAL?
* Es un modelo de datos basado en la lógica de predicados y en la teoría de conjuntos.
* Creado por un científico informático inglés llamado Edgar Frank "Ted" Codd a finales de los 60’.
* Estas relaciones podrían considerarse en forma lógica como conjuntos de datos. Estos conjuntos de datos, se denominan __tuplas__.
* Si pensamos en cada relación como una tabla que está compuesta por registros (cada __fila__ de la tabla sería un __registro o “tupla”__) y columnas (también llamadas “campos”).
* Este modelo está basado en que todos los datos están almacenados en tablas (también llamadas entidades o relaciones)
* __DOMINIO__ en una base de datos relacional define las características y las limitaciones de los datos que pueden almacenarse en un atributo específico de una tabla, garantizando la integridad y la consistencia de los datos.


## NORMALIZACIÓN EN EL MODELO RELACIONAL 
* El objetivo de la normalización es reducir la redundancia de datos y garantizar que los datos se almacenen de manera eficiente y sin anomalías.
* Se basa en una serie de reglas y principios que se aplican para dividir las tablas de una base de datos en estructuras más pequeñas y relacionadas.
* Es un proceso fundamental en el diseño de bases de datos relacionales. Las BD se normalizan para:
1.- Eliminación de redundancia.
2.- Integridad de los datos
3.- Facilita el mantenimiento y coherencia 
4.- Mejora el rendimiento
5.- Adaptabilidad y escalabilidad
6.- Cumplimiento de estándares

## CARACTERÍSTICAS DEL MODELO RELACIONAL
Cada tabla debe tener un nombre único
• Los datos de cualquier columna corresponden a un solo tipo de dato (por ejemplo cadena,entero, doble).
• Las columnas de una relación se conocen como atributos.
• El orden de los atributos no importa: los atributos no están ordenados.
• Cada atributo de la tabla solo puede tener un valor en cada tupla (fila)
• Cada atributo tiene un nombre único en cada tabla (aunque pueden coincidir en tablasdistintas)
• Cada atributo tiene un dominio.
• Los valores de los atributos son atómicos: en cada tupla (fila), cada atributo (columna) toma un solo valor. Esto aporta a la normalización de la base de datos.
• El orden de las filas no importa
• No se permiten filas repetidas mediante la clave primaría.
• No existen 2 filas en la tabla que sean idénticas.





