# Analisis nivel Colombia
# ST0263 Tópicos especiales en telemática


## Fuentes de datos:

* https://www.datos.gov.co/Salud-y-Protecci-n-Social/Casos-positivos-de-COVID-19-en-Colombia/gt2j-8ykr/data
* https://data.humdata.org/dataset/positive-cases-of-covid-19-in-colombia

## Ingesta y almacenamieno: Datalake S3
  ![col](images/co1.png)
  
## Procesamiento : Analisis exploratorio y descriptivo
  
  Consultas:
  
  * Cantidad de pacientes por cada estado
  ![col](images/c1.PNG)
  
  * Alguna información de los fallecidos
  ![col](images/c2.PNG)
  
  * Cantidad de fallecidos por ciudad
  ![col](images/c3.PNG)
  
  * Cantidad de recuperados por ciudad
  ![col](images/c4.PNG)
  
  * Fechas de diferencia entre los sintomas, el diagnostico y la recuperacion de los pacientes
  ![col](images/c5.PNG)
  
  * Personas agrupadas por el estado en el que se encuentran y la edad
  ![col](images/c6.PNG)
  
  * Alguna información de los asíntomaticos
  ![col](images/c7.PNG)
  
  * Información de las personas que se encuentran bajo cuidados intensivos
  ![col](images/c8.PNG)
  
  * Promedio de edad de los fallecidos por genero
  ![col](images/c9.PNG)
  
  * Cantidad de recuperados por género
  ![col](images/c10.PNG)
  
  * ¿De donde provienen olos contagios?
  ![col](images/c11.PNG)
  
  * ¿Si los casos son importados, de que ciudad vienen mayormente?
  ![col](images/c12.PNG)
  
## Visualizacíon 
  
  * Casos por departamento: Totales(Naranja), Recuperacion(Verde) y Muertes(Rojos)
  ![col](images/co3.png)
  
  * Distribucion de los fallecidos por género
  ![col](images/co4.png)
  
  * Distribucion de los casos totales por género
  ![col](images/co5.png)
  
  * Distribucion de los casos por la atención actual
  ![col](images/co6.png)
  
  * Curva por casos presentados cada mes(sin acumular casos)
  ![col](images/co7.png)
  
  * Curva de los casos fallecidos y casos recuperados , respecto a la curva de casos totales
  ![col](images/co8.png)
  
  * Casos totales reportados por mes, acumulados
  ![col](images/co9.png)
  
  * Casos reportados por edades
  ![col](images/co10.png)
  
  * Distribucion del tipo de caso
  ![col](images/co11.png)
  
  * Ciudades de donde provienen los casos importados 
  ![col](images/co12.png)
  
  * Estadistica de los casos fallecidos y recuperados por cada género
  ![col](images/co13.png)
  
  * Distribución de los estados de los pacientes contagiados
  ![col](images/co14.png)
  
## Notebook, EMR, Spark

Para ver mas detalladamente las consultas, funciones, y el origen de las graficas y visualizaciones acceda al notebook:
[MRjob exercise](mrjob)
