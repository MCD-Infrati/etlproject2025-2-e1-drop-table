[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-22041afd0340ce965d47ae6ef1cefeee28c7c493a6346c4f15d667ab976d596c.svg)](https://classroom.github.com/a/3pYkVW5Y)
____________________________________________________________________________________

# PROCESO DE EXTRACCIÓN, TRANSFORMACIÓN Y CARGA
Este proyecto hace parte del cuso de Infraestructura y Arquitectura de TI de la Maestría en Ciencia de Datos, Universidad Icesi, Cali Colombia. 

### Estado del proyecto: Completado

## Integrantes:

|Nombre     |  Código   |   Github   |
|---------|-----------------|------------------|
|Davinson Alexander Arteaga Bermudez | A00419669  | https://github.com/DavinsonA |
|Daniela Castaño Medina | A00400872  | https://github.com/danielacmedina |
|Gian Alepsi Mendoza Oviedo | A00419307  | https://github.com/gianmendozax |
|Juan Jose Villegas  | A00422503  | https://github.com/JuanVille15 |


**Docente: Angela Villota Gomez (https://github.com/angievig)**


## Introducción
El objetivo del proyecto es construir un proceso ETL utilizando Azure Data Factory (ADF) para extraer, transformar y cargar datos a partir de una base de datos en formato CSV, un archivo relacional alojado en PostgreSQL y un archivo almacenado en Mongo. El resultado de este trabajo es un archivo CSV con los registros transformados y unificados.


### Métodos usados
* Procesos ETL
* Análisis Exploratorio
* Transformaciones en ADF
* Consultas SQL
  

### Tecnologías 
* Azure Data Factory
* Python
* PostgreSQL
* MongoDB
* GitHub Classroom


## Descripción del proyecto
En este proyecto se contruye un pipeline ETL en Azure Data Factory el cual tiene como objetivo integrar datos de:

* BD Ames (SQL): tablas relacionales con información detallada de propiedades.
* Archivos CSV: fuentes estructuradas con información general de las propiedades.
* MongoDB: datos no relacionales correpondientes a características adicionales de las propiedades.

Las fuentes cuentan con una columna de identificación (PID), la cual permite realizar la integración entre las bases de datos de manera consistente. El proceso desarrollado incluye:

* Extracción desde las tres fuentes.
* Validación, limpieza y estandarización de los registros..
* Transformación en Data Flows y consultas SQL según los requisitos del archivo esperado.
* Unificación de la información.
* Generación del archivo final salida.csv.



