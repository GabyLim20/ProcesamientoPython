# Procesamiento Python

## 🎯🚀 Skills

- Python

##  👩🏻‍💻📓✍🏻💡 Pasos a configurar el proyecto:

**1. Instalar las dependencias**
```bash
  import pandas as pd
  import numpy as np
```

**2. Agregar la ruta del archivo**
```bash
  dataset= "/content/drive/MyDrive/dataSet/"
```

## Introducción 📜🛠️

En el ámbito de la seguridad pública, entender la magnitud y las causas de las personas desaparecidas y no localizadas es esencial para mejorar las estrategias de prevención y respuesta ante situaciones de desaparición. Factores como el género, la ubicación geográfica, el contexto social y las circunstancias del caso pueden influir en las probabilidades de desaparición y resolución de estos eventos. Este proyecto se enfoca en analizar un conjunto de datos sobre personas desaparecidas para explorar estos factores y ofrecer una visión más clara de las tendencias y patrones relacionados con los casos no resueltos, con el objetivo de contribuir a políticas públicas más efectivas.

## Objetivo general 🎯🎩🪄

Procesar un conjunto de datos sobre personas desaparecidas permite explorar la relación entre diversos factores como la fecha, hora y lugar en que se vieron por última vez, así como características personales como la edad, sexo, estatura, complexión, etnia y discapacidad. El objetivo es identificar patrones y posibles disparidades en las circunstancias de desaparición según estos factores.

## Objetivos específicos ✎ᝰ➴。

* Limpiar y organizar las columnas seleccionadas
  - (Fecha y Hora  en que se le vio por última vez, País, Entidad, Municipio, Localidad, Nacionalidad, Estatura, Complexión, Sexo, Edad, Descripción de señas particulares, Etnia, Discapacidad, Dependencia que envió la información) para garantizar que los datos estén listos para su análisis.
* Analizar la relación entre la edad, el sexo y la desaparición
    -Investigando si ciertos grupos demográficos son más vulnerables a la desaparición que otros.
* Explorar las posibles correlaciones entre la ubicación geográfica
  - (País, entidad, municipio, localidad) y las desapariciones, con el fin de identificar áreas con mayores tasas de desaparición y posibles factores de riesgo asociados.
* Investigar las características particulares
  - (Estatura, complexión, etnia, discapacidad) de las personas desaparecidas para detectar patrones que puedan ayudar a mejorar las estrategias de prevención y localización.
* Evaluar la influencia de las circunstancias
  - (Hora, fecha, y lugar de la desaparición).
## Planteamiento del problema 🚨📝

La desaparición de personas es un problema que afecta a las víctimas, sus familias y a las autoridades encargadas de la búsqueda. A menudo, las investigaciones se ven limitadas por la falta de información precisa, la escasa coordinación y el uso de métodos tradicionales que no siempre son efectivos. Este proyecto tiene como objetivo procesar un conjunto de datos para identificar patrones y optimizar recursos en la búsqueda, tomando en cuenta factores como género, ubicación geográfica.

## Posibles preguntas de investigación ⁉🕵🏼‍♀️

* ¿En qué columnas hay más datos faltantes o incompletos?
* ¿Hay municipios o entidades específicas donde las desapariciones son más frecuentes?
* ¿Cuál es el rango de edades de las personas desaparecidas en el dataset?
* ¿Cuáles son las fechas de desaparición más recientes y las más antiguas en el dataset?
* ¿Cuáles son las discapacidades más comunes entre las personas desaparecidas?
* ¿Cuál es la distribución de las desapariciones según la etnia de las personas desaparecidas?

## Posible solución 🍃💡

La solución consiste en limpiar y procesar los datos utilizando Python y pandas. Primero, se identificará y manejará la información incompleta o nula, eliminando los valores faltantes según lo que se va a necesitar, también trnsformar los datos tales como fecha para obtener variables como el tiempo transcurrido.
Después se realizarán análisis para identificar patrones y distribuciones de variables clave, como la edad, sexo, ubicación (municipio, país) y características físicas (estatura, complexión). Esto permitirá observar tendencias y correlaciones entre diferentes factores, como la hora o fecha de desaparición y la probabilidad de localización.


## Consideraciones futuras 

Una vez que los datos de los desaparecidos hayan sido procesados y limpiados, se podrán realizar análisis más detallados y profundos sobre los patrones y tendencias en las desapariciones. A partir de estos análisis, se podrán identificar posibles tendencias geográficas o demográficas, y reconocer áreas de alta incidencia que podrían requerir atención urgente.
En futuras etapas, se podrían emplear modelos predictivos para anticipar zonas o grupos de alto riesgo de desapariciones, ayudando a las autoridades y organizaciones a priorizar recursos y estrategias de prevención. Además, los datos recopilados podrían contribuir a la creación de alertas tempranas, mejorando la respuesta ante nuevos casos y potenciando las acciones de búsqueda.


##  ✍🏻📚 Caso de uso:
**Moda General:**

- En esta sección podrás visualizar el valor que aparece con mayor frecuencia en una columna dependiendo el año.
 
<img src="Image/moda.png" width="400" alt="General">

**Genero:**

- En esta sección podrás visualizar las personas desaparecidas conforme a su genero.
  
<img src="Image/genero.png" alt="Genero">

**Edad:**

- En esta sección podrás visualizar el rango de edad.
  
<img src="Image/genero.png" alt="Edad">

**Municipio:**

- En esta sección podrás visualizar cuantas personas por municipio desaparecieron.
  
<img src="Image/municipio.png"  alt="Municipio">

**Etnia:**

- En esta sección podrás visualizar las etnias de los desaparecidos.
  
<img src="Image/etnia.png" alt="Etnia">


## Conclusión 

Al realizar el proyecto se pudo identificar que hay datos que no son precisos, lo que genera que al realizar el análisis existan sesgos en la investigación.
Derivado de esto es importante que las bases de datos puedan homologarse de manera que exista el mínimo margen de error.

El análisis de datos sobre desapariciones en México revela patrones clave:
- Edades predominantes: 31-40 años, con casos desde 1 hasta 99 años.
- Municipios más afectados: Acapulco de Juárez, Zumpango y Abasolo.
- Grupos vulnerables: Las personas de etnias indígenas, como los Mayas y Nahuas, enfrentan un mayor riesgo.
- Datos limitados: Inconsistencias en columnas de edad, estatura y fechas complican el análisis.
El análisis permitió identificar áreas prioritarias para intervenciones preventivas y expuso las necesidades de mejora como la implementación sistemas de captura de datos más precisos y uniformes.


**Recursos Utilizados📚🎓**

[Consumo de datos](https://datamx.io/gl/dataset/?tags=desaparecidos)
