# Análisis a nivel Mundial
# ST0263 Tópicos Especiales en Telemática


## Fuentes de Datos
* https://data.humdata.org/dataset/novel-coronavirus-2019-ncov-cases

## Ingesta y Almacenamiento: Datalake S3
![ww](images/cs31.png)
![ww](images/cs32.png)

## Procesamiento: Análisis exploratorio y descriptivo

### Consultas:

* 20 países con más casos confirmados
![ww](images/pmc.png)

* 20 países con menos casos
![ww](images/pmec.png)

* 20 países con más muertes
![ww](images/pmm.png)

* 20 países con menos muertes
![ww](images/pmem.png)

* 20 países con más recuperados
![ww](images/pmr.png)

* 20 países con menos recuperados
![ww](images/pmer.png)

### Funciones

* Función para extraer el mes
![ww](images/f1.png)

* Función para hallar el continente de un país
![ww](images/f2.png)

* Casos totales, recuperados y fallecidos por continente
![ww](images/f21.png)

* Casos totales, recuperados y fallecidos en el mundo
![ww](images/consultas.png)
![ww](images/consultas2.png)

* Casos totales en el mundo por mes
![ww](images/mcxm.png)

* Casos totales en el mundo por mes
![ww](images/mcxf.png)

## Visualización 

**Casos Actuales en el mundo**

* Código
![ww](images/c1.png)

* Gráfico
![ww](images/g1.png)

**Casos totales, recuperados y fallecidos en el mundo**

* Código
![ww](images/c2.png)

* Gráfico
![ww](images/g2.png)

**Mayor cantidad de casos reportados por mes**

* Código
![ww](images/c3.png)

* Gráfico
![ww](images/g3.png)

**Los 10 países con más casos reportados**

* Código
![ww](images/c4.png)

* Gráfico
![ww](images/g4.png)

**Los 10 países con más casos recuperados**

* Código
![ww](images/c5.png)

* Gráfico
![ww](images/g5.png)

**Los 10 países con más casos de fallecidos**

* Código
![ww](images/c6.png)

* Gráfico
![ww](images/g6.png)

**Curva de los 5 países con mayor cantidad de casos según fecha**

* Código
![ww](images/c7.png)

* Gráfico
![ww](images/g7.png)

## Notebook, EMR, Spark

Para ver más detalladamente las consultas, funciones, código de las gráficas/visualizaciones acceda al notebook:
[covid19analisisglobal.ipynb](covid19analisisglobal.ipynb)
