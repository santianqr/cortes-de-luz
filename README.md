# Cortes de luz - Bogotá

Scraping web en python para saber qué barrios tienen más cortes de energía y durante cuanto tiempo.

## Descripción

Proyecto de Scraping web avanzado usando python con la libreria Selenium, donde se toman noticias de la web de la alcaldía para ser tratadas y convertirlas en data útil.

## Archivos

- extraccion.ipynb: en este archivo se encuentra el proceso de extracción de la data. Retorna un dataframe con 3 columnas.
- estructurar.ipynb: se estructura la información y se pasa el formato de noticia a columnas utiles y posteriormente un dataframe.
- fix_address.ipynb: arreglos en la data para arreglar la dirección de la persona.

## Siguientes pasos

- usar regex para estructurar la información.
- usar el barrio y localidad para pasar esto a coordenadas latitud, longitud
- dashboard en power BI, en donde se presente los barrios mas afectados y la duración de los cortes.
