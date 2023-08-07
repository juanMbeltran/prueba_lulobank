# TV Shows Data Analysis

Este proyecto está diseñado para analizar datos de shows de televisión obtenidos de la API de TVmaze. Recoge información como episodios, calificaciones, géneros, horarios, y más, y guarda los datos en diferentes DataFrames. Luego, se utiliza pandas profiling para generar informes HTML que ofrecen un resumen general de cada DataFrame.

## Descripción

El código realiza las siguientes tareas:

1.  Define rutas para almacenar archivos JSON, informes de perfiles y otros datos.
2.  Recopila datos de shows de TV de la API de TVmaze en un rango de fechas determinado.
3.  Almacena los datos recogidos en un archivo JSON.
4.  Lee los datos y los normaliza en varios DataFrames.
5.  Crea informes de perfil para cada DataFrame usando pandas profiling.

## Instalación

Para ejecutar este proyecto, necesitarás tener Python instalado, así como algunas bibliotecas adicionales. Aquí tienes los pasos para instalarlo:

### Pre-requisitos

-   Python 3.x
-   Bibliotecas: os, requests, json, datetime, pandas, pandas_profiling, matplotlib, sklearn, sqlite3, sqlalchemy

### Instrucciones

1.  Clona el repositorio en tu máquina local.
    
2.  Instala las bibliotecas necesarias usando pip:
    
    `pip install requests pandas pandas-profiling matplotlib scikit-learn` 
    
    **Nota**: pandas-profiling será reemplazado por ydata_profiling en futuras versiones. Asegúrate de seguir las advertencias en el código.
    
3.  Ejecuta el script en tu entorno Python preferido.
    

## Uso

Simplemente ejecuta el script y los datos se recopilarán, procesarán y almacenarán en los directorios correspondientes.